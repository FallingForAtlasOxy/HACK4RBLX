--Made by EFTPMC--

--PowerFightingSim--

-- Instances:

local Main = Instance.new("ScreenGui")

local TopBar = Instance.new("Frame")

local AutoFarm = Instance.new("Frame")

local TextLabel = Instance.new("TextLabel")

local Layout = Instance.new("Frame")

local Quests = Instance.new("TextButton")

local Endurance = Instance.new("TextButton")

local Strength = Instance.new("TextButton")

local Psychic = Instance.new("TextButton")

local Speed = Instance.new("TextButton")

local Rank = Instance.new("TextButton")

local UIGridLayout = Instance.new("UIGridLayout")

local Power = Instance.new("TextButton")

local X = Instance.new("TextButton")

local Strength_2 = Instance.new("Frame")

local TextLabel_2 = Instance.new("TextLabel")

local Layout_2 = Instance.new("Frame")

local _100 = Instance.new("TextButton")

local UIGridLayout_2 = Instance.new("UIGridLayout")

local _1k = Instance.new("TextButton")

local _10k = Instance.new("TextButton")

local _100k = Instance.new("TextButton")

local _5m = Instance.new("TextButton")

local _500m = Instance.new("TextButton")

local X_2 = Instance.new("TextButton")

local Endurance_2 = Instance.new("Frame")

local TextLabel_3 = Instance.new("TextLabel")

local Layout_3 = Instance.new("Frame")

local _100_2 = Instance.new("TextButton")

local UIGridLayout_3 = Instance.new("UIGridLayout")

local _1k_2 = Instance.new("TextButton")

local _10k_2 = Instance.new("TextButton")

local _100k_2 = Instance.new("TextButton")

local _5m_2 = Instance.new("TextButton")

local _500m_2 = Instance.new("TextButton")

local X_3 = Instance.new("TextButton")

local Psychic_2 = Instance.new("Frame")

local TextLabel_4 = Instance.new("TextLabel")

local Layout_4 = Instance.new("Frame")

local UIGridLayout_4 = Instance.new("UIGridLayout")

local _1k_3 = Instance.new("TextButton")

local _10k_3 = Instance.new("TextButton")

local _100k_3 = Instance.new("TextButton")

local _5m_3 = Instance.new("TextButton")

local _500m_3 = Instance.new("TextButton")

local X_4 = Instance.new("TextButton")

--[[

	Properties:--]]

Main.Name = "Main"

Main.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")

Main.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Main.ResetOnSpawn = false

TopBar.Name = "TopBar"

TopBar.Parent = Main

TopBar.BackgroundColor3 = Color3.new(1, 1, 1)

TopBar.BackgroundTransparency = 1

TopBar.Position = UDim2.new(0.00999999978, 0, 0.0199999996, 0)

TopBar.Size = UDim2.new(0, 1243, 0, 40)

AutoFarm.Name = "AutoFarm"

AutoFarm.Parent = TopBar

AutoFarm.Active = true

AutoFarm.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)

AutoFarm.BorderColor3 = Color3.new(0.105882, 0.164706, 0.207843)

AutoFarm.BorderSizePixel = 0

AutoFarm.Size = UDim2.new(0, 124, 0, 16)

TextLabel.Parent = AutoFarm

TextLabel.BackgroundColor3 = Color3.new(0, 0, 0)

TextLabel.BackgroundTransparency = 0.80000001192093

TextLabel.Size = UDim2.new(0, 124, 0, 16)

TextLabel.Font = Enum.Font.SourceSans

TextLabel.Text = "Auto-Farm"

TextLabel.TextColor3 = Color3.new(1, 1, 1)

TextLabel.TextSize = 14

Layout.Name = "Layout"

Layout.Parent = AutoFarm

Layout.BackgroundColor3 = Color3.new(1, 1, 1)

Layout.BackgroundTransparency = 1

Layout.BorderSizePixel = 0

Layout.Position = UDim2.new(0, 0, 0.090000011, 0)

Layout.Size = UDim2.new(0, 0, 0, 10)

Quests.Name = "Quests"

Quests.Parent = Layout

Quests.BackgroundColor3 = Color3.new(1, 1, 1)

Quests.BackgroundTransparency = 1

Quests.BorderSizePixel = 0

Quests.LayoutOrder = 1

Quests.Size = UDim2.new(0, 124, 0, 21)

