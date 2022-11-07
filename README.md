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

---------------------------------------------------------------------------

_G.Click = true

----------------------------------------------------------------------------


tgls:Toggle("auto click",true, function(bool)
    _G.Click = bool
end)


----------------------------------------------------------------------------
local ViSendMouseButtonEvent = game:service'VirtualInputManager'

spawn(function()
    while wait() do
      if _G.Click then
        pcall(function()
            ViSendMouseButtonEvent:SendMouseButtonEvent(795, 595, 0, true, game, 1)
wait(.2)
ViSendMouseButtonEvent:SendMouseButtonEvent(795, 595, 0, false, game, 1)    
            
        end)
      end
    end
end)
-----------------------------------------------------------------------------

    
end
