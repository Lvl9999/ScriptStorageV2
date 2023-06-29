# Infinite Script Storage V2
A script that allows you to store your own custom scripts and any other!

[+] Toggle Keybind
```lua
getgenv().ToggleVisibility = "V"
```
[+] Custom Command [Open]
```lua
getgenv().ChatToOpen = "open" 
```
[+] Custom Command [Close]
```lua
getgenv().ChatToClose = "close"
```
[+] Button Creation Function
```lua
getgenv().CreateButton('Test 1', function();
    print("Test 1 clicked");
end)
```
[+] Example
```lua
--[[ Made by ThroughTheFireAndFlames#9925 | 

        [Infinite Script Storage V2]

--]]--------------------------------------

getgenv().ToggleVisibility = "V" -- Change if you want
getgenv().ChatToOpen = "open" -- Chat in roblox "open" to show GUI
getgenv().ChatToClose = "close" -- Chat in roblox "close" to hide GUI

------------------------[[MainScript]]----------------------------------------------------------------
loadstring(game:HttpGet("https://raw.githubusercontent.com/Lvl9999/ScriptStorageV2/main/Universal"))(); 
------------------------------------------------------------------------------------------------------

getgenv().LoaderX(); -- [Main Loader]

-------[[Create Buttons]]-----------------
getgenv().CreateButton('Test 1', function()
    print("Test 1 clicked");
end)

getgenv().CreateButton('Test 2', function()
    print("Test 2 clicked");
end)

getgenv().CreateButton('Test 3', function()
    print("Test 3 clicked");
end)

getgenv().CreateButton('Test 4', function()
    print("Test 4 clicked");
end)

getgenv().CreateButton('Test 5', function()
    print("Test 5 clicked");
end)
```

# Showcase:

![image (4)](https://github.com/Lvl9999/ScriptStorageV2/assets/123672448/1e1b1e08-d5cf-4975-abcd-602ba9aa239c)

