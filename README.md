RimWorld 1.4 Multiplayer Kitchen Sink Reloaded Modpack
===
![Rimworld 1.4 Multiplayer Kitchen Sink Reloaded Modpack Logo](mp-kitchen-sink-reloaded-logo-wide.png)
[![License](https://i.creativecommons.org/l/by-nc/3.0/88x31.png)](https://creativecommons.org/licenses/by-nc/3.0/)
[![Version](https://img.shields.io/badge/Rimworld-1.4-green.svg)](http://rimworldgame.com/)

Required DLC:
* Royalty
* Biotech

Untested DLC:
* Ideology

Multiplayer:
* Zetrith's Multiplayer Mod
* Multiplayer Compat

A few years have gone by and now its time to try again. This modpack is
a slightly less ambitious updated reload of a previous pack that never
stopped desync'ing.

## Installation

1. Click `Subscribe to all` on the ![Steam](https://i.imgur.com/XEAiSka.png) [Mod Collection](https://steamcommunity.com/sharedfiles/filedetails/?id=3174706609) (like and favorite if you choose)
2. Download the [latest config files here](https://github.com/ubergarm/rimworld-mp-kitchen-sink-reloaded/archive/master.zip)
3. Copy/paste the `Config` and `HugsLib` folders from the zip replacing yours e.g. `C:\Users\%USERPROFILE%\AppData\LocalLow\Ludeon Studios\RimWorld by Ludeon Studios\Config` or in Linux `~/.config/unity3d/Ludeon Studios/RimWorld by Ludeon Studios/Config`
4. Workshops mods constantly change so pin them by zipping `~/.steam/steam/steamapps/workshop/content/294100/*` and vendoring it to clients to unzip into `~/.steam/steam/steamapps/common/RimWorld/Mods/`. Don't use the "make local copies" as it messes up the mod names and patches are not properly applied.
   To find the dir to put the mods windows go to `Steam -> Library ->Rimworld -> Gear -> Manage -> Show Folder` will be something like `D:\mySteamGames\steamapps\common\RimWorld\Mods` or whatever you use...

You can skip step 4, but it may be possible mod updates will break the MP compat of the pack during a long playthrough.
Once you are using local versions of the mods, just ignore the mod manager notes about updated versions.

## Loose Stairs
Known source of desyncs:

* If you don't have Ideology enabled, Nomad Scavanger may break your Manage Outfits and Apparel lists unless updated/patched.
* RimHud - don't click self-tend toggle in RIMHud UI - use Health Tab button instead!??
* Alpha Genes - don't use string genes to transmit genes to selected target (is bugged, only xfers names but not genes)??
* More Faction Interaction - Avoid Help With Harvest, Diplomatic Marriage, Annual Expo Event (disabled this in config)
* Vanilla Persona Weapons Expanded - changing persona weapon appearence causes desync, reachin baron/baroness and picking a custom persona weapon causes desync (have server do it alone and save)
* Vanilla Hair Expanded - don't use the barber table (removed it with cherrypicker)
* Set Up Camp - has bugs with multi-faction multiplayer mode (tested okay with normal mode)
* Smart Medicine - disabled stock-up in the configs as it conflicts with vanilla stock-up features and causes desyncs
* Replace Stuff - don't use replace tool, just place new materials over old ones instead
* Colony Groups - Group Menu -> Work -> Form Caravan desyncs, don't use any features except as a colonist bar replacement
* Yayo - not known for desyncs, but just to be safe disable ammo as it is just too much more variables

## Unknown Quantities
These mods have nothing listed in compatibilty spreadsheet:

* Startup Impact 1.4 - only for testing
* Better Surgery - tested okay, failed catastrophic surgery and no desyncs. seems like a good mod!
* Medicines+ 1.4 - hypnotol seems bugged and throws errors but does not desync...
* Tacticowl - it is listed as supported on MPCompat and its 3x base mods are compat, disabled search and destroy to be extra safe
* ResearchPal - 1.4 Repackage - so far so good in very limited testing
* Holy Washer (Continued) - tested good
* Faction Control 1.4 - in limited testing seems okay
* Deep Storage Plus (Continued) - so far so good, the old one was fine

## Testing
Start up an MP server and connect to yourself by starting a second copy
of RimWorld.
```bash
LC_ALL=C ~/.local/share/Steam/steamapps/common/RimWorld/RimWorldLinux -logfile /tmp/rimworld_test_client_log
```

## Development
Copy all configs in linux here:
```bash
./update.sh
```

## References
* [RimWorld Multiplayer Kitchen Sink Reloaded Modpack Steam Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=3174706609)
* [RimWorld Multiplayer Kitchen Sink Reloaded Modpack GitHub](https://github.com/ubergarm/rimworld-mp-kitchen-sink-reloaded)
* [RimWorld Multiplayer Discord Compatibility Spreadsheet](https://docs.google.com/spreadsheets/d/1jaDxV8F7bcz4E9zeIRmZGKuaX7d0kvWWq28aKckISaY/edit#gid=1144921800)
* [HugsLib Record for reference Player.log files](https://gist.github.com/HugsLibRecordKeeper)
* [Multiplayer-able ModPack by Charlotte/NotFood](https://steamcommunity.com/sharedfiles/filedetails/?id=1618452047)
* [Bear's Multiplayer ModPack](https://steamcommunity.com/sharedfiles/filedetails/?id=2930590984)
