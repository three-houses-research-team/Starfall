## Forge

Version: 0.0.4

Forge is a file redirection layer for Fire Emblem Three Houses. When looking for any file, the game will look in Forge's files first. If it is missing, then the original game file will be used.

## How to Install
Download Forge from [the releases page](https://github.com/three-houses-research-team/Starfall/releases).
Place the contents of `sdcard` into the root of your SD card.

## How to Use
Place your files in `sdcard:/Starfall/forge/`. The names of these files must be the name of the entry ID in decimal.

Examples:

* EntryID `0`: `sdcard:/Starfall/forge/0`
* EntryID `11`: `sdcard:/Starfall/forge/11`
* EntryID `3121`: `sdcard:/Starfall/forge/3121`

## Troubleshooting
Make sure that the patch has been applied. You can do by confirming the Starfall version number on the title screen:

![Title screen](titlescreen.jpg)

Furthermore, make sure that your patch files have the correct naming scheme.

## Version History
* **0.0.4** Resolve crashes and corrupted files when replacing a file already indicated in INFO0.
* **0.0.3** Use decimal entry IDs for filename.
* **0.0.2** Include npdm file.
* **0.0.1** Public release.

## Disclaimer

Forge is created by KolakCC and Raytwo using [Starlight](https://github.com/shadowninja108/Starlight).
We take no responsibility for lost save progress, bricked switches, or anything else.
