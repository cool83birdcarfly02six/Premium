-- Gui to Lua
-- Version: 3.2

-- Instances:

local Premiujm = Instance.new("ScreenGui")
local PREMIUMFRAME = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local Premium = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local UIGradient = Instance.new("UIGradient")
local INFO = Instance.new("TextLabel")
local INFO_2 = Instance.new("TextLabel")
local INFO_3 = Instance.new("TextLabel")
local INFO_4 = Instance.new("TextLabel")
local Purchase = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local TextLabel = Instance.new("TextLabel")
local ImageLabel = Instance.new("ImageLabel")
local ImageLabel_2 = Instance.new("ImageLabel")
local ImageLabel_3 = Instance.new("ImageLabel")
local close = Instance.new("ImageButton")
local UIListLayout = Instance.new("UIListLayout")

--Properties:

Premiujm.Name = "Premiujm"
Premiujm.Parent = game.CoreGui

PREMIUMFRAME.Name = "PREMIUMFRAME"
PREMIUMFRAME.Parent = Premiujm
PREMIUMFRAME.BackgroundColor3 = Color3.fromRGB(11, 19, 31)
PREMIUMFRAME.BorderSizePixel = 0
PREMIUMFRAME.Position = UDim2.new(0.596414685, 0, 0.519753098, 0)
PREMIUMFRAME.Size = UDim2.new(0, 306, 0, 249)

UICorner.CornerRadius = UDim.new(0, 4)
UICorner.Parent = PREMIUMFRAME

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = PREMIUMFRAME
DropShadowHolder.BackgroundTransparency = 1.000
DropShadowHolder.BorderSizePixel = 0
DropShadowHolder.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder.ZIndex = 0

DropShadow.Name = "DropShadow"
DropShadow.Parent = DropShadowHolder
DropShadow.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0.503268003, 0, 0.489000916, 0)
DropShadow.Size = UDim2.new(1.00653601, 47, 1.00803208, 47)
DropShadow.ZIndex = 0
DropShadow.Image = "rbxassetid://6014261993"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.500
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

Premium.Name = "Premium"
Premium.Parent = PREMIUMFRAME
Premium.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Premium.BorderColor3 = Color3.fromRGB(27, 42, 53)
Premium.BorderSizePixel = 0
Premium.Size = UDim2.new(0, 306, 0, 249)

UICorner_2.CornerRadius = UDim.new(0, 4)
UICorner_2.Parent = Premium

UIGradient.Color = ColorSequence.new{ColorSequenceKeypoint.new(0.00, Color3.fromRGB(45, 168, 182)), ColorSequenceKeypoint.new(1.00, Color3.fromRGB(64, 96, 161))}
UIGradient.Parent = Premium

INFO.Name = "INFO"
INFO.Parent = Premium
INFO.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
INFO.BackgroundTransparency = 1.000
INFO.Position = UDim2.new(0.0885245875, 0, 0.0645161271, 0)
INFO.Size = UDim2.new(0, 200, 0, 50)
INFO.Font = Enum.Font.SourceSansSemibold
INFO.Text = "Lightux+"
INFO.TextColor3 = Color3.fromRGB(255, 255, 255)
INFO.TextSize = 25.000
INFO.TextXAlignment = Enum.TextXAlignment.Left

INFO_2.Name = "INFO"
INFO_2.Parent = Premium
INFO_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
INFO_2.BackgroundTransparency = 1.000
INFO_2.Position = UDim2.new(0.0885245875, 0, 0.17338711, 0)
INFO_2.Size = UDim2.new(0, 200, 0, 50)
INFO_2.Font = Enum.Font.SourceSans
INFO_2.Text = "This will give you more features and benefits while using the scripts"
INFO_2.TextColor3 = Color3.fromRGB(255, 255, 255)
INFO_2.TextSize = 14.000
INFO_2.TextWrapped = true
INFO_2.TextXAlignment = Enum.TextXAlignment.Left

INFO_3.Name = "INFO"
INFO_3.Parent = Premium
INFO_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
INFO_3.BackgroundTransparency = 1.000
INFO_3.Position = UDim2.new(0.0885245875, 0, 0.322580636, 0)
INFO_3.Size = UDim2.new(0, 200, 0, 50)
INFO_3.Font = Enum.Font.SourceSansSemibold
INFO_3.Text = "Benefits:"
INFO_3.TextColor3 = Color3.fromRGB(255, 255, 255)
INFO_3.TextSize = 25.000
INFO_3.TextXAlignment = Enum.TextXAlignment.Left

