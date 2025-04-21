# Lume Library v1 2025

Loadstring
```lua
local library = loadstring(game:HttpGet("https://raw.githubusercontent.com/memejames/elerium-v2-ui-library//main/Library", true))()
```

Create Window Here:
```lua
local window = library:AddWindow("Name GUI", {
	main_color = Color3.fromRGB(41, 74, 122), -- Color
	min_size = Vector2.new(250, 346), -- Size of the gui
	can_resize = false, -- true or false
})
```
AddLabel:
```lua
features:AddLabel("Hello World!")
```

AddTab:
```lua
local features = window:AddTab("Features") -- Name of tab
features:Show() -- shows the tab
```
AddButton:
```lua
features:AddButton("name",function()
	-- Code here
end)
```
AddToggle:
```lua
local switch = features:AddSwitch("name", function(bool)
	 -- toggle_god_mode(bool)
end)
switch:Set(true)
```
