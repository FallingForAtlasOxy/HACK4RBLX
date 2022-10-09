local EnemiesFolder = workspace.Enemies
local Players = game:GetService("Players")
local Player = Players.LocalPlayer
local Mouse = Player:GetMouse()
local RunService = game:GetService("RunService")

local GetClosestToCursor = function()
   local closestDistance = math.huge
   local closestEnemy = nil

   for _, enemy in pairs(EnemiesFolder:GetChildren()) do
       if not enemy:FindFirstChild("Head") then continue end
       if not enemy:FindFirstChildOfClass("Humanoid") then continue end
       if enemy.Humanoid.Health <= 0 then continue end

       local screenPos, visible = workspace.CurrentCamera:WorldToViewportPoint(enemy.Head.Position)

       local distance = (Vector2.new(Mouse.X, Mouse.Y) - Vector2.new(screenPos.X, screenPos.Y)).Magnitude
       if distance < closestDistance then
           closestEnemy = enemy
           closestDistance = distance
       end
   end

   return closestEnemy
end

local ClosestEnemy = GetClosestToCursor()
RunService.Stepped:Connect(function(time, deltaTime)
   ClosestEnemy = GetClosestToCursor()
end)

local old; old = hookmetamethod(game, '__namecall', function(this, ...)
  local args = {...}
  local method = getnamecallmethod()

  if not checkcaller() and method == 'FireServer' and this.Name == "WeaponHit" then
       if ClosestEnemy then
           args[2].part = ClosestEnemy.Head
       end

   end

  return old(this, unpack(args))
end)

---------------
local old; old = hookmetamethod(game, "__index", function(this, index)
  if not checkcaller() and tostring(this) == "CurrentAmmo" and index == "Value" then
      return 2
  end

  return old(this, index)
end)

----------------

local Player = game:GetService("Players").LocalPlayer

local Mod = function(tool)
   for i, v in pairs(tool.Configuration:GetChildren()) do
       if v.Name == "RecoilMin" or v.Name == "RecoilMax" or v.Name == "ShotCooldown" then
           v.Value = 0
       elseif v.Name == "HitDamage" then
           v.Value = math.huge
       end
   end
end

Player.Character.ChildAdded:Connect(function(child)
   if child.ClassName == "Tool" and child:FindFirstChild("Configuration") then
       Mod(child)
   end
end)

Player.CharacterAdded:Connect(function(character)
   character.ChildAdded:Connect(function(child)
       if child.ClassName == "Tool" and child:FindFirstChild("Configuration") then
           Mod(child)
       end
   end)
end)