INFO_4.Name = "INFO"
INFO_4.Parent = Premium
INFO_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
INFO_4.BackgroundTransparency = 1.000
INFO_4.Position = UDim2.new(0.0885245875, 0, 0.471774191, 0)
INFO_4.Size = UDim2.new(0, 200, 0, 104)
INFO_4.Font = Enum.Font.SourceSans
INFO_4.Text = "•Lightux+ Commands                             •Lightux+ Role                                                                •Direct Keys (New Scripts)                                     •Better/Faster Support"
INFO_4.TextColor3 = Color3.fromRGB(255, 255, 255)
INFO_4.TextSize = 14.000
INFO_4.TextWrapped = true
INFO_4.TextXAlignment = Enum.TextXAlignment.Left
INFO_4.TextYAlignment = Enum.TextYAlignment.Top

Purchase.Name = "Purchase"
Purchase.Parent = Premium
Purchase.BackgroundColor3 = Color3.fromRGB(0, 136, 255)
Purchase.Position = UDim2.new(0.609836042, 0, 0.786355078, 0)
Purchase.Size = UDim2.new(0, 109, 0, 34)
Purchase.Font = Enum.Font.SourceSansSemibold
Purchase.Text = "Purchase"
Purchase.TextColor3 = Color3.fromRGB(255, 255, 255)
Purchase.TextSize = 16.000

UICorner_3.CornerRadius = UDim.new(1, 0)
UICorner_3.Parent = Purchase

TextLabel.Parent = Purchase
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.Position = UDim2.new(0.100917429, 0, 1.02941179, 0)
TextLabel.Size = UDim2.new(0, 86, 0, 18)
TextLabel.Font = Enum.Font.SourceSans
TextLabel.Text = "Copies Discord"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 14.000

ImageLabel.Parent = Premium
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BackgroundTransparency = 1.000
ImageLabel.Position = UDim2.new(0.0882353783, 0, 0.797449052, 0)
ImageLabel.Size = UDim2.new(0, 28, 0, 28)
ImageLabel.Image = "http://www.roblox.com/asset/?id=11713337390"

ImageLabel_2.Parent = Premium
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BackgroundTransparency = 1.000
ImageLabel_2.Position = UDim2.new(0.323529422, 0, 0.797449052, 0)
ImageLabel_2.Size = UDim2.new(0, 28, 0, 28)
ImageLabel_2.Image = "http://www.roblox.com/asset/?id=6908632622"
ImageLabel_2.ImageColor3 = Color3.fromRGB(85, 255, 0)

ImageLabel_3.Parent = Premium
ImageLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_3.BackgroundTransparency = 1.000
ImageLabel_3.Position = UDim2.new(0.212418392, 0, 0.797448993, 0)
ImageLabel_3.Size = UDim2.new(0, 28, 0, 28)
ImageLabel_3.Image = "http://www.roblox.com/asset/?id=10412067982"

close.Name = "close"
close.Parent = Premium
close.BackgroundTransparency = 1.000
close.LayoutOrder = 2
close.Position = UDim2.new(0.918300629, 0, -0.00200802088, 0)
close.Size = UDim2.new(0, 25, 0, 25)
close.ZIndex = 2
close.Image = "rbxassetid://3926305904"
close.ImageRectOffset = Vector2.new(284, 4)
close.ImageRectSize = Vector2.new(24, 24)

UIListLayout.Parent = Premiujm
UIListLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.VerticalAlignment = Enum.VerticalAlignment.Center

-- Scripts:

local function LKQDELG_fake_script() -- Purchase.LocalScript 
	local script = Instance.new('LocalScript', Purchase)

	Purchase.MouseButton1Down:Connect(function()
		setclipboard('https://discord.gg/sdCSmXRjuX')
	end)
end
coroutine.wrap(LKQDELG_fake_script)()
local function QZOBQMN_fake_script() -- close.LocalScript 
	local script = Instance.new('LocalScript', close)

	script.Parent.MouseButton1Click:Connect(function()
		script.Parent.Parent.Parent.Visible = false
	end)
	
	
	
	
end
coroutine.wrap(QZOBQMN_fake_script)()
local function HCYYK_fake_script() -- PREMIUMFRAME.LocalScript 
	local script = Instance.new('LocalScript', PREMIUMFRAME)

	local frame = script.Parent.Parent.LIGHTUX --in the .frame - you should need to change it what is your frame name.
	local hotkey = Enum.KeyCode.L --Change your keybind you want.
	
	local UIS = game:GetService("UserInputService")
	local open = true
	
	
	
	UIS.InputBegan:Connect(function(key, gp)
		if key.KeyCode == hotkey then
			if UIS:GetFocusedTextBox() == nil then
				if open == false then
					open = true 
					frame.Visible = open
				elseif open == true then
					open = false
					frame.Visible = open
				end
			end
		end
	end)
end
coroutine.wrap(HCYYK_fake_script)()
