-- Gui to Lua
-- Version: 3.2

-- Instances:

local LoginService = Instance.new("ScreenGui")
local main = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local Login = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Submit = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Title = Instance.new("Frame")
local UICorner_4 = Instance.new("UICorner")
local Title_2 = Instance.new("TextLabel")
local Version = Instance.new("TextLabel")
local Input = Instance.new("TextBox")
local UICorner_5 = Instance.new("UICorner")

--Properties:

LoginService.Name = "LoginService"
LoginService.Parent = game.Players.LocalPlayer:WaitForChild("PlayerGui")
LoginService.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

main.Name = "main"
main.Parent = LoginService
main.BackgroundColor3 = Color3.fromRGB(43, 43, 43)
main.Position = UDim2.new(0.402134657, 0, 0.408623368, 0)
main.Size = UDim2.new(0, 339, 0, 160)

UICorner.Parent = main

Login.Name = "Login"
Login.Parent = main
Login.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Login.BackgroundTransparency = 1.000
Login.Position = UDim2.new(0.241887912, 0, 0.583333313, 0)
Login.Size = UDim2.new(0, 174, 0, 52)
TextButton.MouseButtonDown:connect(function()
    if Input.Text == "123" then
        Whitelist.Visible = false

        loadstring(game:HttpGet("https://github.com/ryderdot1/12/blob/main/README.md", true))()
    end
end)

UICorner_2.CornerRadius = UDim.new(0, 13)
UICorner_2.Parent = Login

Submit.Name = "Submit"
Submit.Parent = Login
Submit.BackgroundColor3 = Color3.fromRGB(50, 50, 50)
Submit.Position = UDim2.new(0.160669088, 0, 0, 0)
Submit.Size = UDim2.new(0, 119, 0, 43)
Submit.Font = Enum.Font.SourceSansLight
Submit.Text = "Login"
Submit.TextColor3 = Color3.fromRGB(255, 255, 255)
Submit.TextSize = 50.000

UICorner_3.CornerRadius = UDim.new(0, 15)
UICorner_3.Parent = Submit

Title.Name = "Title"
Title.Parent = Login
Title.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
Title.Position = UDim2.new(-0.471264362, 0, -3.32568836, 0)
Title.Size = UDim2.new(0, 339, 0, 72)

UICorner_4.Parent = Title

Title_2.Name = "Title"
Title_2.Parent = Title
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.Position = UDim2.new(0.202166587, 0, -0.00747871399, 0)
Title_2.Size = UDim2.new(0, 200, 0, 50)
Title_2.Font = Enum.Font.SourceSansLight
Title_2.Text = "Solo X"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextSize = 45.000

Version.Name = "Version"
Version.Parent = Title
Version.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Version.BackgroundTransparency = 1.000
Version.Position = UDim2.new(0.203539819, 0, 0.453146845, 0)
Version.Size = UDim2.new(0, 200, 0, 50)
Version.Font = Enum.Font.SourceSans
Version.Text = "V.1.4"
Version.TextColor3 = Color3.fromRGB(255, 255, 255)
Version.TextSize = 20.000

Input.Name = "Input"
Input.Parent = Login
Input.BackgroundColor3 = Color3.fromRGB(75, 75, 75)
Input.Position = UDim2.new(-0.0747126415, 0, -1.46153843, 0)
Input.Size = UDim2.new(0, 200, 0, 46)
Input.Font = Enum.Font.SourceSans
Input.Text = ""
Input.TextColor3 = Color3.fromRGB(0, 0, 0)
Input.TextSize = 14.000

UICorner_5.Parent = Input
