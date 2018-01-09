XrandrForThinkpad

Wanted to scale my laptop screen quickly to fit more stuff. Using xrandr without --panning limits cursor movement to original resolution.
This script automates calculating the values for --panning.
Usage: ./xft $1
$1 is scaling factor. Higher than 2 is probably a bad idea.

Todo: 
-Change to grab current values vs hardcoded
-Sanity check
-GUI?
