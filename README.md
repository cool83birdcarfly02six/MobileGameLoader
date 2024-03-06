-- Gui to Lua
-- Version: 3.2

-- Instances:

local GAMEGUIGUI = Instance.new("ScreenGui")
local Background = Instance.new("Frame")
local UICorner = Instance.new("UICorner")
local DropShadowHolder = Instance.new("Frame")
local DropShadow = Instance.new("ImageLabel")
local SupporGamesPage = Instance.new("Frame")
local UICorner_2 = Instance.new("UICorner")
local Cover = Instance.new("Frame")
local TopImage = Instance.new("ImageLabel")
local UICorner_3 = Instance.new("UICorner")
local SideDarkFades = Instance.new("ImageLabel")
local UICorner_4 = Instance.new("UICorner")
local Title = Instance.new("TextLabel")
local Title_2 = Instance.new("TextLabel")
local ScrollingFrame = Instance.new("ScrollingFrame")
local UIListLayout = Instance.new("UIListLayout")
local ZombieAttack = Instance.new("Frame")
local Frame = Instance.new("Frame")
local TextLabel = Instance.new("TextLabel")
local TextLabel_2 = Instance.new("TextLabel")
local TextButton = Instance.new("TextButton")
local UICorner_5 = Instance.new("UICorner")
local UICorner_6 = Instance.new("UICorner")
local ImageLabel = Instance.new("ImageLabel")
local PrisonLife = Instance.new("Frame")
local Frame_2 = Instance.new("Frame")
local ImageLabel_2 = Instance.new("ImageLabel")
local TextLabel_3 = Instance.new("TextLabel")
local TextLabel_4 = Instance.new("TextLabel")
local TextButton_2 = Instance.new("TextButton")
local UICorner_7 = Instance.new("UICorner")
local UICorner_8 = Instance.new("UICorner")
local LUCKYBLOCKSBattlegrounds = Instance.new("Frame")
local Frame_3 = Instance.new("Frame")
local ImageLabel_3 = Instance.new("ImageLabel")
local TextLabel_5 = Instance.new("TextLabel")
local TextLabel_6 = Instance.new("TextLabel")
local TextButton_3 = Instance.new("TextButton")
local UICorner_9 = Instance.new("UICorner")
local UICorner_10 = Instance.new("UICorner")
local TowerOfHell = Instance.new("Frame")
local Frame_4 = Instance.new("Frame")
local ImageLabel_4 = Instance.new("ImageLabel")
local TextLabel_7 = Instance.new("TextLabel")
local TextLabel_8 = Instance.new("TextLabel")
local TextButton_4 = Instance.new("TextButton")
local UICorner_11 = Instance.new("UICorner")
local UICorner_12 = Instance.new("UICorner")
local AllofUsAreDead = Instance.new("Frame")
local Frame_5 = Instance.new("Frame")
local ImageLabel_5 = Instance.new("ImageLabel")
local TextLabel_9 = Instance.new("TextLabel")
local TextLabel_10 = Instance.new("TextLabel")
local TextButton_5 = Instance.new("TextButton")
local UICorner_13 = Instance.new("UICorner")
local UICorner_14 = Instance.new("UICorner")
local EverySecondYouGet1JumpPower = Instance.new("Frame")
local Frame_6 = Instance.new("Frame")
local ImageLabel_6 = Instance.new("ImageLabel")
local TextLabel_11 = Instance.new("TextLabel")
local TextLabel_12 = Instance.new("TextLabel")
local TextButton_6 = Instance.new("TextButton")
local UICorner_15 = Instance.new("UICorner")
local UICorner_16 = Instance.new("UICorner")
local KAT = Instance.new("Frame")
local Frame_7 = Instance.new("Frame")
local ImageLabel_7 = Instance.new("ImageLabel")
local TextLabel_13 = Instance.new("TextLabel")
local TextLabel_14 = Instance.new("TextLabel")
local TextButton_7 = Instance.new("TextButton")
local UICorner_17 = Instance.new("UICorner")
local UICorner_18 = Instance.new("UICorner")
local ShadowBoxingBattles = Instance.new("Frame")
local Frame_8 = Instance.new("Frame")
local ImageLabel_8 = Instance.new("ImageLabel")
local TextLabel_15 = Instance.new("TextLabel")
local TextLabel_16 = Instance.new("TextLabel")
local TextButton_8 = Instance.new("TextButton")
local UICorner_19 = Instance.new("UICorner")
local UICorner_20 = Instance.new("UICorner")
local DrivingEmpire = Instance.new("Frame")
local Frame_9 = Instance.new("Frame")
local ImageLabel_9 = Instance.new("ImageLabel")
local TextLabel_17 = Instance.new("TextLabel")
local TextLabel_18 = Instance.new("TextLabel")
local TextButton_9 = Instance.new("TextButton")
local UICorner_21 = Instance.new("UICorner")
local UICorner_22 = Instance.new("UICorner")
local BulkedUp = Instance.new("Frame")
local Frame_10 = Instance.new("Frame")
local ImageLabel_10 = Instance.new("ImageLabel")
local TextLabel_19 = Instance.new("TextLabel")
local TextLabel_20 = Instance.new("TextLabel")
local TextButton_10 = Instance.new("TextButton")
local UICorner_23 = Instance.new("UICorner")
local UICorner_24 = Instance.new("UICorner")
local Greenville = Instance.new("Frame")
local Frame_11 = Instance.new("Frame")
local ImageLabel_11 = Instance.new("ImageLabel")
local TextLabel_21 = Instance.new("TextLabel")
local TextLabel_22 = Instance.new("TextLabel")
local TextButton_11 = Instance.new("TextButton")
local UICorner_25 = Instance.new("UICorner")
local UICorner_26 = Instance.new("UICorner")
local BladeBall = Instance.new("Frame")
local Frame_12 = Instance.new("Frame")
local ImageLabel_12 = Instance.new("ImageLabel")
local TextLabel_23 = Instance.new("TextLabel")
local TextLabel_24 = Instance.new("TextLabel")
local TextButton_12 = Instance.new("TextButton")
local UICorner_27 = Instance.new("UICorner")
local UICorner_28 = Instance.new("UICorner")
local TheStrongestBattlegrounds = Instance.new("Frame")
local Frame_13 = Instance.new("Frame")
local ImageLabel_13 = Instance.new("ImageLabel")
local TextLabel_25 = Instance.new("TextLabel")
local TextLabel_26 = Instance.new("TextLabel")
local TextButton_13 = Instance.new("TextButton")
local UICorner_29 = Instance.new("UICorner")
local UICorner_30 = Instance.new("UICorner")
local Tabs = Instance.new("Frame")
local UICorner_31 = Instance.new("UICorner")
local Cover_2 = Instance.new("Frame")
local ImageLabel_14 = Instance.new("ImageLabel")
local SuppGamesButton = Instance.new("ImageButton")
local Close = Instance.new("ImageButton")

