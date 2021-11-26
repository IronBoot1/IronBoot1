

local ScreenGui = Instance.new("ScreenGui")
local Main = Instance.new("Frame")
local label = Instance.new("TextLabel")
local Petsimxred = Instance.new("TextButton")
local Blackgui = Instance.new("TextButton")
local gui = Instance.new("TextButton")

--Properties:

ScreenGui.Parent = game.CoreGui

Main.Name = "Main"
Main.Parent = ScreenGui
Main.BackgroundColor3 = Color3.fromRGB(40, 40, 40)
Main.Position = UDim2.new(0.245583728, 0, 0.352201283, 0)
Main.Size = UDim2.new(0, 469, 0, 206)
Main.Active = true
Main.Draggable = true

label.Name = "label"
label.Parent = Main
label.BackgroundColor3 = Color3.fromRGB(95, 82, 82)
label.Size = UDim2.new(0, 469, 0, 28)
label.Font = Enum.Font.SourceSansBold
label.LineHeight = 1.090
label.Text = "1st"
label.TextColor3 = Color3.fromRGB(0, 0, 0)
label.TextSize = 14.000

Petsimxred.Name = "Pet sim x red"
Petsimxred.Parent = Main
Petsimxred.BackgroundColor3 = Color3.fromRGB(85, 255, 255)
Petsimxred.Position = UDim2.new(0, 0, 0.135922328, 0)
Petsimxred.Size = UDim2.new(0, 200, 0, 50)
Petsimxred.Font = Enum.Font.SourceSans
Petsimxred.Text = "Pet sim x red gui "
Petsimxred.TextColor3 = Color3.fromRGB(0, 0, 0)
Petsimxred.TextSize = 14.000
Petsimxred.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/TurfuGoldy/GoldenScripts/main/EzPets.lua"))()

end)

Blackgui.Name = "Black gui"
Blackgui.Parent = Main
Blackgui.BackgroundColor3 = Color3.fromRGB(170, 170, 0)
Blackgui.Position = UDim2.new(0, 0, 0.378640771, 0)
Blackgui.Size = UDim2.new(0, 200, 0, 50)
Blackgui.Font = Enum.Font.SourceSans
Blackgui.Text = "Black gui "
Blackgui.TextColor3 = Color3.fromRGB(0, 0, 0)
Blackgui.TextSize = 14.000
Blackgui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://raw.githubusercontent.com/si1nnx/psxx/main/g"))()
end)


gui.Name = "gui"
gui.Parent = Main
gui.BackgroundColor3 = Color3.fromRGB(170, 0, 127)
gui.Position = UDim2.new(0, 0, 0.621359229, 0)
gui.Size = UDim2.new(0, 200, 0, 50)
gui.Font = Enum.Font.SourceSans
gui.Text = "Systen exodus alternative"
gui.TextColor3 = Color3.fromRGB(0, 0, 0)
gui.TextSize = 14.000
gui.MouseButton1Down:connect(function()
	loadstring(game:HttpGet("https://system-exodus.com/scripts/PetSimulator/PetSimulatorX.lua", true))()

end)