Quests.Visible = false

Quests.Font = Enum.Font.SourceSans

Quests.Text = "Quests"

Quests.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Quests.TextSize = 14

Endurance.Name = "Endurance"

Endurance.Parent = Layout

Endurance.BackgroundColor3 = Color3.new(1, 1, 1)

Endurance.BackgroundTransparency = 1

Endurance.BorderSizePixel = 0

Endurance.LayoutOrder = 3

Endurance.Size = UDim2.new(0, 124, 0, 21)

Endurance.Visible = false

Endurance.Font = Enum.Font.SourceSans

Endurance.Text = "Endurance"

Endurance.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Endurance.TextSize = 14

Strength.Name = "Strength"

Strength.Parent = Layout

Strength.BackgroundColor3 = Color3.new(1, 1, 1)

Strength.BackgroundTransparency = 1

Strength.BorderSizePixel = 0

Strength.LayoutOrder = 4

Strength.Size = UDim2.new(0, 124, 0, 21)

Strength.Visible = false

Strength.Font = Enum.Font.SourceSans

Strength.Text = "Strength"

Strength.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Strength.TextSize = 14

Psychic.Name = "Psychic"

Psychic.Parent = Layout

Psychic.BackgroundColor3 = Color3.new(1, 1, 1)

Psychic.BackgroundTransparency = 1

Psychic.BorderSizePixel = 0

Psychic.LayoutOrder = 5

Psychic.Size = UDim2.new(0, 124, 0, 21)

Psychic.Visible = false

Psychic.Font = Enum.Font.SourceSans

Psychic.Text = "Psychic"

Psychic.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Psychic.TextSize = 14

Speed.Name = "Speed"

Speed.Parent = Layout

Speed.BackgroundColor3 = Color3.new(1, 1, 1)

Speed.BackgroundTransparency = 1

Speed.BorderSizePixel = 0

Speed.LayoutOrder = 6

Speed.Size = UDim2.new(0, 124, 0, 21)

Speed.Visible = false

Speed.Font = Enum.Font.SourceSans

Speed.Text = "Speed"

Speed.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Speed.TextSize = 14

Rank.Name = "Rank"

Rank.Parent = Layout

Rank.BackgroundColor3 = Color3.new(1, 1, 1)

Rank.BackgroundTransparency = 1

Rank.BorderSizePixel = 0

Rank.LayoutOrder = 2

Rank.Size = UDim2.new(0, 124, 0, 21)

Rank.Visible = false

Rank.Font = Enum.Font.SourceSans

Rank.Text = "Rank"

Rank.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Rank.TextSize = 14

UIGridLayout.Parent = Layout

UIGridLayout.SortOrder = Enum.SortOrder.LayoutOrder

UIGridLayout.CellSize = UDim2.new(0, 124, 0, 21)

Power.Name = "Power"

Power.Parent = Layout

Power.BackgroundColor3 = Color3.new(1, 1, 1)

Power.BackgroundTransparency = 1

Power.BorderSizePixel = 0

Power.Size = UDim2.new(0, 124, 0, 21)

Power.Visible = false

Power.Font = Enum.Font.SourceSans

Power.Text = "On/Off"

Power.TextColor3 = Color3.new(1, 0.239216, 0.25098)

Power.TextSize = 14

X.Name = "X"

X.Parent = AutoFarm

X.BackgroundColor3 = Color3.new(1, 1, 1)

X.BackgroundTransparency = 1

X.BorderSizePixel = 0

X.Position = UDim2.new(0.875, 0, 0, 0)

X.Size = UDim2.new(0, 15, 0, 15)

X.Font = Enum.Font.SourceSans

X.Text = "V"

X.TextColor3 = Color3.new(1, 1, 1)

X.TextSize = 14

Strength_2.Name = "Strength"

Strength_2.Parent = TopBar

Strength_2.Active = true

Strength_2.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)

Strength_2.BorderColor3 = Color3.new(0.105882, 0.164706, 0.207843)

Strength_2.BorderSizePixel = 0

Strength_2.Position = UDim2.new(0, 150, 0, 0)

Strength_2.Size = UDim2.new(0, 124, 0, 16)

TextLabel_2.Parent = Strength_2

TextLabel_2.BackgroundColor3 = Color3.new(0, 0, 0)

TextLabel_2.BackgroundTransparency = 0.80000001192093

