# Keyboard Maestro Macros
Keyboard Maestro is an automation tool for Mac.
https://www.keyboardmaestro.com/

This repository includes some useful macros for productivity.

Some of these emit key combos that trigger actions in other apps, e.g.
Rectangle, a window manager for Mac.
https://rectangleapp.com/

_NOTE:_ As of 2024-11-14, my keyboard is a Royal Kludge RKS70, which has dedicated
macro keys that emit common Windows key combinations, like CTRL-C, CTRL-V, etc.

Since I'm a) on a Mac and b) want to use more interesting macros on those keys,
I've got Keyboard Macro set up to intercept those key combinations.

## RKS70 M2 rectangle left/top
[RKS70_M2_rectangle_left-top.kmmacros](RKS70_M2_rectangle_left-top.kmmacros)
Checks the orientation of the front screen (containing most of the active window)
Simulates the Rectangle key combo for left (if horizontal) or top (if vertical)
Useful in a setup both vertical and horizontal monitors, so you can use the same
key combos for dividing up the screen in either orientation.

## RKS70 M3 rectangle right/bottom
[RKS70_M3_rectangle_right-bottom.kmmacros](RKS70_M3_rectangle_right-bottom.kmmacros)
Similar to the left/top version above, but moves the active window to the right half
or bottom half of the screen.
