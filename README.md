# My i3 config

Just a few changes to personalize i3 for me.

## Pre-requirements:
- Font: Monofur Nerd Font
- `maim` for screenshots
- `xclip` for copying screenshots to clipboard
- `i3-wm`, `i3status`, `picom`, and `dunst` for all the UI stuff

## Installation
- Copy `i3`, `i3status`, and `picom` folders to `~/.config`
- Copy `.fehbg-hecatia` to your home folder (`~/`) and edit it to point to the correct wallpaper file location. Alternatively, just edit i3's config to use `~/.fehbg` and let feh generate its own file. 

## Changes:
- Caps Lock presses ESC
- Runs `feh` for the wallpaper
- Colors changed that matches included wallpaper
- Super+Q to kill programs
- Super+Shift+Q to quit i3 and removed the exit prompt
- Super+Tab to swap to last focused workspace
- Screenshot utils (PrtSc to copy to clipboard, Shift+PrtSc to save to `~/Pictures/`
