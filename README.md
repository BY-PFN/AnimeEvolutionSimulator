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
local tgls3 = serv:Channel("TP Event Power")
---------------------------------------------------------------------------

_G.Click = true
_G.PowerTrain = true
_G.MAGNET = true
_G.RankUp = true
_G.Weapon = true
_G.Sung = true
_G.X25POWER = true
----------------------------------------------------------------------------


tgls:Toggle("Click",true, function(bool)
    _G.Click = bool
end)

tgls:Toggle("PowerTrain",true, function(bool)
    _G.PowerTrain = bool
end)
tgls:Toggle("MAGNET",true, function(bool)
  _G.MAGNET = bool
end)
tgls:Toggle("RankUp",true, function(bool)
    _G.RankUp = bool
end)
tgls:Toggle("Weapon",true, function(bool)
    _G.Weapon = bool
end)
tgls:Toggle("Sung",true, function(bool)
  _G.Sung = bool
end)
tgls:Toggle("X25POWER",true, function(bool)
  _G.X25POWER = bool
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
    while wait() do
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
-------
spawn(function()
  while wait(0.1) do
    if _G.MAGNET then
      pcall(function() 
          


        local Coin = game.Players.localPlayer.Character.HumanoidRootPart
        for i,v in pairs(game.Workspace.__DROPS:GetChildren()) do
            v.CFrame = Coin.CFrame
            wait()
            end
            
        
        
          
          
      end)
    end
  end
end)

------

spawn(function()
    while wait(14.1) do
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


spawn(function()
    while wait(10.1) do
      if _G.Weapon then
        pcall(function() 
            


local args = {
    [1] = {
        [1] = "Weapon"
    }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))



 
            wait()
            
            
        end)
      end
    end
end)



spawn(function()
  while wait() do
    if _G.Sung then
      pcall(function() 
          
     


local args = {
    [1] = {
        [1] = "AttackMob",
        [2] = workspace.__WORKSPACE.Mobs:FindFirstChild("Level Solo").Sung,
        [3] = "Right Arm"
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

_G.Ragnarok = false
tgls1:Toggle("Ragnarok",false, function(bool)
    _G.Ragnarok = bool
end)
spawn(function()
    while wait(0.1) do
      if _G.Ragnarok then
        pcall(function() 
            


local args = {
  [1] = {
      [1] = "BuyTier",
      [2] = workspace.__WORKSPACE.FightersPoint.Ragnarok,
      [3] = "E",
      [4] = {}
  }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))

         
            
        end)
      end
    end
end)

_G.Ragnarok1 = false
tgls1:Toggle("Ragnarok5ดาว",false, function(bool)
    _G.Ragnarok1 = bool
end)
spawn(function()
    while wait(0.1) do
      if _G.Ragnarok1 then
        pcall(function() 
            

local args = {
  [1] = {
      [1] = "BuyTier",
      [2] = workspace.__WORKSPACE.FightersPoint.Ragnarok,
      [3] = "E",
      [4] = {
          ["Poseidon"] = true,
          ["Sasaki"] = true,
          ["Hercules"] = true
      }
  }
}

game:GetService("ReplicatedStorage").Remotes.Client:FireServer(unpack(args))


         
            
        end)
      end
    end
end)
-------------------------------------------------------------------------------------------------------------------


tgls2:Button("Ooy Piece  วันพีช ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0.19173415005207062, 3.051313638687134, -62.48855209350586)    
        
    
end)

tgls2:Button("Narutye นารูโตะ ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8.242718696594238, 3.0192301273345947, 219.44590759277344)    
        
    
end)

tgls2:Button("Draygon Bool ดราก้อนบอล ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(6.520077705383301, 3.0192301273345947, 478.4737854003906)    
        
    
end)

tgls2:Button("Attack On ไททั้น ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(3.2818922996520996, 3.0192301273345947, 772.1893920898438)    
        
    
end)

tgls2:Button("Slayer Demons ดาบพิฆาตอสูร ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(0.634533166885376, 3.0192301273345947, 1069.7413330078125)    
        
    
end)

tgls2:Button("One Punchy วันพันช์แมน ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(8.284528732299805, 3.019230365753174, 1366.1849365234375)    
        
    
end)

tgls2:Button("ฮันเตอร์ × ฮันเตอร์ ", function()
    
    game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2.3151111602783203, 2.4882943630218506, 1967.6131591796875)    
        
    
end)

tgls2:Button("มายฮีโร่ ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(20.738351821899414, 3.5420360565185547, 2393.4365234375)    
      
  
end)

tgls2:Button("โลก2 ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(16.755592346191406, 2.6749017238616943, 2645.599609375)    
      
  
end)

tgls2:Button("มหาเวทย์ผนึกมาร ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(401.6087341308594, 2.921861171722412, 2608.64208984375)    
      
  
end)

tgls2:Button("สลาม ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(432.03887939453125, 2.800079584121704, 2314.130859375)    
      
  
end)

tgls2:Button("คนชมเทพ ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(423.1486511230469, 2.857194662094116, 1990.1640625)    
      
  
end)

tgls2:Button("Tokyio Revengers ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(484.01043701171875, 2.802030086517334, 1704.9384765625)    
      
  
end)

tgls2:Button("Clover Church ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1090.91943359375, 2.559436321258545, 1562.9537353515625)    
      
  
end)

tgls2:Button("Back Clover ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(641.842041015625, 2.8020291328430176, 1537.6514892578125)    
      
  
end)

tgls2:Button("Defense2 ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1440.3270263671875, 15.58559513092041, 1094.453857421875)    
      
  
end)

tgls2:Button("Training Area ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(41921.2825927734375, 2.513629198074341, 1437.83349609375)    
      
  
end)

tgls2:Button("Sword Art ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1921.2825927734375, 2.513629198074341, 1437.83349609375)    
      
  
end)

tgls2:Button("Blechi ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2266.163818359375, 2.754854440689087, 2299.5234375)    
      
  
end)

tgls2:Button("Joujo Adventures ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(2266.163818359375, 2.754854440689087, 2299.5234375)    
      
  
end)

tgls2:Button("Mob Pchaicho ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1377.579345703125, 4.441339492797852, 2822.348388671875)    
      
  
end)

tgls2:Button("TGOH ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1106.9857177734375, 5.44486141204834, 2980.19189453125)    
      
  
end)


-------------------------------------------------------------------------------------------------------------------------------------

tgls3:Button("X16 POWER AREA ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(1641.04345703125, 4.441815376281738, 2577.443115234375)    
      
  
end)

spawn(function()
    while wait(10) do
      if _G.X25POWER then
        pcall(function() 
            

game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(414.8289794921875, 4.123180389404297, 4732.04541015625)
if (CFrame.new(414.8289794921875, 4.123180389404297, 4732.04541015625).Position - game.Players.LocalPlayer.Character.HumanoidRootPart.Position) >= 5 then
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(414.8289794921875, 4.123180389404297, 4732.04541015625)
end

 
            wait(10)
            
            
        end)
      end
    end
end)

tgls3:Button("X25 POWER AREA ", function()
    
  game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new(414.8289794921875, 4.123180389404297, 4732.04541015625)    
      
  
end)

end
