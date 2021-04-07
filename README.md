# CrudeDevour
Due to the lack of xdotool, I made a crude devour script for sway.

## Without title bar
This script set the `layout` to `stacking` for the terminal window in which the gui aplication is launched and switches it back when the program finishes. Wokrs well with the following settings:
```
default_border pixel 2
titlebar_padding 1
font monospace 0
```

## With title bar
If you do have title bars, the stacking layout will not look as if the gui aplication takes the place of the terminal, so I have a different script.
This script moves the terminal to the scratchpad and back when the gui program exits.
