# Iris UI Bundle
Created by [SirMallard](https://github.com/SirMallard) *(known as Michael48)*;
Bundled by [x0581](https://github.com/x0581) *(known as [littlemike57](https://v3rmillion.net/member.php?action=profile&uid=3099053))*;
Created a new version for the latest version of Iris *(Iris v2.4.1)* by [me](https://github.com/ACEtheSOLID);

## Example Usage
```lua
local Players = game:GetService("Players")
local LocalPlayer = Players.LocalPlayer
local Iris = loadstring(game:HttpGet("https://raw.githubusercontent.com/ACEtheSOLID/Roblox-UI-Libs/main/Iris%20%5BIMGUI%5D/Source-v2.4.1"))()

Iris.Init(LocalPlayer.PlayerGui)
Iris:Connect(Iris.ShowDemoWindow)
```
