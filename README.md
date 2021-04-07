# CrudeDevour
Due to the lack of xdotool, I made a crude devour script for sway. Please note the name, These scrips are crude, they are hacks, not well crafted works of art.

## Versions
### Without title bar
This script set the `layout` to `stacking` for the terminal window in which the GUI application is launched and switches it back when the program finishes. This script is designed for the following settings:
```
default_border pixel
titlebar_padding 1
font monospace 0
```

### With title bar
If you do have title bars, the stacking layout will not look as if the GUI application takes the place of the terminal, so I have a different script.
This script moves the terminal to the scratchpad and back when the GUI program exits.

## Usage
Download either version of the script and prepend `devour` in front of any GUI command like so: `devour mpv test,.mp4`.
Alternatively you can make an alias in your shell's rc file.
