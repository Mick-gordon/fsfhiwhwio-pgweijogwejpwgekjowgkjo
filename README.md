local HyperXLoadgui = Instance.new("ScreenGui")
local back = Instance.new("Frame")
local Front = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local Exit = Instance.new("TextButton")
local Load = Instance.new("TextButton")

HyperXLoadgui.Name = "Hyper X Load gui"
HyperXLoadgui.Parent = game.CoreGui

back.Name = "back"
back.Parent = HyperXLoadgui
back.BackgroundColor3 = Color3.fromRGB(60, 60, 60)
back.BorderColor3 = Color3.fromRGB(5, 5, 5)
back.Position = UDim2.new(0.315175116, 0, 0.263803691, 0)
back.Size = UDim2.new(0, 354, 0, 233)

Front.Name = "Front"
Front.Parent = back
Front.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
Front.BorderColor3 = Color3.fromRGB(60, 60, 60)
Front.Position = UDim2.new(0.00564971566, 0, 0.00858368725, 0)
Front.Size = UDim2.new(0, 349, 0, 228)

TextLabel.Parent = Front
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.212034389, 0, 0.140350863, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 50)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Hyper X"
TextLabel.TextColor3 = Color3.fromRGB(191, 191, 191)
TextLabel.TextSize = 14.000
TextLabel.TextWrapped = true

Exit.Name = "Exit"
Exit.Parent = Front
Exit.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Exit.BorderColor3 = Color3.fromRGB(50, 50, 50)
Exit.Position = UDim2.new(0.320916891, 0, 0.833333313, 0)
Exit.Size = UDim2.new(0, 122, 0, 29)
Exit.Font = Enum.Font.GothamBold
Exit.Text = "Exit"
Exit.TextColor3 = Color3.fromRGB(159, 159, 159)
Exit.TextSize = 11.000
Exit.TextWrapped = true
Exit.MouseButton1Down:connect(function()
	back.Visible = false
end)

Load.Name = "Load"
Load.Parent = Front
Load.BackgroundColor3 = Color3.fromRGB(30, 30, 30)
Load.BorderColor3 = Color3.fromRGB(50, 50, 50)
Load.Position = UDim2.new(0.323782235, 0, 0.640350878, 0)
Load.Size = UDim2.new(0, 122, 0, 29)
Load.Font = Enum.Font.GothamBold
Load.Text = "Load"
Load.TextColor3 = Color3.fromRGB(159, 159, 159)
Load.TextSize = 11.000
Load.TextWrapped = true
Load.MouseButton1Down:connect(function()
	back.Visible = false
	loadstring(game:HttpGet("https://raw.githubusercontent.com/Mick-gordon/Loader/main/README.md", true))()

end)
print ("██╗  ██╗██╗   ██╗██████╗ ███████╗██████╗     ██╗  ██╗")
print ("██║  ██║╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗    ╚██╗██╔╝")
print ("███████║ ╚████╔╝ ██████╔╝█████╗  ██████╔╝     ╚███╔╝ ")
print ("██╔══██║  ╚██╔╝  ██╔═══╝ ██╔══╝  ██╔══██╗     ██╔██╗ ")
print ("██║  ██║   ██║   ██║     ███████╗██║  ██║    ██╔╝ ██╗")
print ("╚═   ╚═╝   ╚═╝   ╚═╝     ╚══════╝╚═╝  ╚═╝    ╚═╝  ╚═╝")