--Properties:

GAMEGUIGUI.Name = "GAMEGUIGUI"
GAMEGUIGUI.Parent = game.CoreGui
GAMEGUIGUI.ZIndexBehavior = Enum.ZIndexBehavior.Sibling

Background.Name = "Background"
Background.Parent = GAMEGUIGUI
Background.BackgroundColor3 = Color3.fromRGB(15, 15, 15)
Background.BorderColor3 = Color3.fromRGB(0, 0, 0)
Background.BorderSizePixel = 0
Background.Position = UDim2.new(0.360949278, 0, 0.324419647, 0)
Background.Size = UDim2.new(0, 449, 0, 283)

UICorner.Parent = Background

DropShadowHolder.Name = "DropShadowHolder"
DropShadowHolder.Parent = Background
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
DropShadow.Image = "rbxassetid://6015897843"
DropShadow.ImageColor3 = Color3.fromRGB(0, 0, 0)
DropShadow.ImageTransparency = 0.500
DropShadow.ScaleType = Enum.ScaleType.Slice
DropShadow.SliceCenter = Rect.new(49, 49, 450, 450)

SupporGamesPage.Name = "SupporGamesPage"
SupporGamesPage.Parent = Background
SupporGamesPage.BackgroundColor3 = Color3.fromRGB(8, 8, 8)
SupporGamesPage.BorderColor3 = Color3.fromRGB(0, 0, 0)
SupporGamesPage.BorderSizePixel = 0
SupporGamesPage.Position = UDim2.new(0.102881074, 0, 0.395759732, 0)
SupporGamesPage.Size = UDim2.new(0, 402, 0, 171)

UICorner_2.Parent = SupporGamesPage

Cover.Name = "Cover"
Cover.Parent = SupporGamesPage
Cover.BackgroundColor3 = Color3.fromRGB(8, 8, 8)
Cover.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cover.BorderSizePixel = 0
Cover.Position = UDim2.new(0.0190879107, 0, -0.00408435846, 0)
Cover.Size = UDim2.new(0, 395, 0, 10)

TopImage.Name = "TopImage"
TopImage.Parent = SupporGamesPage
TopImage.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
TopImage.BackgroundTransparency = 1.000
TopImage.BorderColor3 = Color3.fromRGB(0, 0, 0)
TopImage.BorderSizePixel = 0
TopImage.Position = UDim2.new(0, 0, -0.655000031, 0)
TopImage.Size = UDim2.new(0, 402, 0, 120)
TopImage.Image = "http://www.roblox.com/asset/?id=14722784726"
TopImage.ImageTransparency = 0.400

UICorner_3.Parent = TopImage

SideDarkFades.Name = "SideDarkFades"
SideDarkFades.Parent = TopImage
SideDarkFades.BackgroundColor3 = Color3.fromRGB(26, 26, 26)
SideDarkFades.BackgroundTransparency = 1.000
SideDarkFades.BorderColor3 = Color3.fromRGB(0, 0, 0)
SideDarkFades.BorderSizePixel = 0
SideDarkFades.Position = UDim2.new(0.0190879107, 0, 0.00333328242, 0)
SideDarkFades.Size = UDim2.new(0, 394, 0, 120)
SideDarkFades.Image = "http://www.roblox.com/asset/?id=14722131500"

UICorner_4.Parent = SideDarkFades

Title.Name = "Title"
Title.Parent = TopImage
Title.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title.BackgroundTransparency = 1.000
Title.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title.BorderSizePixel = 0
Title.Position = UDim2.new(0.0293691456, 0, 0.166666672, 0)
Title.Size = UDim2.new(0, 391, 0, 45)
Title.Font = Enum.Font.ArialBold
Title.Text = "Supported Games"
Title.TextColor3 = Color3.fromRGB(85, 170, 255)
Title.TextSize = 25.000

Title_2.Name = "Title"
Title_2.Parent = TopImage
Title_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Title_2.BackgroundTransparency = 1.000
Title_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Title_2.BorderSizePixel = 0
Title_2.Position = UDim2.new(0.0293691456, 0, 0.450041711, 0)
Title_2.Size = UDim2.new(0, 391, 0, 21)
Title_2.Font = Enum.Font.ArialBold
Title_2.Text = "Choose the game you want to load"
Title_2.TextColor3 = Color3.fromRGB(255, 255, 255)
Title_2.TextSize = 12.000

ScrollingFrame.Parent = SupporGamesPage
ScrollingFrame.Active = true
ScrollingFrame.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ScrollingFrame.BackgroundTransparency = 1.000
ScrollingFrame.BorderColor3 = Color3.fromRGB(0, 0, 0)
ScrollingFrame.BorderSizePixel = 0
ScrollingFrame.Position = UDim2.new(0.0105171772, 0, -0.00408435846, 0)
ScrollingFrame.Size = UDim2.new(0, 397, 0, 171)
ScrollingFrame.CanvasSize = UDim2.new(0, 0, 5, 200)
ScrollingFrame.ScrollBarThickness = 2

UIListLayout.Parent = ScrollingFrame
UIListLayout.HorizontalAlignment = Enum.HorizontalAlignment.Center
UIListLayout.SortOrder = Enum.SortOrder.LayoutOrder

ZombieAttack.Name = "ZombieAttack"
ZombieAttack.Parent = ScrollingFrame
ZombieAttack.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
ZombieAttack.BackgroundTransparency = 1.000
ZombieAttack.BorderColor3 = Color3.fromRGB(0, 0, 0)
ZombieAttack.BorderSizePixel = 0
ZombieAttack.Position = UDim2.new(0.0321336761, 0, 0, 0)
ZombieAttack.Size = UDim2.new(0, 364, 0, 75)

Frame.Parent = ZombieAttack
Frame.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame.BorderSizePixel = 0
Frame.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame.Size = UDim2.new(0, 356, 0, 63)

