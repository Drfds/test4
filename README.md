local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()
local Window = Library.CreateLib("Dark Hub", "DarkTheme")
local Tab = Window:NewTab("Tween")
local Section = Tab:NewSection("Warp")
Section:NewButton("Spawn", "", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(68.6557846069336, 176.98095703125, 236.40591430664062)}):Play()
end)

Section:NewButton("7-11", "", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-20.852022171020508, 177.19801330566406, 204.5872802734375)}):Play()
end)

Section:NewButton("Animation", "", function()
    local TweenService = game:GetService("TweenService")

local Tw = TweenService:Create(game.Players.LocalPlayer.Character.HumanoidRootPart, TweenInfo.new(2, Enum.EasingStyle.Linear, Enum.EasingDirection.Out,0,false,0),
{CFrame = CFrame.new(-63.20124053955078, 177.19801330566406, 202.10574340820312)}):Play()
end)
