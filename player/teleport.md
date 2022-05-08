## Teleporting to parts
```lua
function teleportTO(placeCFrame)
    local plyr = game.Players.LocalPlayer;
    if plyr.Character then
        plyr.Character.HumanoidRootPart.CFrame = placeCFrame;
    end
end
teleportTO(pathhere) -- example: teleportTO(game.Workspace.Part)
```
## Teleport to a player or to a cframe
```lua
--// tping to player
local player = "player name here"
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = game.Players[player].Character.HumanoidRootPart.CFrame * CFrame.new(0,0,1)
--// tping to a cframe
game.Players.LocalPlayer.Character.HumanoidRootPart.CFrame = CFrame.new() -- put a cframe in ()
```