TextLabel.Parent = Frame
TextLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.BackgroundTransparency = 1.000
TextLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel.BorderSizePixel = 0
TextLabel.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel.Size = UDim2.new(0, 200, 0, 17)
TextLabel.Font = Enum.Font.ArialBold
TextLabel.Text = "Zombie Attack"
TextLabel.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel.TextSize = 12.000
TextLabel.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_2.Parent = Frame
TextLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_2.BackgroundTransparency = 1.000
TextLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_2.BorderSizePixel = 0
TextLabel_2.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_2.Size = UDim2.new(0, 200, 0, 12)
TextLabel_2.Font = Enum.Font.ArialBold
TextLabel_2.Text = "Last Update: 26/02/24"
TextLabel_2.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_2.TextSize = 9.000
TextLabel_2.TextXAlignment = Enum.TextXAlignment.Left

TextButton.Parent = Frame
TextButton.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton.BorderSizePixel = 0
TextButton.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton.Size = UDim2.new(0, 103, 0, 28)
TextButton.Font = Enum.Font.SourceSans
TextButton.Text = "Load"
TextButton.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton.TextSize = 14.000

UICorner_5.CornerRadius = UDim.new(0, 3)
UICorner_5.Parent = TextButton

UICorner_6.CornerRadius = UDim.new(0, 3)
UICorner_6.Parent = Frame

ImageLabel.Parent = Frame
ImageLabel.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel.BorderSizePixel = 0
ImageLabel.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel.Size = UDim2.new(0, 40, 0, 40)
ImageLabel.Image = "http://www.roblox.com/asset/?id=12471230958"

PrisonLife.Name = "PrisonLife"
PrisonLife.Parent = ScrollingFrame
PrisonLife.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
PrisonLife.BackgroundTransparency = 1.000
PrisonLife.BorderColor3 = Color3.fromRGB(0, 0, 0)
PrisonLife.BorderSizePixel = 0
PrisonLife.Position = UDim2.new(0.0321336761, 0, 0, 0)
PrisonLife.Size = UDim2.new(0, 364, 0, 75)
PrisonLife.Visible = false

Frame_2.Parent = PrisonLife
Frame_2.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_2.BorderSizePixel = 0
Frame_2.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_2.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_2.Parent = Frame_2
ImageLabel_2.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_2.BorderSizePixel = 0
ImageLabel_2.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_2.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_2.Image = "http://www.roblox.com/asset/?id=13818775017"

TextLabel_3.Parent = Frame_2
TextLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.BackgroundTransparency = 1.000
TextLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_3.BorderSizePixel = 0
TextLabel_3.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_3.Size = UDim2.new(0, 200, 0, 17)
TextLabel_3.Font = Enum.Font.ArialBold
TextLabel_3.Text = "Prison Life"
TextLabel_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_3.TextSize = 12.000
TextLabel_3.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_4.Parent = Frame_2
TextLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_4.BackgroundTransparency = 1.000
TextLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_4.BorderSizePixel = 0
TextLabel_4.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_4.Size = UDim2.new(0, 200, 0, 12)
TextLabel_4.Font = Enum.Font.ArialBold
TextLabel_4.Text = "Last Update: 00/00/00"
TextLabel_4.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_4.TextSize = 9.000
TextLabel_4.TextXAlignment = Enum.TextXAlignment.Left

TextButton_2.Parent = Frame_2
TextButton_2.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_2.BorderSizePixel = 0
TextButton_2.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_2.Size = UDim2.new(0, 103, 0, 28)
TextButton_2.Font = Enum.Font.SourceSans
TextButton_2.Text = "Load"
TextButton_2.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_2.TextSize = 14.000

UICorner_7.CornerRadius = UDim.new(0, 3)
UICorner_7.Parent = TextButton_2

UICorner_8.CornerRadius = UDim.new(0, 3)
UICorner_8.Parent = Frame_2

LUCKYBLOCKSBattlegrounds.Name = "LUCKY BLOCKS Battlegrounds"
LUCKYBLOCKSBattlegrounds.Parent = ScrollingFrame
LUCKYBLOCKSBattlegrounds.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
LUCKYBLOCKSBattlegrounds.BackgroundTransparency = 1.000
LUCKYBLOCKSBattlegrounds.BorderColor3 = Color3.fromRGB(0, 0, 0)
LUCKYBLOCKSBattlegrounds.BorderSizePixel = 0
LUCKYBLOCKSBattlegrounds.Position = UDim2.new(0.0321336761, 0, 0, 0)
LUCKYBLOCKSBattlegrounds.Size = UDim2.new(0, 364, 0, 75)
LUCKYBLOCKSBattlegrounds.Visible = false

Frame_3.Parent = LUCKYBLOCKSBattlegrounds
Frame_3.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_3.BorderSizePixel = 0
Frame_3.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_3.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_3.Parent = Frame_3
ImageLabel_3.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_3.BorderSizePixel = 0
ImageLabel_3.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_3.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_3.Image = "http://www.roblox.com/asset/?id=14764947712"

TextLabel_5.Parent = Frame_3
TextLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.BackgroundTransparency = 1.000
TextLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_5.BorderSizePixel = 0
TextLabel_5.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_5.Size = UDim2.new(0, 200, 0, 17)
TextLabel_5.Font = Enum.Font.ArialBold
TextLabel_5.Text = "LUCKY BLOCKS Battlegrounds"
TextLabel_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_5.TextSize = 12.000
TextLabel_5.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_6.Parent = Frame_3
TextLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_6.BackgroundTransparency = 1.000
TextLabel_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_6.BorderSizePixel = 0
TextLabel_6.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_6.Size = UDim2.new(0, 200, 0, 12)
TextLabel_6.Font = Enum.Font.ArialBold
TextLabel_6.Text = "Last Update: 00/00/00"
TextLabel_6.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_6.TextSize = 9.000
TextLabel_6.TextXAlignment = Enum.TextXAlignment.Left

TextButton_3.Parent = Frame_3
TextButton_3.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_3.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_3.BorderSizePixel = 0
TextButton_3.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_3.Size = UDim2.new(0, 103, 0, 28)
TextButton_3.Font = Enum.Font.SourceSans
TextButton_3.Text = "Load"
TextButton_3.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_3.TextSize = 14.000

UICorner_9.CornerRadius = UDim.new(0, 3)
UICorner_9.Parent = TextButton_3

UICorner_10.CornerRadius = UDim.new(0, 3)
UICorner_10.Parent = Frame_3

TowerOfHell.Name = "Tower Of Hell"
TowerOfHell.Parent = ScrollingFrame
TowerOfHell.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
TowerOfHell.BackgroundTransparency = 1.000
TowerOfHell.BorderColor3 = Color3.fromRGB(0, 0, 0)
TowerOfHell.BorderSizePixel = 0
TowerOfHell.Position = UDim2.new(0.0321336761, 0, 0, 0)
TowerOfHell.Size = UDim2.new(0, 364, 0, 75)
TowerOfHell.Visible = false

