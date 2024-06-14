# Booting the Library
```lua
local SolarLibrary = loadstring(game:HttpGet(('https://raw.githubusercontent.com/Riv3rZZ/SolarLibrary/main/source')))()
```
# Creating a Window
```lua
SolarLibrary:NewWindow(true, "Skibidi", 1, false, "Hi")
--[[
Name = <String> - Name of the UI
Wait Till Open = <Number> - Time it takes till it opens
KeySystem = <bool> - Whether if you want it to make the Keysystem on
Key = <String> - it can be a a link or a text, its the key for the keysystem.
]]
```
# Creating a New tab
```lua
local Tab = SolarLibrary:NewTab(true,"NewTab", "rbxassetid://6821165844")
--[[
Name = <String> - The Name of the tab
TabImage = <String> - You can set it to nothing and it will be the standard tab image or you can set it yourself, it needs to be a roblox assetid like this: (rbxassetid://11001100)
]]
```
# Creating a New button
```lua
SolarLibrary::NewElement("Button","Button",Tab,print('Hi'))

--[[ 
ElementName = <String> - The Element Name
ElementType = <String> - The Element Type (This will be used later in the documentation)
ElementParent = <Tab> - The Elements Parent (IT NEEDS TO BE A TAB !1!1!1!1)
Script = <LocalScript> - a code that will fire once u click the button
]]
```

# Creating a New toggle
```lua
local toggle = SolarLibrary:NewToggle("Toggle", Tab, function(newValue)
	if newValue then
		print("Hi")
	else
		print("Bye")
	end
end)

--[[
ToggleName = <String> - The Toggle Name
ToggleParent = <Tab> - The Toggle Parent
newValue = <Bool> - When the value is changed (it needs to be put in a function>
]]
```


