## using table.find()
```lua
local player = game.Players.LocalPlayer -- player
local table1 = {"player username"} -- table
if table.find(table1,player.Name) then -- if it finds  an player username in the table then it will print hi
    print("Hi")
end
```