Frame_4.Parent = TowerOfHell
Frame_4.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_4.BorderSizePixel = 0
Frame_4.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_4.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_4.Parent = Frame_4
ImageLabel_4.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_4.BorderSizePixel = 0
ImageLabel_4.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_4.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_4.Image = "http://www.roblox.com/asset/?id=14764957089"

TextLabel_7.Parent = Frame_4
TextLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.BackgroundTransparency = 1.000
TextLabel_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_7.BorderSizePixel = 0
TextLabel_7.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_7.Size = UDim2.new(0, 200, 0, 17)
TextLabel_7.Font = Enum.Font.ArialBold
TextLabel_7.Text = "Tower Of Hell"
TextLabel_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_7.TextSize = 12.000
TextLabel_7.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_8.Parent = Frame_4
TextLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_8.BackgroundTransparency = 1.000
TextLabel_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_8.BorderSizePixel = 0
TextLabel_8.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_8.Size = UDim2.new(0, 200, 0, 12)
TextLabel_8.Font = Enum.Font.ArialBold
TextLabel_8.Text = "Last Update: 00/00/00"
TextLabel_8.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_8.TextSize = 9.000
TextLabel_8.TextXAlignment = Enum.TextXAlignment.Left

TextButton_4.Parent = Frame_4
TextButton_4.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_4.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_4.BorderSizePixel = 0
TextButton_4.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_4.Size = UDim2.new(0, 103, 0, 28)
TextButton_4.Font = Enum.Font.SourceSans
TextButton_4.Text = "Load"
TextButton_4.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_4.TextSize = 14.000

UICorner_11.CornerRadius = UDim.new(0, 3)
UICorner_11.Parent = TextButton_4

UICorner_12.CornerRadius = UDim.new(0, 3)
UICorner_12.Parent = Frame_4

AllofUsAreDead.Name = "All of Us Are Dead"
AllofUsAreDead.Parent = ScrollingFrame
AllofUsAreDead.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
AllofUsAreDead.BackgroundTransparency = 1.000
AllofUsAreDead.BorderColor3 = Color3.fromRGB(0, 0, 0)
AllofUsAreDead.BorderSizePixel = 0
AllofUsAreDead.Position = UDim2.new(0.0321336761, 0, 0, 0)
AllofUsAreDead.Size = UDim2.new(0, 364, 0, 75)
AllofUsAreDead.Visible = false

Frame_5.Parent = AllofUsAreDead
Frame_5.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_5.BorderSizePixel = 0
Frame_5.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_5.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_5.Parent = Frame_5
ImageLabel_5.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_5.BackgroundTransparency = 1.000
ImageLabel_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_5.BorderSizePixel = 0
ImageLabel_5.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_5.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_5.Image = "http://www.roblox.com/asset/?id=14764974945"

TextLabel_9.Parent = Frame_5
TextLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.BackgroundTransparency = 1.000
TextLabel_9.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_9.BorderSizePixel = 0
TextLabel_9.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_9.Size = UDim2.new(0, 200, 0, 17)
TextLabel_9.Font = Enum.Font.ArialBold
TextLabel_9.Text = "All of Us Are Dead"
TextLabel_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_9.TextSize = 12.000
TextLabel_9.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_10.Parent = Frame_5
TextLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_10.BackgroundTransparency = 1.000
TextLabel_10.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_10.BorderSizePixel = 0
TextLabel_10.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_10.Size = UDim2.new(0, 200, 0, 12)
TextLabel_10.Font = Enum.Font.ArialBold
TextLabel_10.Text = "Last Update: 00/00/00"
TextLabel_10.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_10.TextSize = 9.000
TextLabel_10.TextXAlignment = Enum.TextXAlignment.Left

TextButton_5.Parent = Frame_5
TextButton_5.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_5.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_5.BorderSizePixel = 0
TextButton_5.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_5.Size = UDim2.new(0, 103, 0, 28)
TextButton_5.Font = Enum.Font.SourceSans
TextButton_5.Text = "Load"
TextButton_5.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_5.TextSize = 14.000

UICorner_13.CornerRadius = UDim.new(0, 3)
UICorner_13.Parent = TextButton_5

UICorner_14.CornerRadius = UDim.new(0, 3)
UICorner_14.Parent = Frame_5

EverySecondYouGet1JumpPower.Name = "Every Second You Get +1 Jump Power"
EverySecondYouGet1JumpPower.Parent = ScrollingFrame
EverySecondYouGet1JumpPower.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
EverySecondYouGet1JumpPower.BackgroundTransparency = 1.000
EverySecondYouGet1JumpPower.BorderColor3 = Color3.fromRGB(0, 0, 0)
EverySecondYouGet1JumpPower.BorderSizePixel = 0
EverySecondYouGet1JumpPower.Position = UDim2.new(0.0321336761, 0, 0, 0)
EverySecondYouGet1JumpPower.Size = UDim2.new(0, 364, 0, 75)
EverySecondYouGet1JumpPower.Visible = false

Frame_6.Parent = EverySecondYouGet1JumpPower
Frame_6.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_6.BorderSizePixel = 0
Frame_6.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_6.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_6.Parent = Frame_6
ImageLabel_6.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_6.BackgroundTransparency = 1.000
ImageLabel_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_6.BorderSizePixel = 0
ImageLabel_6.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_6.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_6.Image = "http://www.roblox.com/asset/?id=14484921401"

TextLabel_11.Parent = Frame_6
TextLabel_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_11.BackgroundTransparency = 1.000
TextLabel_11.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_11.BorderSizePixel = 0
TextLabel_11.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_11.Size = UDim2.new(0, 200, 0, 17)
TextLabel_11.Font = Enum.Font.ArialBold
TextLabel_11.Text = "Every Second You Get +1 Jump Power"
TextLabel_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_11.TextSize = 12.000
TextLabel_11.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_12.Parent = Frame_6
TextLabel_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_12.BackgroundTransparency = 1.000
TextLabel_12.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_12.BorderSizePixel = 0
TextLabel_12.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_12.Size = UDim2.new(0, 200, 0, 12)
TextLabel_12.Font = Enum.Font.ArialBold
TextLabel_12.Text = "Last Update: 00/00/00"
TextLabel_12.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_12.TextSize = 9.000
TextLabel_12.TextXAlignment = Enum.TextXAlignment.Left

