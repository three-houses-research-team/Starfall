## Forge

Version: 0.0.1

Forge is a file redirection layer for Fire Emblem Three Houses. When looking for any file, the game will look in Forge's files first. If it is missing, then the original game file will be used.

## How to Install
Download Forge from [the releases page](https://github.com/three-houses-research-team/Starfall/releases).
Place the contents of `sdcard` into the root of your SD card.

## How to Use
Place your files in `sdcard:/Starfall/forge/`. The names of these files must be four characters long, being the name of the entry ID in lowercase hex.

Examples:

* EntryID `0`: `sdcard:/Starfall/forge/0000`
* EntryID `11`: `sdcard:/Starfall/forge/000b`
* EntryID `481`: `sdcard:/Starfall/forge/01e1`

## Troubleshooting
Make sure that the patch has been applied. You can do by confirming the Starfall version number on the title screen:

![Title screen](titlescreen.jpg)

Furthermore, make sure that your patch files have the correct naming scheme.

## Disclaimer

Forge is created by KolakCC and Raytwo using [Starlight](https://github.com/shadowninja108/Starlight).
We take no responsibility for lost save progress, bricked switches, or anything else.