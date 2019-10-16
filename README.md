# osu-linux-wacom
Wacom area setting utility for osu. 

This little script calculates and sets tablet's area for Wacom tablets automatically, given four parameters.

It disables any smoothing by default.

# requirements
Make sure to install `xf86-input-wacom` and `xorg-xrandr` before running the script

Arch Linux:
`sudo pacman -S xf86-input-wacom xorg-xrandr`

# parameters
- Area percentage: from 0 to 100 (accepts floats)
- Left-handed mode (tablet rotated 180 degrees): y / n
- Area's placement on the X axis: from 0 to 100 (accepts floats)
- Area's placement on the Y axis: from 0 to 100 (accepts floats)

# how to execute the script
Clone the script into your home directory:

`git clone https://github.com/smokepenguin/osu-linux-wacom`

Finally, run the script using: 

`cd ./osu-linux-wacom`

`python wacom.py`