TextButton_6.Parent = Frame_6
TextButton_6.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_6.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_6.BorderSizePixel = 0
TextButton_6.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_6.Size = UDim2.new(0, 103, 0, 28)
TextButton_6.Font = Enum.Font.SourceSans
TextButton_6.Text = "Load"
TextButton_6.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_6.TextSize = 14.000

UICorner_15.CornerRadius = UDim.new(0, 3)
UICorner_15.Parent = TextButton_6

UICorner_16.CornerRadius = UDim.new(0, 3)
UICorner_16.Parent = Frame_6

KAT.Name = "KAT"
KAT.Parent = ScrollingFrame
KAT.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
KAT.BackgroundTransparency = 1.000
KAT.BorderColor3 = Color3.fromRGB(0, 0, 0)
KAT.BorderSizePixel = 0
KAT.Position = UDim2.new(0.0321336761, 0, 0, 0)
KAT.Size = UDim2.new(0, 364, 0, 75)
KAT.Visible = false

Frame_7.Parent = KAT
Frame_7.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_7.BorderSizePixel = 0
Frame_7.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_7.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_7.Parent = Frame_7
ImageLabel_7.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_7.BackgroundTransparency = 1.000
ImageLabel_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_7.BorderSizePixel = 0
ImageLabel_7.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_7.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_7.Image = "http://www.roblox.com/asset/?id=14764993603"

TextLabel_13.Parent = Frame_7
TextLabel_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_13.BackgroundTransparency = 1.000
TextLabel_13.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_13.BorderSizePixel = 0
TextLabel_13.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_13.Size = UDim2.new(0, 200, 0, 17)
TextLabel_13.Font = Enum.Font.ArialBold
TextLabel_13.Text = "KAT"
TextLabel_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_13.TextSize = 12.000
TextLabel_13.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_14.Parent = Frame_7
TextLabel_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_14.BackgroundTransparency = 1.000
TextLabel_14.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_14.BorderSizePixel = 0
TextLabel_14.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_14.Size = UDim2.new(0, 200, 0, 12)
TextLabel_14.Font = Enum.Font.ArialBold
TextLabel_14.Text = "Last Update: 00/00/00"
TextLabel_14.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_14.TextSize = 9.000
TextLabel_14.TextXAlignment = Enum.TextXAlignment.Left

TextButton_7.Parent = Frame_7
TextButton_7.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_7.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_7.BorderSizePixel = 0
TextButton_7.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_7.Size = UDim2.new(0, 103, 0, 28)
TextButton_7.Font = Enum.Font.SourceSans
TextButton_7.Text = "Load"
TextButton_7.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_7.TextSize = 14.000

UICorner_17.CornerRadius = UDim.new(0, 3)
UICorner_17.Parent = TextButton_7

UICorner_18.CornerRadius = UDim.new(0, 3)
UICorner_18.Parent = Frame_7

ShadowBoxingBattles.Name = "Shadow Boxing Battles"
ShadowBoxingBattles.Parent = ScrollingFrame
ShadowBoxingBattles.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
ShadowBoxingBattles.BackgroundTransparency = 1.000
ShadowBoxingBattles.BorderColor3 = Color3.fromRGB(0, 0, 0)
ShadowBoxingBattles.BorderSizePixel = 0
ShadowBoxingBattles.Position = UDim2.new(0.0321336761, 0, 0, 0)
ShadowBoxingBattles.Size = UDim2.new(0, 364, 0, 75)
ShadowBoxingBattles.Visible = false

Frame_8.Parent = ShadowBoxingBattles
Frame_8.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_8.BorderSizePixel = 0
Frame_8.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_8.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_8.Parent = Frame_8
ImageLabel_8.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_8.BackgroundTransparency = 1.000
ImageLabel_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_8.BorderSizePixel = 0
ImageLabel_8.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_8.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_8.Image = "http://www.roblox.com/asset/?id=14168113901"

TextLabel_15.Parent = Frame_8
TextLabel_15.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_15.BackgroundTransparency = 1.000
TextLabel_15.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_15.BorderSizePixel = 0
TextLabel_15.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_15.Size = UDim2.new(0, 200, 0, 17)
TextLabel_15.Font = Enum.Font.ArialBold
TextLabel_15.Text = "Shadow Boxing Battles"
TextLabel_15.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_15.TextSize = 12.000
TextLabel_15.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_16.Parent = Frame_8
TextLabel_16.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_16.BackgroundTransparency = 1.000
TextLabel_16.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_16.BorderSizePixel = 0
TextLabel_16.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_16.Size = UDim2.new(0, 200, 0, 12)
TextLabel_16.Font = Enum.Font.ArialBold
TextLabel_16.Text = "Last Update: 00/00/00"
TextLabel_16.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_16.TextSize = 9.000
TextLabel_16.TextXAlignment = Enum.TextXAlignment.Left

TextButton_8.Parent = Frame_8
TextButton_8.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_8.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_8.BorderSizePixel = 0
TextButton_8.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_8.Size = UDim2.new(0, 103, 0, 28)
TextButton_8.Font = Enum.Font.SourceSans
TextButton_8.Text = "Load"
TextButton_8.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_8.TextSize = 14.000

UICorner_19.CornerRadius = UDim.new(0, 3)
UICorner_19.Parent = TextButton_8

UICorner_20.CornerRadius = UDim.new(0, 3)
UICorner_20.Parent = Frame_8

DrivingEmpire.Name = "Driving Empire"
DrivingEmpire.Parent = ScrollingFrame
DrivingEmpire.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
DrivingEmpire.BackgroundTransparency = 1.000
DrivingEmpire.BorderColor3 = Color3.fromRGB(0, 0, 0)
DrivingEmpire.BorderSizePixel = 0
DrivingEmpire.Position = UDim2.new(0.0321336761, 0, 0, 0)
DrivingEmpire.Size = UDim2.new(0, 364, 0, 75)

Frame_9.Parent = DrivingEmpire
Frame_9.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_9.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_9.BorderSizePixel = 0
Frame_9.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_9.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_9.Parent = Frame_9
ImageLabel_9.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_9.BackgroundTransparency = 1.000
ImageLabel_9.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_9.BorderSizePixel = 0
ImageLabel_9.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_9.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_9.Image = "http://www.roblox.com/asset/?id=14321431463"

