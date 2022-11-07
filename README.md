repeat wait() until game:IsLoaded()
wait(10)
local vu = game:GetService("VirtualUser")
game:GetService("Players").LocalPlayer.Idled:connect(function()
   vu:Button2Down(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
   wait(1)
   vu:Button2Up(Vector2.new(0,0),workspace.CurrentCamera.CFrame)
end)
if game.PlaceId == 10723695195 then -- Anime Evolution Simulator
 

local DiscordLib = loadstring(game:HttpGet("https://pastebin.com/raw/xcdmdnw0"))()
local win = DiscordLib:Window("Anime Evolution Simulator")

local serv = win:Server("ByPFN", "")



local tgls = serv:Channel("AutoFarm")
local tgls1 = serv:Channel("Egg")
local tgls2 = serv:Channel("TP")

---------------------------------------------------------------------------

_G.Click = true
_G.PowerTrain = false
_G.RankUp = false

----------------------------------------------------------------------------


tgls:Toggle("Click",true, function(bool)
    _G.Click = bool
end)

tgls:Toggle("PowerTrain",false, function(bool)
    _G.PowerTrain = bool
end)

tgls:Toggle("RankUp",false, function(bool)
    _G.RankUp = bool
end)

----------------------------------------------------------------------------

local ViSendMouseButtonEvent = game:service'VirtualInputManager'

spawn(function()
    while wait() do
      if _G.Click then
        pcall(function()
            ViSendMouseButtonEvent:SendMouseButtonEvent(795, 595, 0, true, game, 1)
wait(.5)
ViSendMouseButtonEvent:SendMouseButtonEvent(795, 595, 0, false, game, 1)    
            
        end)
      end
    end
end)
-----------------------------------------------------------------------------


spawn(function()
    while wait(0.1) do
      if _G.PowerTrain then
        pcall(function() 
            


local args = {
    [1] = {
        [1] = "PowerTrain"
    }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))


 
            wait()
            
            
        end)
      end
    end
end)

spawn(function()
    while wait(0.1) do
      if _G.RankUp then
        pcall(function() 
            



local args = {
    [1] = {
        [1] = "RankUp"
    }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))



 
            wait()
            
            
        end)
      end
    end
end)
-------------------------------------------------------------------------------------------------------------------

_G.EggHXH = false
tgls1:Toggle("EggHXH",false, function(bool)
    _G.EggHXH = bool
end)
spawn(function()
    while wait(0.1) do
      if _G.EggHXH then
        pcall(function() 
            


local args = {
    [1] = {
        [1] = "BuyTier",
        [2] = workspace.__WORKSPACE.FightersPoint.Hunters,
        [3] = "E",
        [4] = {}
    }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))

 
            wait()
            
            
        end)
      end
    end
end)

_G.MyHero = false
tgls1:Toggle("MyHero",false, function(bool)
    _G.MyHero = bool
end)
spawn(function()
    while wait(0.1) do
      if _G.MyHero then
        pcall(function() 
            




local args = {
    [1] = {
        [1] = "BuyTier",
        [2] = workspace.__WORKSPACE.FightersPoint:FindFirstChild("My Hero"),
        [3] = "E",
        [4] = {}
    }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))


            
            
        end)
      end
    end
end)

-------------------------------------------------------------------------------------------------------------------


tgls2:Button("วันพีช ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0.19173415005207062, 3.051313638687134, -62.48855209350586)    
        
    
end)

tgls2:Button("นารูโตะ ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8.242718696594238, 3.0192301273345947, 219.44590759277344)    
        
    
end)

tgls2:Button("ดราก้อนบอล ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6.520077705383301, 3.0192301273345947, 478.4737854003906)    
        
    
end)

tgls2:Button("ไททั้น ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3.2818922996520996, 3.0192301273345947, 772.1893920898438)    
        
    
end)

tgls2:Button("ดาบพิฆาตอสูร ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0.634533166885376, 3.0192301273345947, 1069.7413330078125)    
        
    
end)

tgls2:Button("วันพันช์แมน ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8.284528732299805, 3.019230365753174, 1366.1849365234375)    
        
    
end)

tgls2:Button("ฮันเตอร์ × ฮันเตอร์ ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2.3151111602783203, 2.4882943630218506, 1967.6131591796875)    
        
    
end)


end
