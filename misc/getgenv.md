## usage of getgenv
```lua
getgenv().c = true;

while getgenv().c == true do -- you can use this to loop an function (you can stop it by changing getgenv().c to false!
  print("true")
  wait()
end
if getgenv().c == false then -- if getgenv().c = false it will print false
  print("false")
end
```