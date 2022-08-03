# Translation Notes
This repo is an English language fork of [vscode-quickxdev](https://github.com/leitwolf/vscode-QuickXDev). Currently all translations are machine translated via [DeepL](https://www.deepl.com). Any code/functionality issues should be directed to the original repo. Feel free to submit pull requests for improved translations.

The following is a machine translation of the original README.md.

# QuickXDev for vscode
Powerful quick-cocos2dx development tools, currently adapted to Quick-Cocos2dx-Community version 3.7.x and partially adapted to Cocos2d-Lua-Community version 4.0.

QuickXDev exchange group: 625657444, welcome to ask questions and discuss problems.

## Cocos2d-Lua-Community 4.0 Release Notes
- It is now partially adapted to this version, where LuaGameRunner (Player in the old version) is available. The usage of this feature is the same as in previous versions, right click -> Run in Player, the plugin will determine which version it is based on the directory structure of the engine.
- Because this version no longer has environment variables, it is not possible to get the root directory of the engine from the system, so to use version 4.0, the user must actively set the plugin quickxdev.root, which is the root directory of the engine.
- If you want to develop both 3.7.x and 4.0 version projects, set quickxdev.root in the working directory of the project, so that the settings of different projects are separated and do not affect each other.

## Installation
Search for "QuickXDev" in the vscode extension store to find it.

## Features
- Code hints for cocos2dx c++ side
- Code hints on the quick lua side
- lua 5.1 system code hints
- if, while, function, etc. fragments
- Go to Define Features
- Run functions in Player (F6)

## Configuration
- quickxdev.root quick engine directory, if it is a normal installation of quick (execution of setup_win.bat/setup_mac.sh), the plug-in automatically get this variable. If it is 4.0 version then you need to set it manually.

## Open Player
Right click on any lua file in the project -> Run in Player, or press F6 to run the project.

## Third Party Library
This plugin uses [luaparse](https://github.com/oxyc/luaparse) as the lua code parsing library, and I'd like to thank the original author!

## A few functional gifs
- Automatic completion
![completion](https://user-images.githubusercontent.com/1720546/44968155-c290b580-af78-11e8-8d58-4e5d43a31cd7.gif)
- Go to Definition
![godef](https://user-images.githubusercontent.com/1720546/44968156-c58ba600-af78-11e8-8a98-3f73c5a51b34.gif)
- Run Player
![runplayer](https://user-images.githubusercontent.com/1720546/44968157-c6243c80-af78-11e8-8490-920d2db74789.gif)