TextLabel_17.Parent = Frame_9
TextLabel_17.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_17.BackgroundTransparency = 1.000
TextLabel_17.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_17.BorderSizePixel = 0
TextLabel_17.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_17.Size = UDim2.new(0, 200, 0, 17)
TextLabel_17.Font = Enum.Font.ArialBold
TextLabel_17.Text = "Driving Empire"
TextLabel_17.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_17.TextSize = 12.000
TextLabel_17.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_18.Parent = Frame_9
TextLabel_18.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_18.BackgroundTransparency = 1.000
TextLabel_18.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_18.BorderSizePixel = 0
TextLabel_18.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_18.Size = UDim2.new(0, 200, 0, 12)
TextLabel_18.Font = Enum.Font.ArialBold
TextLabel_18.Text = "Last Update: 00/00/00"
TextLabel_18.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_18.TextSize = 9.000
TextLabel_18.TextXAlignment = Enum.TextXAlignment.Left

TextButton_9.Parent = Frame_9
TextButton_9.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_9.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_9.BorderSizePixel = 0
TextButton_9.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_9.Size = UDim2.new(0, 103, 0, 28)
TextButton_9.Font = Enum.Font.SourceSans
TextButton_9.Text = "Load"
TextButton_9.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_9.TextSize = 14.000

UICorner_21.CornerRadius = UDim.new(0, 3)
UICorner_21.Parent = TextButton_9

UICorner_22.CornerRadius = UDim.new(0, 3)
UICorner_22.Parent = Frame_9

BulkedUp.Name = "Bulked Up"
BulkedUp.Parent = ScrollingFrame
BulkedUp.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
BulkedUp.BackgroundTransparency = 1.000
BulkedUp.BorderColor3 = Color3.fromRGB(0, 0, 0)
BulkedUp.BorderSizePixel = 0
BulkedUp.Position = UDim2.new(0.0321336761, 0, 0, 0)
BulkedUp.Size = UDim2.new(0, 364, 0, 75)
BulkedUp.Visible = false

Frame_10.Parent = BulkedUp
Frame_10.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_10.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_10.BorderSizePixel = 0
Frame_10.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_10.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_10.Parent = Frame_10
ImageLabel_10.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_10.BackgroundTransparency = 1.000
ImageLabel_10.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_10.BorderSizePixel = 0
ImageLabel_10.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_10.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_10.Image = "http://www.roblox.com/asset/?id=14765013900"

TextLabel_19.Parent = Frame_10
TextLabel_19.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_19.BackgroundTransparency = 1.000
TextLabel_19.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_19.BorderSizePixel = 0
TextLabel_19.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_19.Size = UDim2.new(0, 200, 0, 17)
TextLabel_19.Font = Enum.Font.ArialBold
TextLabel_19.Text = "Bulked Up"
TextLabel_19.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_19.TextSize = 12.000
TextLabel_19.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_20.Parent = Frame_10
TextLabel_20.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_20.BackgroundTransparency = 1.000
TextLabel_20.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_20.BorderSizePixel = 0
TextLabel_20.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_20.Size = UDim2.new(0, 200, 0, 12)
TextLabel_20.Font = Enum.Font.ArialBold
TextLabel_20.Text = "Last Update: 00/00/00"
TextLabel_20.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_20.TextSize = 9.000
TextLabel_20.TextXAlignment = Enum.TextXAlignment.Left

TextButton_10.Parent = Frame_10
TextButton_10.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_10.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_10.BorderSizePixel = 0
TextButton_10.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_10.Size = UDim2.new(0, 103, 0, 28)
TextButton_10.Font = Enum.Font.SourceSans
TextButton_10.Text = "Load"
TextButton_10.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_10.TextSize = 14.000

UICorner_23.CornerRadius = UDim.new(0, 3)
UICorner_23.Parent = TextButton_10

UICorner_24.CornerRadius = UDim.new(0, 3)
UICorner_24.Parent = Frame_10

Greenville.Name = "Greenville"
Greenville.Parent = ScrollingFrame
Greenville.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
Greenville.BackgroundTransparency = 1.000
Greenville.BorderColor3 = Color3.fromRGB(0, 0, 0)
Greenville.BorderSizePixel = 0
Greenville.Position = UDim2.new(0.0321336761, 0, 0, 0)
Greenville.Size = UDim2.new(0, 364, 0, 75)
Greenville.Visible = false

Frame_11.Parent = Greenville
Frame_11.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_11.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_11.BorderSizePixel = 0
Frame_11.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_11.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_11.Parent = Frame_11
ImageLabel_11.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_11.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_11.BorderSizePixel = 0
ImageLabel_11.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_11.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_11.Image = "http://www.roblox.com/asset/?id=14767606662"

TextLabel_21.Parent = Frame_11
TextLabel_21.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_21.BackgroundTransparency = 1.000
TextLabel_21.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_21.BorderSizePixel = 0
TextLabel_21.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_21.Size = UDim2.new(0, 200, 0, 17)
TextLabel_21.Font = Enum.Font.ArialBold
TextLabel_21.Text = "Greenville"
TextLabel_21.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_21.TextSize = 12.000
TextLabel_21.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_22.Parent = Frame_11
TextLabel_22.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_22.BackgroundTransparency = 1.000
TextLabel_22.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_22.BorderSizePixel = 0
TextLabel_22.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_22.Size = UDim2.new(0, 200, 0, 12)
TextLabel_22.Font = Enum.Font.ArialBold
TextLabel_22.Text = "Last Update: 13/09/2023"
TextLabel_22.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_22.TextSize = 9.000
TextLabel_22.TextXAlignment = Enum.TextXAlignment.Left

TextButton_11.Parent = Frame_11
TextButton_11.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_11.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_11.BorderSizePixel = 0
TextButton_11.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_11.Size = UDim2.new(0, 103, 0, 28)
TextButton_11.Font = Enum.Font.SourceSans
TextButton_11.Text = "Load"
TextButton_11.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_11.TextSize = 14.000

UICorner_25.CornerRadius = UDim.new(0, 3)
UICorner_25.Parent = TextButton_11

UICorner_26.CornerRadius = UDim.new(0, 3)
UICorner_26.Parent = Frame_11

BladeBall.Name = "BladeBall"
BladeBall.Parent = ScrollingFrame
BladeBall.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
BladeBall.BackgroundTransparency = 1.000
BladeBall.BorderColor3 = Color3.fromRGB(0, 0, 0)
BladeBall.BorderSizePixel = 0
BladeBall.Position = UDim2.new(0.0321336761, 0, 0, 0)
BladeBall.Size = UDim2.new(0, 364, 0, 75)
BladeBall.Visible = false

Frame_12.Parent = BladeBall
Frame_12.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_12.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_12.BorderSizePixel = 0
Frame_12.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_12.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_12.Parent = Frame_12
ImageLabel_12.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_12.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_12.BorderSizePixel = 0
ImageLabel_12.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_12.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_12.Image = "http://www.roblox.com/asset/?id=14797015628"

