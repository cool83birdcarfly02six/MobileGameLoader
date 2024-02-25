-- Gui to Lua
-- Version: 3.2

-- Instances:

local DEVICECHOOSER = Instance.new("ScreenGui")
local FitAllScreens = Instance.new("Frame")
local FitAllScreens_2 = Instance.new("Frame")
local MENUNotification = Instance.new("ImageLabel")
local UICorner = Instance.new("UICorner")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local Titles = Instance.new("TextLabel")
local Titles_2 = Instance.new("TextLabel")
local PC = Instance.new("TextButton")
local UICorner_2 = Instance.new("UICorner")
local Mobile = Instance.new("TextButton")
local UICorner_3 = Instance.new("UICorner")
local Close = Instance.new("ImageButton")
local UIListLayout = Instance.new("UIListLayout")
local UIListLayout_2 = Instance.new("UIListLayout")

--Properties:

DEVICECHOOSER.Name = "DEVICECHOOSER"
DEVICECHOOSER.Parent = game.CoreGui
DEVICECHOOSER.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

FitAllScreens.Name = "FitAllScreens"
FitAllScreens.Parent = DEVICECHOOSER
FitAllScreens.BackgroundColor3 = Color3.fromRGB(85, 255, 255)
FitAllScreens.BackgroundTransparency = 1.000
FitAllScreens.BorderColor3 = Color3.fromRGB(0, 0, 0)
FitAllScreens.BorderSizePixel = 0
FitAllScreens.Position = UDim2.new(0.798165143, 0, 0, 0)
FitAllScreens.Size = UDim2.new(0.0511140227, 230, 1, 0)

FitAllScreens_2.Name = "FitAllScreens"
FitAllScreens_2.Parent = FitAllScreens
FitAllScreens_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
FitAllScreens_2.BackgroundTransparency = 1.000
FitAllScreens_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
FitAllScreens_2.BorderSizePixel = 0
FitAllScreens_2.Position = UDim2.new(0, 0, 0.853597999, 0)
FitAllScreens_2.Size = UDim2.new(0, 308, 0, 117)

MENUNotification.Name = "MENU Notification"
MENUNotification.Parent = FitAllScreens_2
MENUNotification.BackgroundColor3 = Color3.fromRGB(39, 39, 39)
MENUNotification.BorderColor3 = Color3.fromRGB(0, 0, 0)
MENUNotification.BorderSizePixel = 0
MENUNotification.Position = UDim2.new(-0.0487012975, 0, 0.136752144, 0)
MENUNotification.Size = UDim2.new(0, 295, 0, 94)
MENUNotification.Image = "http://www.roblox.com/asset/?id=15229583503"
MENUNotification.ScaleType = Enum.ScaleType.Crop

UICorner.Parent = MENUNotification

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = MENUNotification
DropShadowHolder.BackgroundTransparency = 1.000
DropShadowHolder.BorderSizePixel = 0
DropShadowHolder.Size = UDim2.new(1, 0, 1, 0)
DropShadowHolder.ZIndex = 0

DropShadow.Name = "DropShadow"
DropShadow.Parent = DropShadowHolder
DropShadow.AnchorPoint = Vector2.new(0.5, 0.5)
DropShadow.BackgroundTransparency = 1.000
DropShadow.BorderSizePixel = 0
DropShadow.Position = UDim2.new(0.5, 0, 0.5, 0)
DropShadow.Size = UDim2.new(1, 47, 1, 47)
DropShadow.ZIndex = 0
DropShadow.Image = "rbxassetid://6014261993"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.500
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

Titles.Name = "Titles"
Titles.Parent = MENUNotification
Titles.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Titles.BackgroundTransparency = 1.000
Titles.BorderColor3 = Color3.fromRGB(0, 0, 0)
Titles.BorderSizePixel = 0
Titles.Position = UDim2.new(0.0271186437, 0, 0.0809670314, 0)
Titles.Size = UDim2.new(0, 203, 0, 20)
Titles.Font = Enum.Font.SourceSansBold
Titles.Text = "Welcome To Lightux!"
Titles.TextColor3 = Color3.fromRGB(255, 255, 255)
Titles.TextSize = 20.000
Titles.TextXAlignment = Enum.TextXAlignment.Left
Titles.TextYAlignment = Enum.TextYAlignment.Top