TextLabel_2.Size = UDim2.new(0, 124, 0, 16)

TextLabel_2.Font = Enum.Font.SourceSans

TextLabel_2.Text = "Strength"

TextLabel_2.TextColor3 = Color3.new(1, 1, 1)

TextLabel_2.TextSize = 14

Layout_2.Name = "Layout"

Layout_2.Parent = Strength_2

Layout_2.BackgroundColor3 = Color3.new(1, 1, 1)

Layout_2.BackgroundTransparency = 1

Layout_2.BorderSizePixel = 0

Layout_2.Position = UDim2.new(0, 0, 0.090000011, 0)

Layout_2.Size = UDim2.new(0, 0, 0, 10)

_100.Name = "100"

_100.Parent = Layout_2

_100.BackgroundColor3 = Color3.new(1, 1, 1)

_100.BackgroundTransparency = 1

_100.BorderSizePixel = 0

_100.LayoutOrder = 3

_100.Size = UDim2.new(0, 124, 0, 21)

_100.Visible = false

_100.Font = Enum.Font.SourceSans

_100.Text = "100"

_100.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_100.TextSize = 14

UIGridLayout_2.Parent = Layout_2

UIGridLayout_2.SortOrder = Enum.SortOrder.LayoutOrder

UIGridLayout_2.CellSize = UDim2.new(0, 124, 0, 21)

_1k.Name = "1k"

_1k.Parent = Layout_2

_1k.BackgroundColor3 = Color3.new(1, 1, 1)

_1k.BackgroundTransparency = 1

_1k.BorderSizePixel = 0

_1k.LayoutOrder = 3

_1k.Size = UDim2.new(0, 124, 0, 21)

_1k.Visible = false

_1k.Font = Enum.Font.SourceSans

_1k.Text = "1k"

_1k.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_1k.TextSize = 14

_10k.Name = "10k"

_10k.Parent = Layout_2

_10k.BackgroundColor3 = Color3.new(1, 1, 1)

_10k.BackgroundTransparency = 1

_10k.BorderSizePixel = 0

_10k.LayoutOrder = 3

_10k.Size = UDim2.new(0, 124, 0, 21)

_10k.Visible = false

_10k.Font = Enum.Font.SourceSans

_10k.Text = "10k"

_10k.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_10k.TextSize = 14

_100k.Name = "100k"

_100k.Parent = Layout_2

_100k.BackgroundColor3 = Color3.new(1, 1, 1)

_100k.BackgroundTransparency = 1

_100k.BorderSizePixel = 0

_100k.LayoutOrder = 3

_100k.Size = UDim2.new(0, 124, 0, 21)

_100k.Visible = false

_100k.Font = Enum.Font.SourceSans

_100k.Text = "100k"

_100k.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_100k.TextSize = 14

_5m.Name = "5m"

_5m.Parent = Layout_2

_5m.BackgroundColor3 = Color3.new(1, 1, 1)

_5m.BackgroundTransparency = 1

_5m.BorderSizePixel = 0

_5m.LayoutOrder = 3

_5m.Size = UDim2.new(0, 124, 0, 21)

_5m.Visible = false

_5m.Font = Enum.Font.SourceSans

_5m.Text = "5m"

_5m.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_5m.TextSize = 14

_500m.Name = "500m"

_500m.Parent = Layout_2

_500m.BackgroundColor3 = Color3.new(1, 1, 1)

_500m.BackgroundTransparency = 1

_500m.BorderSizePixel = 0

_500m.LayoutOrder = 3

_500m.Size = UDim2.new(0, 124, 0, 21)

_500m.Visible = false

_500m.Font = Enum.Font.SourceSans

_500m.Text = "500m"

_500m.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_500m.TextSize = 14

X_2.Name = "X"

X_2.Parent = Strength_2

X_2.BackgroundColor3 = Color3.new(1, 1, 1)

X_2.BackgroundTransparency = 1

X_2.BorderSizePixel = 0

X_2.Position = UDim2.new(0.875, 0, 0, 0)

X_2.Size = UDim2.new(0, 15, 0, 15)

X_2.Font = Enum.Font.SourceSans

X_2.Text = "V"

X_2.TextColor3 = Color3.new(1, 1, 1)

X_2.TextSize = 14

Endurance_2.Name = "Endurance"

Endurance_2.Parent = TopBar