TextLabel_23.Parent = Frame_12
TextLabel_23.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_23.BackgroundTransparency = 1.000
TextLabel_23.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_23.BorderSizePixel = 0
TextLabel_23.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_23.Size = UDim2.new(0, 200, 0, 17)
TextLabel_23.Font = Enum.Font.ArialBold
TextLabel_23.Text = "Blade Ball"
TextLabel_23.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_23.TextSize = 12.000
TextLabel_23.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_24.Parent = Frame_12
TextLabel_24.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_24.BackgroundTransparency = 1.000
TextLabel_24.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_24.BorderSizePixel = 0
TextLabel_24.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_24.Size = UDim2.new(0, 200, 0, 12)
TextLabel_24.Font = Enum.Font.ArialBold
TextLabel_24.Text = "Last Update: 16/09/2023"
TextLabel_24.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_24.TextSize = 9.000
TextLabel_24.TextXAlignment = Enum.TextXAlignment.Left

TextButton_12.Parent = Frame_12
TextButton_12.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_12.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_12.BorderSizePixel = 0
TextButton_12.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_12.Size = UDim2.new(0, 103, 0, 28)
TextButton_12.Font = Enum.Font.SourceSans
TextButton_12.Text = "Load"
TextButton_12.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_12.TextSize = 14.000

UICorner_27.CornerRadius = UDim.new(0, 3)
UICorner_27.Parent = TextButton_12

UICorner_28.CornerRadius = UDim.new(0, 3)
UICorner_28.Parent = Frame_12

TheStrongestBattlegrounds.Name = "TheStrongestBattlegrounds"
TheStrongestBattlegrounds.Parent = ScrollingFrame
TheStrongestBattlegrounds.BackgroundColor3 = Color3.fromRGB(255, 170, 127)
TheStrongestBattlegrounds.BackgroundTransparency = 1.000
TheStrongestBattlegrounds.BorderColor3 = Color3.fromRGB(0, 0, 0)
TheStrongestBattlegrounds.BorderSizePixel = 0
TheStrongestBattlegrounds.Position = UDim2.new(0.0321336761, 0, 0, 0)
TheStrongestBattlegrounds.Size = UDim2.new(0, 364, 0, 75)

Frame_13.Parent = TheStrongestBattlegrounds
Frame_13.BackgroundColor3 = Color3.fromRGB(31, 31, 31)
Frame_13.BorderColor3 = Color3.fromRGB(0, 0, 0)
Frame_13.BorderSizePixel = 0
Frame_13.Position = UDim2.new(0.0137362638, 0, 0.0793652311, 0)
Frame_13.Size = UDim2.new(0, 356, 0, 63)

ImageLabel_13.Parent = Frame_13
ImageLabel_13.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_13.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_13.BorderSizePixel = 0
ImageLabel_13.Position = UDim2.new(0.0327201597, 0, 0.178197473, 0)
ImageLabel_13.Size = UDim2.new(0, 40, 0, 40)
ImageLabel_13.Image = "http://www.roblox.com/asset/?id=14966099367"

TextLabel_25.Parent = Frame_13
TextLabel_25.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_25.BackgroundTransparency = 1.000
TextLabel_25.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_25.BorderSizePixel = 0
TextLabel_25.Position = UDim2.new(0.179775283, 0, 0.253968269, 0)
TextLabel_25.Size = UDim2.new(0, 200, 0, 17)
TextLabel_25.Font = Enum.Font.ArialBold
TextLabel_25.Text = "The Strongest Battlegrounds"
TextLabel_25.TextColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_25.TextSize = 12.000
TextLabel_25.TextXAlignment = Enum.TextXAlignment.Left

TextLabel_26.Parent = Frame_13
TextLabel_26.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
TextLabel_26.BackgroundTransparency = 1.000
TextLabel_26.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextLabel_26.BorderSizePixel = 0
TextLabel_26.Position = UDim2.new(0.179775283, 0, 0.523809552, 0)
TextLabel_26.Size = UDim2.new(0, 200, 0, 12)
TextLabel_26.Font = Enum.Font.ArialBold
TextLabel_26.Text = "Last Update: 05/03/24"
TextLabel_26.TextColor3 = Color3.fromRGB(109, 109, 109)
TextLabel_26.TextSize = 9.000
TextLabel_26.TextXAlignment = Enum.TextXAlignment.Left

TextButton_13.Parent = Frame_13
TextButton_13.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
TextButton_13.BorderColor3 = Color3.fromRGB(0, 0, 0)
TextButton_13.BorderSizePixel = 0
TextButton_13.Position = UDim2.new(0.693636775, 0, 0.269841284, 0)
TextButton_13.Size = UDim2.new(0, 103, 0, 28)
TextButton_13.Font = Enum.Font.SourceSans
TextButton_13.Text = "Load"
TextButton_13.TextColor3 = Color3.fromRGB(255, 255, 255)
TextButton_13.TextSize = 14.000

UICorner_29.CornerRadius = UDim.new(0, 3)
UICorner_29.Parent = TextButton_13

UICorner_30.CornerRadius = UDim.new(0, 3)
UICorner_30.Parent = Frame_13

Tabs.Name = "Tabs"
Tabs.Parent = Background
Tabs.BackgroundColor3 = Color3.fromRGB(8, 8, 8)
Tabs.BorderColor3 = Color3.fromRGB(0, 0, 0)
Tabs.BorderSizePixel = 0
Tabs.Size = UDim2.new(0, 57, 0, 283)

UICorner_31.Parent = Tabs

Cover_2.Name = "Cover"
Cover_2.Parent = Tabs
Cover_2.BackgroundColor3 = Color3.fromRGB(8, 8, 8)
Cover_2.BorderColor3 = Color3.fromRGB(0, 0, 0)
Cover_2.BorderSizePixel = 0
Cover_2.Position = UDim2.new(0.789428711, 0, 0, 0)
Cover_2.Size = UDim2.new(0, 11, 0, 283)

ImageLabel_14.Parent = Tabs
ImageLabel_14.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
ImageLabel_14.BackgroundTransparency = 1.000
ImageLabel_14.BorderColor3 = Color3.fromRGB(0, 0, 0)
ImageLabel_14.BorderSizePixel = 0
ImageLabel_14.Position = UDim2.new(-0.216565579, 0, -0.0494699664, 0)
ImageLabel_14.Size = UDim2.new(0, 80, 0, 80)
ImageLabel_14.Image = "http://www.roblox.com/asset/?id=12124296333"