Titles_2.Name = "Titles"
Titles_2.Parent = MENUNotification
Titles_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Titles_2.BackgroundTransparency = 1.000
Titles_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Titles_2.BorderSizePixel = 0
Titles_2.Position = UDim2.new(0.0271186437, 0, 0.28309533, 0)
Titles_2.Size = UDim2.new(0, 203, 0, 19)
Titles_2.Font = Enum.Font.SourceSansBold
Titles_2.Text = "Please select the device you are using"
Titles_2.TextColor3 = Color3.fromRGB(134, 134, 134)
Titles_2.TextSize = 14.000
Titles_2.TextXAlignment = Enum.TextXAlignment.Left

PC.Name = "PC"
PC.Parent = MENUNotification
PC.BackgroundColor3 = Color3.fromRGB(75, 151, 226)
PC.BorderColor3 = Color3.fromRGB(0, 0, 0)
PC.BorderSizePixel = 0
PC.Position = UDim2.new(0.0271186437, 0, 0.570928037, 0)
PC.Size = UDim2.new(0, 105, 0, 28)
PC.Font = Enum.Font.SourceSansBold
PC.Text = "PC"
PC.TextColor3 = Color3.fromRGB(255, 255, 255)
PC.TextSize = 17.000

UICorner_2.Parent = PC

Mobile.Name = "Mobile"
Mobile.Parent = MENUNotification
Mobile.BackgroundColor3 = Color3.fromRGB(75, 151, 226)
Mobile.BorderColor3 = Color3.fromRGB(0, 0, 0)
Mobile.BorderSizePixel = 0
Mobile.Position = UDim2.new(0.406779647, 0, 0.570927858, 0)
Mobile.Size = UDim2.new(0, 105, 0, 28)
Mobile.Font = Enum.Font.SourceSansBold
Mobile.Text = "Mobile"
Mobile.TextColor3 = Color3.fromRGB(255, 255, 255)
Mobile.TextSize = 17.000

UICorner_3.Parent = Mobile

Close.Name = "Close"
Close.Parent = MENUNotification
Close.Active = false
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.912914932, 0, 0.0529724769, 0)
Close.Selectable = false
Close.Size = UDim2.new(0, 21, 0, 21)
Close.Image = "http://www.roblox.com/asset/?id=12707060750"

UIListLayout.Parent = FitAllScreens
UIListLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder
UIListLayout.VerticalAlignment = Enum.VerticalAlignment.Bottom

UIListLayout_2.Parent = DEVICECHOOSER
UIListLayout_2.HorizontalAlignment = Enum.HorizontalAlignment.Right
UIListLayout_2.SortOrder = Enum.SortOrder.LayoutOrder

-- Scripts:

local function ZIIJUN_fake_script() -- PC.LocalScript 
	local script = Instance.new('LocalScript', PC)

	script.Parent.MouseButton1Down:connect(function()
	
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/PCGAMECHECKERLOADER/main/README.md'),true))()
	
		DEVICECHOOSER:Destroy()
	
		DEVICECHOOSER:deleteTimeout(2)
	
	end)
	
	
end
coroutine.wrap(ZIIJUN_fake_script)()
local function CCUY_fake_script() -- Mobile.LocalScript 
	local script = Instance.new('LocalScript', Mobile)

	script.Parent.MouseButton1Down:connect(function()
	
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/MobileGameLoader/main/README.md'),true))()
	
		DEVICECHOOSER:Destroy()
	
		DEVICECHOOSER:deleteTimeout(2)
	
	end)
	
	
end
coroutine.wrap(CCUY_fake_script)()
local function NZDFVD_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Down:connect(function()
	
		DEVICECHOOSER:Destroy()
	
		DEVICECHOOSER:deleteTimeout(2)
	
	end)
end
coroutine.wrap(NZDFVD_fake_script)()