Endurance_2.Active = true

Endurance_2.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)

Endurance_2.BorderColor3 = Color3.new(0.105882, 0.164706, 0.207843)

Endurance_2.BorderSizePixel = 0

Endurance_2.Position = UDim2.new(0, 300, 0, 0)

Endurance_2.Size = UDim2.new(0, 124, 0, 16)

TextLabel_3.Parent = Endurance_2

TextLabel_3.BackgroundColor3 = Color3.new(0, 0, 0)

TextLabel_3.BackgroundTransparency = 0.80000001192093

TextLabel_3.Size = UDim2.new(0, 124, 0, 16)

TextLabel_3.Font = Enum.Font.SourceSans

TextLabel_3.Text = "Endurance"

TextLabel_3.TextColor3 = Color3.new(1, 1, 1)

TextLabel_3.TextSize = 14

Layout_3.Name = "Layout"

Layout_3.Parent = Endurance_2

Layout_3.BackgroundColor3 = Color3.new(1, 1, 1)

Layout_3.BackgroundTransparency = 1

Layout_3.BorderSizePixel = 0

Layout_3.Position = UDim2.new(0, 0, 0.090000011, 0)

Layout_3.Size = UDim2.new(0, 0, 0, 10)

_100_2.Name = "100"

_100_2.Parent = Layout_3

_100_2.BackgroundColor3 = Color3.new(1, 1, 1)

_100_2.BackgroundTransparency = 1

_100_2.BorderSizePixel = 0

_100_2.LayoutOrder = 3

_100_2.Size = UDim2.new(0, 124, 0, 21)

_100_2.Visible = false

_100_2.Font = Enum.Font.SourceSans

_100_2.Text = "100"

_100_2.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_100_2.TextSize = 14

UIGridLayout_3.Parent = Layout_3

UIGridLayout_3.SortOrder = Enum.SortOrder.LayoutOrder

UIGridLayout_3.CellSize = UDim2.new(0, 124, 0, 21)

_1k_2.Name = "1k"

_1k_2.Parent = Layout_3

_1k_2.BackgroundColor3 = Color3.new(1, 1, 1)

_1k_2.BackgroundTransparency = 1

_1k_2.BorderSizePixel = 0

_1k_2.LayoutOrder = 3

_1k_2.Size = UDim2.new(0, 124, 0, 21)

_1k_2.Visible = false

_1k_2.Font = Enum.Font.SourceSans

_1k_2.Text = "1k"

_1k_2.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_1k_2.TextSize = 14

_10k_2.Name = "10k"

_10k_2.Parent = Layout_3

_10k_2.BackgroundColor3 = Color3.new(1, 1, 1)

_10k_2.BackgroundTransparency = 1

_10k_2.BorderSizePixel = 0

_10k_2.LayoutOrder = 3

_10k_2.Size = UDim2.new(0, 124, 0, 21)

_10k_2.Visible = false

_10k_2.Font = Enum.Font.SourceSans

_10k_2.Text = "10k"

_10k_2.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_10k_2.TextSize = 14

_100k_2.Name = "100k"

_100k_2.Parent = Layout_3

_100k_2.BackgroundColor3 = Color3.new(1, 1, 1)

_100k_2.BackgroundTransparency = 1

_100k_2.BorderSizePixel = 0

_100k_2.LayoutOrder = 3

_100k_2.Size = UDim2.new(0, 124, 0, 21)

_100k_2.Visible = false

_100k_2.Font = Enum.Font.SourceSans

_100k_2.Text = "100k"

_100k_2.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_100k_2.TextSize = 14

_5m_2.Name = "5m"

_5m_2.Parent = Layout_3

_5m_2.BackgroundColor3 = Color3.new(1, 1, 1)

_5m_2.BackgroundTransparency = 1

_5m_2.BorderSizePixel = 0

_5m_2.LayoutOrder = 3

_5m_2.Size = UDim2.new(0, 124, 0, 21)

_5m_2.Visible = false

_5m_2.Font = Enum.Font.SourceSans

_5m_2.Text = "5m"

_5m_2.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_5m_2.TextSize = 14

_500m_2.Name = "500m"

_500m_2.Parent = Layout_3

_500m_2.BackgroundColor3 = Color3.new(1, 1, 1)

_500m_2.BackgroundTransparency = 1

_500m_2.BorderSizePixel = 0

