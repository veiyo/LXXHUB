

local ScreenGui = Instance.new("ScreenGui")
local Frame = Instance.new("ImageLabel")
local TextLabel = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local TextButton_Roundify_12px = Instance.new("ImageLabel")
local TextBox = Instance.new("TextBox")
local TextLabel_2 = Instance.new("TextLabel")
local TextLabel_Roundify_12px = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_Roundify_12px_2 = Instance.new("ImageLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")

--Properties:

ScreenGui.Parent = game.Workspace

Frame.Name = "Frame"
Frame.Parent = ScreenGui
Frame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Frame.BackgroundTransparency = 1.000
Frame.Position = UDim2.new(0.27399382, 0, 0.331288338, 0)
Frame.Size = UDim2.new(0, 469, 0, 236)
Frame.Image = "rbxassetid://3570695787"
Frame.ImageColor3 = Color3.fromRGB(45, 45, 45)
Frame.ImageTransparency = 0.250
Frame.ScaleType = Enum.ScaleType.Slice
Frame.SliceCenter = Rect.new(100, 100, 100, 100)
Frame.SliceScale = 0.120
Frame. Active = true 
Frame. Draggable = true


TextLabel.Parent = ScreenGui
TextLabel.BackgroundColor3 = Color3.fromRGB(49, 49, 49)
TextLabel.BackgroundTransparency = 0.700
TextLabel.Position = UDim2.new(0.27399382, 0, 0.331288338, 0)
TextLabel.Size = UDim2.new(0, 221, 0, 63)
TextLabel.Font = Enum.Font.AmaticSC
TextLabel.Text = "LXXHUB V1"
TextLabel.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.TextSize = 41.000


TextButton.Parent = ScreenGui
TextButton.BackgroundColor3 = Color3.fromRGB(255, 0, 17)
TextButton.BackgroundTransparency = 1.000
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.267027855, 0, 0.331288338, 0)
TextButton.Size = UDim2.new(0, 18, 0, 19)
TextButton.Font = Enum.Font.PatrickHand
TextButton.Text = "X"
TextButton.TextColor3 = Color3.fromRGB(0, 0, 0)
TextButton.TextSize = 14.000

TextButton_Roundify_12px.Name = "TextButton_Roundify_12px"
TextButton_Roundify_12px.Parent = TextButton
TextButton_Roundify_12px.Active = true
TextButton_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextButton_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextButton_Roundify_12px.BackgroundTransparency = 1.000
TextButton_Roundify_12px.Position = UDim2.new(0.5, 0, 0.5, 0)
TextButton_Roundify_12px.Selectable = true
TextButton_Roundify_12px.Size = UDim2.new(1, 0, 1, 0)
TextButton_Roundify_12px.Image = "rbxassetid://3570695787"
TextButton_Roundify_12px.ImageColor3 = Color3.fromRGB(255, 0, 17)
TextButton_Roundify_12px.ImageTransparency = 0.400
TextButton_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextButton_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextButton_Roundify_12px.SliceScale = 0.120

TextBox.Parent = ScreenGui
TextBox.BackgroundColor3 = Color3.fromRGB(81, 81, 81)
TextBox.BackgroundTransparency = 0.500
TextBox.Position = UDim2.new(0.445046425, 0, 0.331288338, 0)
TextBox.Size = UDim2.new(0, 248, 0, 236)
TextBox.Font = Enum.Font.SourceSans
TextBox.Text = ""
TextBox.TextColor3 = Color3.fromRGB(0, 0, 0)
TextBox.TextSize = 14.000

TextLabel_2.Parent = ScreenGui
TextLabel_2.BackgroundColor3 = Color3.fromRGB(74, 74, 74)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.266253889, 0, 0.492024511, 0)
TextLabel_2.Size = UDim2.new(0, 221, 0, 58)
TextLabel_2.Font = Enum.Font.SourceSans
TextLabel_2.Text = "Note: 2% of the script has been done"
TextLabel_2.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.TextSize = 14.000

TextLabel_Roundify_12px.Name = "TextLabel_Roundify_12px"
TextLabel_Roundify_12px.Parent = TextLabel_2
TextLabel_Roundify_12px.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_Roundify_12px.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Roundify_12px.BackgroundTransparency = 0.650
TextLabel_Roundify_12px.Position = UDim2.new(0.547511339, 0, -0.749999464, 0)
TextLabel_Roundify_12px.Size = UDim2.new(0.98642534, 0, 0.844827056, 0)
TextLabel_Roundify_12px.Image = "rbxassetid://3570695787"
TextLabel_Roundify_12px.ImageColor3 = Color3.fromRGB(74, 74, 74)
TextLabel_Roundify_12px.ImageTransparency = 0.050
TextLabel_Roundify_12px.ScaleType = Enum.ScaleType.Slice
TextLabel_Roundify_12px.SliceCenter = Rect.new(100, 100, 100, 100)
TextLabel_Roundify_12px.SliceScale = 0.120

TextLabel_3.Parent = ScreenGui
TextLabel_3.BackgroundColor3 = Color3.fromRGB(85, 85, 85)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.27399382, 0, 0.563190222, 0)
TextLabel_3.Size = UDim2.new(0, 220, 0, 47)
TextLabel_3.Font = Enum.Font.SourceSans
TextLabel_3.Text = "This script is in its Early Devolpent"
TextLabel_3.TextColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.TextSize = 14.000

TextLabel_Roundify_12px_2.Name = "TextLabel_Roundify_12px"
TextLabel_Roundify_12px_2.Parent = TextLabel_3
TextLabel_Roundify_12px_2.AnchorPoint = Vector2.new(0.5, 0.5)
TextLabel_Roundify_12px_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_Roundify_12px_2.BackgroundTransparency = 1.000
TextLabel_Roundify_12px_2.Position = UDim2.new(0.50454545, 0, 0.436169565, 0)
TextLabel_Roundify_12px_2.Size = UDim2.new(1.0090909, 0, 1.12766099, 0)
TextLabel_Roundify_12px_2.Image = "rbxassetid://3570695787"
TextLabel_Roundify_12px_2.ImageColor3 = Color3.fromRGB(85, 85, 85)
TextLabel_Roundify_12px_2.ImageTransparency = 0.500
TextLabel_Roundify_12px_2.ScaleType = Enum.ScaleType.Slice
TextLabel_Roundify_12px_2.SliceCenter = Rect.new(100, 100, 100, 100)
TextLabel_Roundify_12px_2.SliceScale = 0.120

ScrollingFrame.Parent = ScreenGui
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(45, 45, 45)
ScrollingFrame.BackgroundTransparency = 0.250
ScrollingFrame.Position = UDim2.new(0.275541812, 0, 0.467484713, 0)
ScrollingFrame.Size = UDim2.new(0, 218, 0, 71)
