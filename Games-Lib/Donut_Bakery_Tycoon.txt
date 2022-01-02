-- SneosX
-- Version: 1.0 Beta
--Script from someone idk but revamped by Senko#4150
--btw nice ui dude


local ScreenGui = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local lable = Instance.new("TextLabel")
local UICorner_2 = Instance.new("UICorner")
local lable_2 = Instance.new("TextLabel")
local UICorner_3 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local UICorner_4 = Instance.new("UICorner")
local TextLabel_2 = Instance.new("TextLabel")
local UICorner_5 = Instance.new("UICorner")
local script5 = Instance.new("TextButton")
local UICorner_6 = Instance.new("UICorner")
local script8 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local script1 = Instance.new("TextButton")
local UICorner_8 = Instance.new("UICorner")
local script2 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local script3 = Instance.new("TextButton")
local UICorner_10 = Instance.new("UICorner")
local script4 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local UICorner_12 = Instance.new("UICorner")

--Properties:

ScreenGui.Parent = game.CoreGui

main.Name = "main"
main.Parent = ScreenGui
main.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
main.Position = UDim2.new(0.280302882, 0, 0.104972452, 0)
main.Size = UDim2.new(0, 364, 0, 415)
main.Active = true
main.Draggable = true

UICorner.CornerRadius = UDim.new(0, 30)
UICorner.Parent = main

lable.Name = "lable"
lable.Parent = main
lable.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
lable.Position = UDim2.new(-8.38395025e-08, 0, 0, 0)
lable.Size = UDim2.new(0, 195, 0, 49)
lable.Font = Enum.Font.Arial
lable.Text = "SneosX"
lable.TextColor3 = Color3.fromRGB(42, 0, 255)
lable.TextSize = 30.000

UICorner_2.CornerRadius = UDim.new(0, 30)
UICorner_2.Parent = lable

lable_2.Name = "lable"
lable_2.Parent = main
lable_2.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
lable_2.Position = UDim2.new(0.429854423, 0, 0.048192773, 0)
lable_2.Size = UDim2.new(0, 151, 0, 8)
lable_2.Font = Enum.Font.Arial
lable_2.Text = "Donut Bakery Tycoon"
lable_2.TextColor3 = Color3.fromRGB(255, 255, 255)
lable_2.TextSize = 18.000

UICorner_3.CornerRadius = UDim.new(0, 30)
UICorner_3.Parent = lable_2

TextLabel.Parent = main
TextLabel.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
TextLabel.Position = UDim2.new(-2.27037817e-05, 0, 0.503614426, 0)
TextLabel.Size = UDim2.new(0, 364, 0, 38)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "OP stuff"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 28.000

UICorner_4.CornerRadius = UDim.new(0, 30)
UICorner_4.Parent = TextLabel

TextLabel_2.Parent = main
TextLabel_2.BackgroundColor3 = Color3.fromRGB(44, 44, 44)
TextLabel_2.Position = UDim2.new(-3.02724075e-05, 0, 0.118072286, 0)
TextLabel_2.Size = UDim2.new(0, 364, 0, 38)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Farm Cheat"
TextLabel_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.TextSize = 28.000

UICorner_5.CornerRadius = UDim.new(0, 30)
UICorner_5.Parent = TextLabel_2

script5.Name = "script5"
script5.Parent = main
script5.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
script5.Position = UDim2.new(0.0247328207, 0, 0.630120456, 0)
script5.Size = UDim2.new(0, 346, 0, 47)
script5.Font = Enum.Font.Ubuntu
script5.Text = "Rebirth Cheat"
script5.TextColor3 = Color3.fromRGB(0, 0, 0)
script5.TextSize = 14.000
script5.MouseButton1Down:Connect(function()
	while true do
		wait()
		game.Workspace.DiamondStoreEvents.Rebirth:FireServer()
	end	
end)

UICorner_6.CornerRadius = UDim.new(0, 30)
UICorner_6.Parent = script5

script8.Name = "script8"
script8.Parent = main
script8.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
script8.Position = UDim2.new(0.0274800733, 0, 0.766946077, 0)
script8.Size = UDim2.new(0, 345, 0, 40)
script8.Font = Enum.Font.Ubuntu
script8.Text = "Infinite Yeild / Admin Command"
script8.TextColor3 = Color3.fromRGB(0, 0, 0)
script8.TextSize = 14.000
script1.MouseButton1Down:Connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/EdgeIY/infiniteyield/master/source"))()
end)

UICorner_7.CornerRadius = UDim.new(0, 30)
UICorner_7.Parent = script8

script1.Name = "script1"
script1.Parent = main
script1.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
script1.Position = UDim2.new(0.0274800956, 0, 0.225301206, 0)
script1.Size = UDim2.new(0, 161, 0, 47)
script1.Font = Enum.Font.Ubuntu
script1.Text = "Infinity Iron"
script1.TextColor3 = Color3.fromRGB(0, 0, 0)
script1.TextSize = 14.000
script1.MouseButton1Down:Connect(function()
	game.Workspace.DiamondStoreEvents.AddMoney:FireServer(math.huge,"Iron")	
end)

UICorner_8.CornerRadius = UDim.new(0, 30)
UICorner_8.Parent = script1

script2.Name = "script2"
script2.Parent = main
script2.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
script2.Position = UDim2.new(0.535668969, 0, 0.225301191, 0)
script2.Size = UDim2.new(0, 161, 0, 47)
script2.Font = Enum.Font.Ubuntu
script2.Text = "Infinity Wood"
script2.TextColor3 = Color3.fromRGB(0, 0, 0)
script2.TextSize = 14.000
script2.MouseButton1Down:Connect(function()
	game.Workspace.DiamondStoreEvents.AddMoney:FireServer(math.huge,"Wood")	
end)

UICorner_9.CornerRadius = UDim.new(0, 30)
UICorner_9.Parent = script2

script3.Name = "script3"
script3.Parent = main
script3.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
script3.Position = UDim2.new(0.0274271369, 0, 0.372289121, 0)
script3.Size = UDim2.new(0, 161, 0, 47)
script3.Font = Enum.Font.Ubuntu
script3.Text = "Infinity Money"
script3.TextColor3 = Color3.fromRGB(0, 0, 0)
script3.TextSize = 14.000
script3.MouseButton1Down:Connect(function()
	game.Workspace.DiamondStoreEvents.AddCash:FireServer(math.huge)	
end)

UICorner_10.CornerRadius = UDim.new(0, 30)
UICorner_10.Parent = script3

script4.Name = "script4"
script4.Parent = main
script4.BackgroundColor3 = Color3.fromRGB(79, 79, 79)
script4.Position = UDim2.new(0.53301245, 0, 0.372289121, 0)
script4.Size = UDim2.new(0, 161, 0, 47)
script4.Font = Enum.Font.Ubuntu
script4.Text = "Infinity Wheat"
script4.TextColor3 = Color3.fromRGB(0, 0, 0)
script4.TextSize = 14.000
script4.MouseButton1Down:Connect(function()
	game.Workspace.DiamondStoreEvents.AddMoney:FireServer(math.huge,"Wheat")	
end)

UICorner_11.CornerRadius = UDim.new(0, 30)
UICorner_11.Parent = script4

UICorner_12.CornerRadius = UDim.new(0, 30)
UICorner_12.Parent = main
