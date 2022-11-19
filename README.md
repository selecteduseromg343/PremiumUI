-- GUI to Lua 
-- Version: 0.0.3

-- Instances:

local ScreenGui = Instance.new("ScreenGui")
local DragMain_1 = Instance.new("Frame")
local Draggable_1 = Instance.new("Frame")
local TextLabel_1 = Instance.new("TextLabel")
local UICorner_1 = Instance.new("UICorner")
local UICorner_2 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local Scripts_1 = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local fe_1 = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local yield_1 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local cmdx_1 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local aimbot_1 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local doors_1 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local TextLabel_3 = Instance.new("TextLabel")
local fpsgun_1 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")

ScreenGui.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
ScreenGui.ZIndexBehavior = Enum.ZIndexBehavior.Global

DragMain_1.Name = "DragMain"
DragMain_1.Parent = ScreenGui
DragMain_1.BackgroundColor3 = Color3.fromRGB(40,40,40)
DragMain_1.BorderColor3 = Color3.fromRGB(255,0,4)
DragMain_1.Position = UDim2.new(0.150670752, 0,0.331746042, 0)
DragMain_1.Size = UDim2.new(0, 444,0, 336)
DragMain_1.Active = true
DragMain_1.Draggable = true

Draggable_1.Name = "Draggable"
Draggable_1.Parent = DragMain_1
Draggable_1.BackgroundColor3 = Color3.fromRGB(85,85,255)
Draggable_1.BorderColor3 = Color3.fromRGB(27,42,53)
Draggable_1.Size = UDim2.new(0, 444,0, 49)
DragMain_1.Size = UDim2.new(0, 444,0, 336)


TextLabel_1.Parent = Draggable_1
TextLabel_1.BackgroundColor3 = Color3.fromRGB(58,58,58)
TextLabel_1.BorderColor3 = Color3.fromRGB(27,42,53)
TextLabel_1.Position = UDim2.new(-0.00675162673, 0,0, 0)
TextLabel_1.Size = UDim2.new(0, 446,0, 23)
TextLabel_1.Font = Enum.Font.PatrickHand
TextLabel_1.Text = "DarkWare | Premium"
TextLabel_1.TextColor3 = Color3.fromRGB(255,183,0)
TextLabel_1.TextScaled = true
TextLabel_1.TextSize = 14
TextLabel_1.TextStrokeColor3 = Color3.fromRGB(255,0,0)
TextLabel_1.TextWrapped = true

UICorner_1.Parent = TextLabel_1

UICorner_2.Parent = Draggable_1

TextLabel_2.Parent = Draggable_1
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255,0,4)
TextLabel_2.BorderColor3 = Color3.fromRGB(255,0,4)
TextLabel_2.Position = UDim2.new(0.676404536, 0,1.28571427, 0)
TextLabel_2.Size = UDim2.new(0, 124,0, 34)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "FE Scripts [New]"
TextLabel_2.TextSize = 14

UICorner_3.Parent = TextLabel_2

Scripts_1.Name = "Scripts"
Scripts_1.Parent = Draggable_1
Scripts_1.BackgroundColor3 = Color3.fromRGB(255,0,4)
Scripts_1.BorderColor3 = Color3.fromRGB(255,0,4)
Scripts_1.Position = UDim2.new(0.0359550565, 0,1.28571427, 0)
Scripts_1.Size = UDim2.new(0, 111,0, 34)
Scripts_1.Font = Enum.Font.SourceSans
Scripts_1.Text = "Scripts"
Scripts_1.TextSize = 14

UICorner_4.Parent = Scripts_1

fe_1.Name = "fe"
fe_1.Parent = DragMain_1
fe_1.Active = true
fe_1.BackgroundColor3 = Color3.fromRGB(66,189,255)
fe_1.BorderColor3 = Color3.fromRGB(27,42,53)
fe_1.Position = UDim2.new(0.684684813, 0,0.326283962, 0)
fe_1.Size = UDim2.new(0, 117,0, 30)
fe_1.Font = Enum.Font.FredokaOne
fe_1.Text = " GrandMaster[NEW]"
fe_1.TextSize = 14
fe_1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/selecteduseromg343/GrandMasterAnim/main/README.md"))();
end)


UICorner_5.Parent = fe_1

