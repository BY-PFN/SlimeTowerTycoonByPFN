repeat wait() until game:IsLoaded()
wait(5)
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)


if game.PlaceId == 10675066724 then -- Slime Tower Tycoon
local DiscordLib = loadstring(game:HttpGet("https://pastebin.com/raw/xcdmdnw0"))()
local win = DiscordLib:Window("Slime Tower Tycoon ByPFN [UPDATE 4]")

local serv = win:Server("ByPFN", "")
local tgls = serv:Channel("AutoFarm")
local tgls1 = serv:Channel("AutoBuy")
local HRP = game.Players.LocalPlayer.Character.HumanoidRootPart
local Plot = game:GetService("Workspace").Plots["1"]
local Plot = game:GetService("Workspace").Plots["2"]
local Plot = game:GetService("Workspace").Plots["3"]
local Plot = game:GetService("Workspace").Plots["4"]
local Plot = game:GetService("Workspace").Plots["5"]
local Plot = game:GetService("Workspace").Plots["6"]
local Plot = game:GetService("Workspace").Plots["7"]
local Plot = game:GetService("Workspace").Plots["8"]
local Ahn = game:GetService("Workspace").ObbyCheckpoints
local Uwu = game:GetService("Workspace").ObbyButton2


spawn(function()
while true do
game:GetService("VirtualInputManager"):SendKeyEvent(true,Enum.KeyCode.Quote,false,game)
game:GetService("VirtualInputManager"):SendKeyEvent(false,Enum.KeyCode.Quote,false,game)
wait(10)
end
end)



-----------------------------------------------------------------------------------------
_G.weapon = false
tgls:Toggle("Auto Collect",false, function(bool)
    _G.weapon = bool
end)

spawn(function()
    while wait(1) do
      if _G.weapon then
        pcall(function() 
            

for i,v in pairs(game:GetService("Workspace").Drops:GetDescendants()) do
            if v.Name == "Dropper_Drop" then
                v.CFrame = HRP.CFrame
            end
        end
            wait(5)
        end)
      end
    end
end)


-----------------
_G.weapon1 = false
tgls:Toggle("Auto Deposit",false, function(bool)
    _G.weapon1 = bool
end)

spawn(function()
    while wait(1) do
      if _G.weapon1 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.DepositButton.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(5)
        end)
      end
    end
end)

-----------------
_G.weapon2 = false
tgls:Toggle("UpAutoSellSpeed",false, function(bool)
    _G.weapon2 = bool
end)

spawn(function()
    while wait(1) do
      if _G.weapon2 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.BuySpeed.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(5)
        end)
      end
    end
end)

-----------------
_G.weapon3 = false
tgls:Toggle("Auto Merge",false, function(bool)
    _G.weapon3 = bool
end)

spawn(function()
    while wait(1) do
      if _G.weapon3 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.MergeButton.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(5)
        end)
      end
    end
end)

-----------------
_G.weapon4 = false
tgls:Toggle("Auto Obby",false, function(bool)
    _G.weapon4 = bool
end)

spawn(function()
    while wait(1) do
      if _G.weapon4 then
       firetouchinterest(HRP, Ahn.ObbyCheckpoint1, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint1, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint2, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint2, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint3, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint3, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint4, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint4, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint5, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint5, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint6, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint6, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint7, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint7, 1)
wait(0.75)
firetouchinterest(HRP, Ahn.ObbyCheckpoint8, 0)
firetouchinterest(HRP, Ahn.ObbyCheckpoint8, 1)
wait(0.75)
firetouchinterest(HRP, Uwu.Button, 0)
firetouchinterest(HRP, Uwu.Button, 1)
end
end
end)
-----------------------------------------------------------------------------------------
---2---
-----------------------------------------------------------------------------------------
_G.BuyDropper = false
tgls1:Toggle("Auto Slime +1",false, function(bool)
    _G.BuyDropper = bool
end)

spawn(function()
    while wait(1) do
      if _G.BuyDropper then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.BuyDropper.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(1)
        end)
      end
    end
end)

-----------------
_G.BuyDropper5 = false
tgls1:Toggle("Auto Slime +5",false, function(bool)
    _G.BuyDropper5 = bool
end)

spawn(function()
    while wait(1) do
      if _G.BuyDropper5 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.BuyDropper5.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(1)
        end)
      end
    end
end)

-----------------
_G.BuyDropper25 = false
tgls1:Toggle("Auto Slime +25",false, function(bool)
    _G.BuyDropper25 = bool
end)

spawn(function()
    while wait(1) do
      if _G.BuyDropper25 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.BuyDropper25.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(1)
        end)
      end
    end
end)

-----------------
_G.BuyDropper50 = false
tgls1:Toggle("Auto Slime +50",false, function(bool)
    _G.BuyDropper50 = bool
end)

spawn(function()
    while wait(1) do
      if _G.BuyDropper50 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.BuyDropper50.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(1)
        end)
      end
    end
end)

-----------------
_G.BuyDropper100 = false
tgls1:Toggle("Auto Slime +100",false, function(bool)
    _G.BuyDropper100 = bool
end)

spawn(function()
    while wait(1) do
      if _G.BuyDropper100 then
        pcall(function() 
            

for i,v in pairs(Plot.Buttons.BuyDropper100.Button:GetChildren()) do
            if v:IsA("TouchTransmitter") then
                firetouchinterest(HRP, v.Parent, 0)
                firetouchinterest(HRP, v.Parent, 1)
            end
        end
            wait(1)
        end)
      end
    end
end)
-----------------------------------------------------------------------------------------

local Slider = Section:CreateSlider('Walkspeed', 16, 200, 16, Color3.fromRGB(155, 255, 130), function(Value)
    game.Players.LocalPlayer.Character.Humanoid.WalkSpeed = Value
end)

end