SuppGamesButton.Name = "SuppGamesButton"
SuppGamesButton.Parent = Tabs
SuppGamesButton.BackgroundColor3 = Color3.fromRGB(85, 170, 255)
SuppGamesButton.BackgroundTransparency = 1.000
SuppGamesButton.BorderColor3 = Color3.fromRGB(0, 0, 0)
SuppGamesButton.BorderSizePixel = 0
SuppGamesButton.Position = UDim2.new(0.157894731, 0, 0.190812722, 0)
SuppGamesButton.Size = UDim2.new(0, 35, 0, 35)
SuppGamesButton.Image = "http://www.roblox.com/asset/?id=14722728596"
SuppGamesButton.ImageColor3 = Color3.fromRGB(85, 170, 255)

Close.Name = "Close"
Close.Parent = Background
Close.Active = false
Close.BackgroundColor3 = Color3.fromRGB(255, 255, 255)
Close.BackgroundTransparency = 1.000
Close.Position = UDim2.new(0.912914932, 0, 0.0529724769, 0)
Close.Selectable = false
Close.Size = UDim2.new(0, 21, 0, 21)
Close.Image = "http://www.roblox.com/asset/?id=12707060750"

-- Scripts:

local function JFAH_fake_script() -- Background.drag 
	local script = Instance.new('LocalScript', Background)

	local UserInputService = game:GetService("UserInputService")
	local runService = (game:GetService("RunService"));
	
	local gui = script.Parent
	
	local dragging
	local dragInput
	local dragStart
	local startPos
	
	function Lerp(a, b, m)
		return a + (b - a) * m
	end;
	
	local lastMousePos
	local lastGoalPos
	local DRAG_SPEED = (8); -- // The speed of the UI darg.
	function Update(dt)
		if not (startPos) then return end;
		if not (dragging) and (lastGoalPos) then
			gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, lastGoalPos.X.Offset, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, lastGoalPos.Y.Offset, dt * DRAG_SPEED))
			return 
		end;
	
		local delta = (lastMousePos - UserInputService:GetMouseLocation())
		local xGoal = (startPos.X.Offset - delta.X);
		local yGoal = (startPos.Y.Offset - delta.Y);
		lastGoalPos = UDim2.new(startPos.X.Scale, xGoal, startPos.Y.Scale, yGoal)
		gui.Position = UDim2.new(startPos.X.Scale, Lerp(gui.Position.X.Offset, xGoal, dt * DRAG_SPEED), startPos.Y.Scale, Lerp(gui.Position.Y.Offset, yGoal, dt * DRAG_SPEED))
	end;
	
	gui.InputBegan:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseButton1 or input.UserInputType == Enum.UserInputType.Touch then
			dragging = true
			dragStart = input.Position
			startPos = gui.Position
			lastMousePos = UserInputService:GetMouseLocation()
	
			input.Changed:Connect(function()
				if input.UserInputState == Enum.UserInputState.End then
					dragging = false
				end
			end)
		end
	end)
	
	gui.InputChanged:Connect(function(input)
		if input.UserInputType == Enum.UserInputType.MouseMovement or input.UserInputType == Enum.UserInputType.Touch then
			dragInput = input
		end
	end)
	
	runService.Heartbeat:Connect(Update)
end
coroutine.wrap(JFAH_fake_script)()
local function XOYFSQT_fake_script() -- TextButton.LocalScript 
	local script = Instance.new('LocalScript', TextButton)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/ZombAttackMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(XOYFSQT_fake_script)()
local function CBJLEK_fake_script() -- TextButton_2.LocalScript 
	local script = Instance.new('LocalScript', TextButton_2)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/PrisonLife-Mobile/main/README.md'),true))()
		end)
end
coroutine.wrap(CBJLEK_fake_script)()
local function IUDBXL_fake_script() -- TextButton_3.LocalScript 
	local script = Instance.new('LocalScript', TextButton_3)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/LuckyBlocksMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(IUDBXL_fake_script)()
local function NCMM_fake_script() -- TextButton_4.LocalScript 
	local script = Instance.new('LocalScript', TextButton_4)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/TOHMOBILE/main/README.md'),true))()
		end)
end
coroutine.wrap(NCMM_fake_script)()
local function MFOSUBR_fake_script() -- TextButton_5.LocalScript 
	local script = Instance.new('LocalScript', TextButton_5)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/AllOfUsAreDeadMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(MFOSUBR_fake_script)()
local function XDPVBK_fake_script() -- TextButton_6.LocalScript 
	local script = Instance.new('LocalScript', TextButton_6)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/EverySecondYouGet1JumpPowerMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(XDPVBK_fake_script)()
local function PELHYNL_fake_script() -- TextButton_7.LocalScript 
	local script = Instance.new('LocalScript', TextButton_7)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/KATMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(PELHYNL_fake_script)()
local function URHE_fake_script() -- TextButton_8.LocalScript 
	local script = Instance.new('LocalScript', TextButton_8)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/ShadowBoxingMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(URHE_fake_script)()
local function CAWSG_fake_script() -- TextButton_9.LocalScript 
	local script = Instance.new('LocalScript', TextButton_9)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/DrivingEmpireMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(CAWSG_fake_script)()
local function NYKBH_fake_script() -- TextButton_10.LocalScript 
	local script = Instance.new('LocalScript', TextButton_10)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/BulkedUpMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(NYKBH_fake_script)()
local function IFFF_fake_script() -- TextButton_11.LocalScript 
	local script = Instance.new('LocalScript', TextButton_11)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/GreenVilleMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(IFFF_fake_script)()
local function TETMN_fake_script() -- TextButton_12.LocalScript 
	local script = Instance.new('LocalScript', TextButton_12)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/BladeBallMobile/main/README.md'),true))()
		end)
end
coroutine.wrap(TETMN_fake_script)()
local function TZATC_fake_script() -- TextButton_13.LocalScript 
	local script = Instance.new('LocalScript', TextButton_13)

	script.Parent.MouseButton1Down:connect(function()
		loadstring(game:HttpGet(('https://raw.githubusercontent.com/cool83birdcarfly02six/TheStrongestBattlegroundsPC/main/README.md'),true))()
		end)
end
coroutine.wrap(TZATC_fake_script)()
local function EFOUGGV_fake_script() -- Close.LocalScript 
	local script = Instance.new('LocalScript', Close)

	script.Parent.MouseButton1Down:connect(function()
	
		GAMEGUIGUI:Destroy()
	
		GAMEGUIGUI:deleteTimeout(2)
	
	end)
end
coroutine.wrap(EFOUGGV_fake_script)()