yield_1.Name = "yield"
yield_1.Parent = DragMain_1
yield_1.Active = true
yield_1.BackgroundColor3 = Color3.fromRGB(66,189,255)
yield_1.BorderColor3 = Color3.fromRGB(27,42,53)
yield_1.Position = UDim2.new(0.0494382381, 0,0.326283991, 0)
yield_1.Size = UDim2.new(0, 98,0, 30)
yield_1.Font = Enum.Font.FredokaOne
yield_1.Text = "InfYield FE"
yield_1.TextSize = 14
yield_1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end)

UICorner_6.Parent = yield_1

cmdx_1.Name = "cmdx"
cmdx_1.Parent = DragMain_1
cmdx_1.Active = true
cmdx_1.BackgroundColor3 = Color3.fromRGB(84,150,255)
cmdx_1.BorderColor3 = Color3.fromRGB(27,42,53)
cmdx_1.Position = UDim2.new(0.0494382009, 0,0.456193358, 0)
cmdx_1.Size = UDim2.new(0, 98,0, 25)
cmdx_1.Font = Enum.Font.Creepster
cmdx_1.Text = "Cmd X"
cmdx_1.TextSize = 14
cmdx_1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CMD-X/CMD-X/master/CMD-X"))()
end)

UICorner_7.Parent = cmdx_1

aimbot_1.Name = "aimbot"
aimbot_1.Parent = DragMain_1
aimbot_1.Active = true
aimbot_1.BackgroundColor3 = Color3.fromRGB(107,159,255)
aimbot_1.BorderColor3 = Color3.fromRGB(27,42,53)
aimbot_1.Position = UDim2.new(0.0494382009, 0,0.568020761, 0)
aimbot_1.Size = UDim2.new(0, 98,0, 24)
aimbot_1.Font = Enum.Font.LuckiestGuy
aimbot_1.Text = "Owl Hub"
aimbot_1.TextSize = 14
aimbot_1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/CriShoux/OwlHub/master/OwlHub.txt"))();
end)

UICorner_8.Parent = aimbot_1

doors_1.Name = "doors"
doors_1.Parent = DragMain_1
doors_1.Active = true
doors_1.BackgroundColor3 = Color3.fromRGB(118,255,26)
doors_1.BorderColor3 = Color3.fromRGB(27,42,53)
doors_1.Position = UDim2.new(0.0472972989, 0,0.675595224, 0)
doors_1.Size = UDim2.new(0, 98,0, 25)
doors_1.Font = Enum.Font.FredokaOne
doors_1.Text = "Doors Script [Special]"
doors_1.TextScaled = true
doors_1.TextSize = 14
doors_1.TextWrapped = true
doors_1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet('https://raw.githubusercontent.com/plamen6789/DoorsEntitySummonerGUI/main/EntityGUI'))()
end)

UICorner_9.Parent = doors_1

TextLabel_3.Parent = DragMain_1
TextLabel_3.BackgroundColor3 = Color3.fromRGB(34,255,0)
TextLabel_3.BorderColor3 = Color3.fromRGB(27,42,53)
TextLabel_3.Position = UDim2.new(0.389639646, 0,0.922619045, 0)
TextLabel_3.Size = UDim2.new(0, 270,0, 26)
TextLabel_3.Font = Enum.Font.FredokaOne
TextLabel_3.Text = "INFO: Green = Special    Cyan = Basic Scripts"
TextLabel_3.TextSize = 14

fpsgun_1.Name = "fpsgun"
fpsgun_1.Parent = DragMain_1
fpsgun_1.Active = true
fpsgun_1.BackgroundColor3 = Color3.fromRGB(118,255,26)
fpsgun_1.BorderColor3 = Color3.fromRGB(27,42,53)
fpsgun_1.Position = UDim2.new(0.0472972989, 0,0.773809493, 0)
fpsgun_1.Size = UDim2.new(0, 92,0, 34)
fpsgun_1.Font = Enum.Font.FredokaOne
fpsgun_1.Text = "DoorsFpsGun[Special]"
fpsgun_1.TextScaled = true
fpsgun_1.TextSize = 14
fpsgun_1.TextWrapped = true
fpsgun_1.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/ZepsyyCodesLUA/Utilities/main/DOORSFpsGun.lua?token=GHSAT0AAAAAAB2POHILOXMAHBQ2GN2QD2MQY3SXTCQ"))()
end)

UICorner_10.Parent = fpsgun_1
