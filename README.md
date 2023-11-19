# Garry-UI


```lua
local ui=loadstring(game:HttpGet('https://raw.githubusercontent.com/3345-c-a-t-s-u-s/Garry-UI/main/source'))()
if not game:IsLoaded() then
	game.Loaded:Wait()
end
task.wait(3)
ui:MakeLoad("LOAD","ADADADADAD")
getfenv().MyUI = ui:Create("BEDOL HUB","SERVER")

local d= MyUI:CreateTab("Example",'earth')
d:CreateLabel("TITLE")
d:CreateButton("BUTTON",function()
	print('ccccc')
end)
d:CreateToggle("TOGGLE",false,function()
	
end)

d:CreateKeybind("KEYBINDS",nil,function()
	
end)

d:CreateSlider("SLIDER",1,10,5,function()
	
end)

MyUI:CreateTab("Example2",'list')
```
