## usage of _G.
```lua
_G.c = true;

while _G.c = true do -- you can use this to loop an function (you can stop it by changing _G.c to false!
  print("true")
  wait()
end
if _G.c == false then -- if _G.c = false it will print false
  print("false")
end
```