_500m_2.LayoutOrder = 3

_500m_2.Size = UDim2.new(0, 124, 0, 21)

_500m_2.Visible = false

_500m_2.Font = Enum.Font.SourceSans

_500m_2.Text = "500m"

_500m_2.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_500m_2.TextSize = 14

X_3.Name = "X"

X_3.Parent = Endurance_2

X_3.BackgroundColor3 = Color3.new(1, 1, 1)

X_3.BackgroundTransparency = 1

X_3.BorderSizePixel = 0

X_3.Position = UDim2.new(0.875, 0, 0, 0)

X_3.Size = UDim2.new(0, 15, 0, 15)

X_3.Font = Enum.Font.SourceSans

X_3.Text = "V"

X_3.TextColor3 = Color3.new(1, 1, 1)

X_3.TextSize = 14

Psychic_2.Name = "Psychic"

Psychic_2.Parent = TopBar

Psychic_2.Active = true

Psychic_2.BackgroundColor3 = Color3.new(0.105882, 0.164706, 0.207843)

Psychic_2.BorderColor3 = Color3.new(0.105882, 0.164706, 0.207843)

Psychic_2.BorderSizePixel = 0

Psychic_2.Position = UDim2.new(0, 450, 0, 0)

Psychic_2.Size = UDim2.new(0, 124, 0, 16)

TextLabel_4.Parent = Psychic_2

TextLabel_4.BackgroundColor3 = Color3.new(0, 0, 0)

TextLabel_4.BackgroundTransparency = 0.80000001192093

TextLabel_4.Size = UDim2.new(0, 124, 0, 16)

TextLabel_4.Font = Enum.Font.SourceSans

TextLabel_4.Text = "Psychic"

TextLabel_4.TextColor3 = Color3.new(1, 1, 1)

TextLabel_4.TextSize = 14

Layout_4.Name = "Layout"

Layout_4.Parent = Psychic_2

Layout_4.BackgroundColor3 = Color3.new(1, 1, 1)

Layout_4.BackgroundTransparency = 1

Layout_4.BorderSizePixel = 0

Layout_4.Position = UDim2.new(0, 0, 0.090000011, 0)

Layout_4.Size = UDim2.new(0, 0, 0, 10)

UIGridLayout_4.Parent = Layout_4

UIGridLayout_4.SortOrder = Enum.SortOrder.LayoutOrder

UIGridLayout_4.CellSize = UDim2.new(0, 124, 0, 21)

_1k_3.Name = "1k"

_1k_3.Parent = Layout_4

_1k_3.BackgroundColor3 = Color3.new(1, 1, 1)

_1k_3.BackgroundTransparency = 1

_1k_3.BorderSizePixel = 0

_1k_3.LayoutOrder = 3

_1k_3.Size = UDim2.new(0, 124, 0, 21)

_1k_3.Visible = false

_1k_3.Font = Enum.Font.SourceSans

_1k_3.Text = "1k"

_1k_3.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_1k_3.TextSize = 14

_10k_3.Name = "10k"

_10k_3.Parent = Layout_4

_10k_3.BackgroundColor3 = Color3.new(1, 1, 1)

_10k_3.BackgroundTransparency = 1

_10k_3.BorderSizePixel = 0

_10k_3.LayoutOrder = 3

_10k_3.Size = UDim2.new(0, 124, 0, 21)

_10k_3.Visible = false

_10k_3.Font = Enum.Font.SourceSans

_10k_3.Text = "10k"

_10k_3.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_10k_3.TextSize = 14

_100k_3.Name = "100k"

_100k_3.Parent = Layout_4

_100k_3.BackgroundColor3 = Color3.new(1, 1, 1)

_100k_3.BackgroundTransparency = 1

_100k_3.BorderSizePixel = 0

_100k_3.LayoutOrder = 3

_100k_3.Size = UDim2.new(0, 124, 0, 21)

_100k_3.Visible = false

_100k_3.Font = Enum.Font.SourceSans

_100k_3.Text = "100k"

_100k_3.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_100k_3.TextSize = 14

_5m_3.Name = "5m"

_5m_3.Parent = Layout_4

_5m_3.BackgroundColor3 = Color3.new(1, 1, 1)

_5m_3.BackgroundTransparency = 1

_5m_3.BorderSizePixel = 0

_5m_3.LayoutOrder = 3

