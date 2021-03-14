# Call of Duty Extended [Client]

Call of Duty Extended Client is a modification of the Call of Duty 1 client game. It supports patch 1.1.
Goal of this project is to fix bugs from the original 1.1 client, add features that are present in newer, but less popular patches, and also to add some of our own unique features (e.g. Discord RPC, CoD 4-like UI elements).

## Changes/additions

- servername whitelist (removed [] symbols and trailing spaces in hostname, patched empty hostname)
- fixed  "invalid CD-Key" when using fs_game / mods
- cURL (HTTP/fast) download
- CoD 4-like scoreboard & loading screen (optional - cg_xui_scoreboard 1, cg_xui_connect 1)
- Discord RPC
- unlocked FOV (80-95, change with cg_fov)

## Presentation of several functions
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/OTtJrzUuO70/0.jpg)](https://www.youtube.com/watch?v=OTtJrzUuO70)

## Usage

Note! Your own build will not be the same as the officialy released patch! Some servers may prevent you from joining them when using a non-official build of Extended.

Compile (you will need additional dependencies - libcurl, Discord RPC)<br>
Rename old mss32.dll to miles32.dll<br>
Copy newly compiled DLL to game directory and rename it to mss32.dll<br>
???<br>
PROFIT<br>

## Questions

Forum: http://xtnded.org (php)<br>
Steam: riicchhaarrd (php)<br>
Discord: Defected#0001 (dftd) / Prawy#3490 (PrawyCoD1)<br>

## License

CoDExtended is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
