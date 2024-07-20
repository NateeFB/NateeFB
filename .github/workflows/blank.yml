loadstring(game:HttpGet('https://raw.githubusercontent.com/XorV2/script/main/Unfair'))()
Infinite Honey Script:
loadstring(game:HttpGet("https://raw.githubusercontent.com/Boxking776/GrubHubNonPremium/main/GrubGubMain.lua"))()
Auto Kill Script:
loadstring(game:HttpGet("https://raw.githubusercontent.com/YtBatuhanG/roblox/main/BatuhanGHub"))()
Auto Jelly Spinner Script:
getgenv().Enabled = false;
getgenv().TargetBees = {'TadpoleBee', 'BuoyantBee'}
getgenv().X = 4 -- right/left
getgenv().Y = 2 -- up/down
local Client = game.Players.LocalPlayer;
local HoneyComb = Client.Honeycomb;
--
local main = {}; do
main.beeCheck = function()
if table.find(TargetBees, HoneyComb.Value.Cells['C' .. X .. "," .. Y].CellType.Value) then
return HoneyComb.Value.Cells['C' .. X .. "," .. Y].CellType.Value
else
return nil
end
end
main.spinRoyalJelly = function()
game.ReplicatedStorage.Events.ConstructHiveCellFromEgg:InvokeServer(X, Y, 'RoyalJelly', 1)
end
end
if not main.beeCheck() and getgenv().Enabled then
repeat main.spinRoyalJelly()
until main.beeCheck() or not getgenv().Enabled
end
