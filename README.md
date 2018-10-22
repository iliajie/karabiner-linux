## About
If you are going to actively work in GNOME on Linux and Aqua on macOS at the same time, you will be completely paralyzed by the significant differences in the ways shortcut keys are utilized.

I post here, my way of making keybindings of Aqua on macOS to work pretty close alike as in GNOME on Linux.

## Requirements
Installed copy of [Karabiner-Elements](https://github.com/tekezo/Karabiner-Elements) by [Takayama Fumihiko](https://github.com/tekezo) on your Mac. It can be downloaded from [official website](https://pqrs.org/osx/karabiner).

Please support the developer by sending [donation](https://pqrs.org/osx/karabiner/pricing.html).

## Installation
All you need is just to copy _karabiner.json_ file from this repo to _/Users/username/.config/karabiner_ directory on your Mac, and running Karabiner-Elements will automatically apply the modifications.

## Rules
* Swap control keys
* Common for copy (Ctrl+C), paste (Ctrl+V) and cut (Ctrl+X)
* Common Terminal sigterm (Ctrl+C) and search (Ctrl+R)
* Common browser open location (Alt+D)
* Common for closing application (Alt+F4)
* Common keys for switching applications (Option+Tab)
* Common keys for switching applications (Command+Tab)
* Common keys for switching tabs in applications (Ctrl+Tab)
* Additional keys for moving focus to next window in application (Option+`)
* Additional keys for moving focus to next window in application (Command+`)
* Additional keys for quick switching to tabs (Alt+1..9)

## License
Released under the [MIT License](https://github.com/rostovtsev/karabiner-linux/blob/master/LICENSE).