_5m_3.Size = UDim2.new(0, 124, 0, 21)

_5m_3.Visible = false

_5m_3.Font = Enum.Font.SourceSans

_5m_3.Text = "5m"

_5m_3.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_5m_3.TextSize = 14

_500m_3.Name = "500m"

_500m_3.Parent = Layout_4

_500m_3.BackgroundColor3 = Color3.new(1, 1, 1)

_500m_3.BackgroundTransparency = 1

_500m_3.BorderSizePixel = 0

_500m_3.LayoutOrder = 3

_500m_3.Size = UDim2.new(0, 124, 0, 21)

_500m_3.Visible = false

_500m_3.Font = Enum.Font.SourceSans

_500m_3.Text = "500m"

_500m_3.TextColor3 = Color3.new(1, 0.239216, 0.25098)

_500m_3.TextSize = 14

X_4.Name = "X"

X_4.Parent = Psychic_2

X_4.BackgroundColor3 = Color3.new(1, 1, 1)

X_4.BackgroundTransparency = 1

X_4.BorderSizePixel = 0

X_4.Position = UDim2.new(0.875, 0, 0, 0)

X_4.Size = UDim2.new(0, 15, 0, 15)

X_4.Font = Enum.Font.SourceSans

X_4.Text = "V"

X_4.TextColor3 = Color3.new(1, 1, 1)

X_4.TextSize = 14

--[[

	 Scripts:

--]]

