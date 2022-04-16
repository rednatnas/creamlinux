# Creamlinux
CreamApi(dlc unlocker) for Linux.

## BIG NOTICE PLEASE READ
This has primarily been made for my personal use, however I have decided to open source it. A lot of the code is based on hookey, which means this will work for HOI4 but other games are unknown. Maybe don't try it on VAC-secure games. THIS WILL NOT WORK THROUGH WINE/PROTON (maybe)

## Usage
1. build the project with `sh build.sh`.

2. Copy build/lib folder contents to the game folder.
3. Then set steam launch params: `./cream.sh %command%`
4. If you copied an existing cream_api.ini, make sure the line endings are set to linux line endings, otherwise this will not work (just open it and save it again)

When the dialog pops up, it will look a bit strange due to steam's bundled deps being ancient (gtk2 is seriously out of date). If you are running on Arch, you can run steam-native.


If you want to load cream_api.ini from a separate path, specify the path with CREAM_CONFIG_PATH;

## Credits
mINI for ini.h

Valve for steamworks

[gabime](https://github.com/gabime) for [spdlog](https://github.com/gabime/spdlog)

goddeysfreya for [hookey](https://github.com/goddessfreya/hookey)