local function JHCIO_fake_script() -- Layout.Script 

	local script = Instance.new('Script', Layout)

	--Variables--

	local A_1 = "Strength"

	local A_2 = "Endurance"

	local A_3 = "Psychic"

	local A_4 = "GamesReborn"

	local A_5 = "DailyStrength"

	local A_6 = "DailyEndurance"

	local A_7 = "DailyPsychic"

	local A_8 = "StrengthMultiplier"

	local A_9 = "PsychicMultiplier"

	local A_10 = "EnduranceMultiplier"

	local A_11 = "SpeedMultiplier"

	

	local Event = game:GetService("ReplicatedStorage").Events.Train

	local Event1 = game:GetService("ReplicatedStorage").Events.Quest

	local Event2 = game:GetService("ReplicatedStorage").Functions.Multiplier

	local Event3 = game:GetService("ReplicatedStorage").Functions.BuyRank

	local Power = script.Parent.Power

	local Quests = script.Parent.Quests

	local Endurance = script.Parent.Endurance

	local Strength = script.Parent.Strength

	local Psychic = script.Parent.Psychic

	local Speed = script.Parent.Speed

	local Rank = script.Parent.Rank

	local powerSwitch = false

	local switch1 = false

	--Variables--

	

	--Functions--

	spawn(function()

		while true do

			while switch1 == true do

				Event:FireServer(A_1)

				Event:FireServer(A_2)

				Event:FireServer(A_3)

				wait(1)

			end

			wait()

		end

	end)

	--Functions--

	

	--Switches--

	Power.MouseButton1Click:Connect(function()

		if powerSwitch == false then

			switch1 = true

			Power.TextColor3 = Color3.fromRGB(13, 208, 0)

			wait(1)

			powerSwitch = true

		elseif powerSwitch == true then

			switch1 = false

			Power.TextColor3 = Color3.fromRGB(255, 61, 64)

			wait(1)

			powerSwitch = false

		end

	end)

	Quests.MouseButton1Click:Connect(function()

			Quests.TextColor3 = Color3.fromRGB(13, 208, 0)

				Event1:FireServer(A_4)

				Event1:FireServer(A_5)

				Event1:FireServer(A_6)

				Event1:FireServer(A_7)

			wait(.1)

			Quests.TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	Endurance.MouseButton1Click:Connect(function()

			Endurance.TextColor3 = Color3.fromRGB(13, 208, 0)

				Event2:InvokeServer(A_10)

			wait(.1)

			Endurance.TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	Strength.MouseButton1Click:Connect(function()

			Strength.TextColor3 = Color3.fromRGB(13, 208, 0)

				Event2:InvokeServer(A_8)

			wait(.1)

			Strength.TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	Psychic.MouseButton1Click:Connect(function()

			Psychic.TextColor3 = Color3.fromRGB(13, 208, 0)

				Event2:InvokeServer(A_9)

			wait(.1)

			Psychic.TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	Speed.MouseButton1Click:Connect(function()

			Speed.TextColor3 = Color3.fromRGB(13, 208, 0)

				Event2:InvokeServer(A_11)

			wait(.1)

			Speed.TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	Rank.MouseButton1Click:Connect(function()

			Rank.TextColor3 = Color3.fromRGB(13, 208, 0)

				Event3:InvokeServer()

			wait(.1)

			Rank.TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	--Switches--

end

coroutine.wrap(JHCIO_fake_script)()

local function CBWHA_fake_script() -- AutoFarm.Script 

	local script = Instance.new('Script', AutoFarm)

	local X = script.Parent.X

	local AutoFarm = script.Parent

	local Layout = AutoFarm.Layout

	local switch = false

	X.MouseButton1Click:Connect(function()

		if switch == false then

			AutoFarm:TweenSize(UDim2.new(0, 124,0, 207))

			Layout:TweenSize(UDim2.new(0,0,0,10))

			X.Text = "^"

			wait(1)

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = true

				end

			end

			switch = true

		elseif switch == true then

			AutoFarm:TweenSize(UDim2.new(0, 124,0, 16))

			Layout:TweenSize(UDim2.new(0, 124,0, 188))

			X.Text = "V"

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = false

				end

			end

			wait(1)

			switch = false

		end

	end)

end

coroutine.wrap(CBWHA_fake_script)()

local function NFZSWK_fake_script() -- Layout_2.Script 

	local script = Instance.new('Script', Layout_2)

	

	--Switches--

	script.Parent['100'].MouseButton1Click:Connect(function()

			script.Parent['100'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-282.303162, 89.2314529, -150.449631)

			wait(.1)

			script.Parent['100'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['1k'].MouseButton1Click:Connect(function()

			script.Parent['1k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-778.789734, 70.5612411, -354.488922)

			wait(.1)

			script.Parent['1k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['10k'].MouseButton1Click:Connect(function()

			script.Parent['10k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-135.344543, 81.7630997, -424.823425)

			wait(.1)

			script.Parent['10k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['100k'].MouseButton1Click:Connect(function()

			script.Parent['100k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-962.245911, 80.1975708, -172.509216)

			wait(.1)

			script.Parent['100k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['5m'].MouseButton1Click:Connect(function()

			script.Parent['5m'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-665.387207, 86.1773148, -1048.65759)

			wait(.1)

			script.Parent['5m'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['500m'].MouseButton1Click:Connect(function()

			script.Parent['500m'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(127.35659, 68.2385941, -509.417145)

			wait(.1)

			script.Parent['500m'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	

	--Switches--

end

coroutine.wrap(NFZSWK_fake_script)()

local function ZCOG_fake_script() -- Strength_2.Script 

	local script = Instance.new('Script', Strength_2)

	local X = script.Parent.X

	local Strength = script.Parent

	local Layout = Strength.Layout

	local switch = false

	X.MouseButton1Click:Connect(function()

		if switch == false then

			Strength:TweenSize(UDim2.new(0, 124,0, 175))

			Layout:TweenSize(UDim2.new(0,0,0,10))

			X.Text = "^"

			wait(1)

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = true

				end

			end

			switch = true

		elseif switch == true then

			Strength:TweenSize(UDim2.new(0, 124,0, 16))

			Layout:TweenSize(UDim2.new(0, 124,0, 188))

			X.Text = "V"

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = false

				end

			end

			wait(1)

			switch = false

		end

	end)

end

coroutine.wrap(ZCOG_fake_script)()

local function LOTJVI_fake_script() -- Layout_3.Script 

	local script = Instance.new('Script', Layout_3)

	

	--Switches--

	script.Parent['100'].MouseButton1Click:Connect(function()

			script.Parent['100'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-757.719727, 70.3633652, -616.067444)

			wait(.1)

			script.Parent['100'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['1k'].MouseButton1Click:Connect(function()

			script.Parent['1k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-774.234741, 70.5612411, -392.441528)

			wait(.1)

			script.Parent['1k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['10k'].MouseButton1Click:Connect(function()

			script.Parent['10k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(242.560959, 70.3633652, -313.201782)

			wait(.1)

			script.Parent['10k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['100k'].MouseButton1Click:Connect(function()

			script.Parent['100k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(191.853943, 61.5814247, -225.951813)

			wait(.1)

			script.Parent['100k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['5m'].MouseButton1Click:Connect(function()

			script.Parent['5m'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-626.927612, 80.7909851, -34.5663109)

			wait(.1)

			script.Parent['5m'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['500m'].MouseButton1Click:Connect(function()

			script.Parent['500m'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-729.13446, 80.5644073, -55.5897675)

			wait(.1)

			script.Parent['500m'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	

	--Switches--

end

coroutine.wrap(LOTJVI_fake_script)()

local function WJHHB_fake_script() -- Endurance_2.Script 

	local script = Instance.new('Script', Endurance_2)

	local X = script.Parent.X

	local Strength = script.Parent

	local Layout = Strength.Layout

	local switch = false

	X.MouseButton1Click:Connect(function()

		if switch == false then

			Strength:TweenSize(UDim2.new(0, 124,0, 175))

			Layout:TweenSize(UDim2.new(0,0,0,10))

			X.Text = "^"

			wait(1)

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = true

				end

			end

			switch = true

		elseif switch == true then

			Strength:TweenSize(UDim2.new(0, 124,0, 16))

			Layout:TweenSize(UDim2.new(0, 124,0, 188))

			X.Text = "V"

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = false

				end

			end

			wait(1)

			switch = false

		end

	end)

end

coroutine.wrap(WJHHB_fake_script)()

local function LWJPD_fake_script() -- Layout_4.Script 

	local script = Instance.new('Script', Layout_4)

	

	--Switches--

	script.Parent['1k'].MouseButton1Click:Connect(function()

			script.Parent['1k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-882.282166, 72.0333939, -435.8172)

			wait(.1)

			script.Parent['1k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['10k'].MouseButton1Click:Connect(function()

			script.Parent['10k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-890.757568, 104.813324, -461.94696)

			wait(.1)

			script.Parent['10k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['100k'].MouseButton1Click:Connect(function()

			script.Parent['100k'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(178.4478, 43.3183556, -516.21991)

			wait(.1)

			script.Parent['100k'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['5m'].MouseButton1Click:Connect(function()

			script.Parent['5m'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(-842.758545, 70.2589874, -28.3897324)

			wait(.1)

			script.Parent['5m'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	script.Parent['500m'].MouseButton1Click:Connect(function()

			script.Parent['500m'].TextColor3 = Color3.fromRGB(13, 208, 0)

				game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(393.733704, 162.158066, -526.994812)

			wait(.1)

			script.Parent['500m'].TextColor3 = Color3.fromRGB(255, 61, 64)

	end)

	

	--Switches--

end

coroutine.wrap(LWJPD_fake_script)()

local function DYCFGUW_fake_script() -- Psychic_2.Script 

	local script = Instance.new('Script', Psychic_2)

	local X = script.Parent.X

	local Strength = script.Parent

	local Layout = Strength.Layout

	local switch = false

	X.MouseButton1Click:Connect(function()

		if switch == false then

			Strength:TweenSize(UDim2.new(0, 124,0, 150))

			Layout:TweenSize(UDim2.new(0,0,0,10))

			X.Text = "^"

			wait(1)

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = true

				end

			end

			switch = true

		elseif switch == true then

			Strength:TweenSize(UDim2.new(0, 124,0, 16))

			Layout:TweenSize(UDim2.new(0, 124,0, 188))

			X.Text = "V"

			for key, buttons in pairs(Layout:GetChildren()) do

				if buttons:IsA("TextButton") then

					buttons.Visible = false

				end

			end

			wait(1)

			switch = false

		end

	end)

end

coroutine.wrap(DYCFGUW_fake_script)()

local function HNCMCC_fake_script() -- Main.Anti-Afk 

	local script = Instance.new('LocalScript', Main)

	local vu = game:GetService("VirtualUser")

	game:GetService("Players").LocalPlayer.Idled:connect(function()

	   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

	   wait(1)

	   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)

	end)

end

coroutine.wrap(HNCMCC_fake_script)()

local function RMDWM_fake_script() -- Main.Draggable 

	local script = Instance.new('LocalScript', Main)

	script.Parent.TopBar.AutoFarm.Draggable = true

	script.Parent.TopBar.Endurance.Draggable = true

	script.Parent.TopBar.Psychic.Draggable = true

	script.Parent.TopBar.Strength.Draggable = true

	

end

coroutine.wrap(RMDWM_fake_script)()
