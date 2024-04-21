## v0.9
* add Ideology DLC (because i thrive in chaos lmaooo)
* remove 2379076640 More Faction Interaction (would desync calculating the random gift left behind after trader left)
* remove 2878860499 Medicines+ 1.4 (probably never should have included, has at least one messed up HeDiff)
* remove  870089952 cleaning area (probably fine, but pulling out my hair with the FilthTracker desync)
* remove 2809972387 Better Ground Penetrating Scanner
* add    2619652663 Smart Farming (gotta say I'm impressed with Owlchemist's work)
* reconfigure Infused to lowest possible chance as on our current save it desyncs (likely not Infused itself, but our save is getting janky)
* undo custom Nomad Scavanger Mod Patch as now HackingSpeed exists with Ideology enabled `<!-- <HackingSpeed>0.2</HackingSpeed> -->`

## v0.8
* disable Search and Destroy from the Tacticowl mod (but leave it installed as it is a set of 3x mods)
* remove  797360572 Grenade Fix Rearmed as it is an unknown quantity (and thought we saw some odd error messages on GZ using EMP)
* remove 1729446857 Time of Day Switches as the MPCompat patch seems old https://github.com/rwmt/Multiplayer-Compatibility/issues/434
* remove  726244033 Fluffy Breakdowns as the 1.3 version was confirmed compatible, but not the 1.4 nor new 1.5 Update fork reupload.. on the fence about this but meh...
* remove 2021510577 [SYR] more slaves as it is an unknown quantity (and [SYR] harvest yield seemed to cause desyncs)
* remove 1508778962 [SYR] Door Mats as it is an unknown quantity and seeing desync traces about FilthTracker which ?may? be correlated?
* add    1505423207 Door Mat as it is used in other MP modpacks and is rated 4 https://steamcommunity.com/sharedfiles/filedetails/?id=1505423207
* remove 1190364506 Invisible Conduit (previous 1.3 version used to be compatible xml, but this version now has a DLL and is an unknown quantity
* add    1735421319 Underground Conduit or Subsurface Conduit - same steel cost but more work for underground
* add     838336462 Conduit Deconstruct - more easy to remove groups of conduits
* add    2952716728 Power Tab 2 - simple GUI to see details on power grid producers and consumers
* custom-patch Nomad Scavanger Mod that was breaking Manage Outfits menu due to HackingSpeed without Ideology mod. Details: https://gist.github.com/ubergarm/f9d3e4751cdbe6e34bfa1bfa9d05075a

## v0.7
* remove [SYR] Harvest Yield - desyncs seemed to occur when a pawn would harvest or mine and stopped after removing
* remove Fluffy Animal Tab - possibly just correlation, but possibly opening wildlife/animal tab was desyncing with this
* remove Numbers - opening the numbers tab was correlated with desyncs
* remove Dubs Mint Menus - an issue with adding bills was causing desyncs until removing this
* add in Simple Side Arms again now that things are getting more stable as it was likely fine
* add in Vanilla Expanded Weapons Heavy Weapons as I just forgot to add it originally

## v0.6
* remove grazing lands as saw some debug logs about it near a desync (could possibly use [KIT] Graze Up instead?)
* disable smart medicine "stock up" as saw debug logs before many desyncs (and overlaps with vanilla now)
* remove gear up and go as no longer have its companion mod bettert pawn control anyway
* remove incident person stat (continued) as its status is unknown
* remove exotic arsenal as its status is unknown
* remove common sense as it isn't on other MP modpacks list
* remove heat map as status is 3 and thought i saw general errors in debug log
* remove the price is right its status is unknown
* remove simple sidearms as other MP modpacks don't have it and already have dual wielding meh
* remove searchable menus as its status is not known and vanilla has some search bars now it seems
* remove float sub-menus as it was only a dependency for the above mod
* remove mod error checker as not sure exactly what it does and status is unknown
* remove fermenter (continued) as status is not known and not really using it
* remove follow me as it seems too easy to accidently turn on the cinematic camera which can causes desyncs
* remove compositable loadout as we don't know how to even use it
* remove room sense as the debug log throws some error (doesn't desync but whatever)
* remove Netrve's DeepStorage GUI as getting "DSGUI" spam before "Desynced" grepping Player.log file

## v0.5
* remove Fluffy's Work Tab as it seemed to be causing frozen pawns/mechanoids/animals and making clients unable to join while dev log spammed errors. removing it seems to fix.
* remove Fluffy's Mod Manager as it is not recommended on RimWorld Multiplayer Discord
* remove EDB Prepare Carefully as it is not recommended on RimWorld Multiplayer Discord
* remove Gloomy Face mk2 because it seems to overwrite vanilla faces instead of giving additional options
* remove Dub's Paint Shop because we don't use it and it adds complexity
* remove Designator Shapes because we don't use it much and it adds complexity (and flood fill may be a loose stair)
* add Character Editor - don't edit items in MP saves. can use this to bootstrap friends characters into a game etc.
* change config on Smart Medicine to enable stocking up from pawns gear menu (didn't desync in testing)

## v0.4
* remove reinforced structures (already have embrasures for all in concrete walls mod and less obnoxious research)
* considered tiered concrete but went with known and trusted concrete walls
* add vanilla psycasts expanded
* remove choice of psycasts
* considered vpe biotech integration (skipped it as gets too complex for my n00b tastes and untested)
* considered vpe biotech integration for alpha animals and more (alpha animals already has this it seems?)

## v0.3
* add [fsf] complex jobs
* add electric stonecutting table
* remove lights out (seems fine, but just more jobs for pawns to do leave the lights on lol, also have time-of-day switches)
* tweak configs faction interaction to dial back pirate expanding chance (as we have 3 pirate factions)
* tweak configs colony groups for a nice 5x red to green hex code mood color bar
* considered CM Color Coded Mood Bar (but passed as colony groups does enough)
* consider better pawn control over compositable loadouts (unfortunately, bpc is not likely MP compat)

## v0.2
* add Cherry Picker
* cherry pick remove medicines+ hypnotol
* cherry pick remove vanilla hair expanded barber table
* cherry pick remove alpha genetics ocular affinity (ocular jellyfish may desync)
* remove Settlements Quests
* remove Yayo Addon
* remove RT Solar Shield
* remove Solar Shield Retexture
* remove misc. robots as mechinators can do it all now
* remove stabilize here (psure vanilla does this if drafted w/ meds in pawn inventory?) (smart medicine has something too??)
* remove (Multiplayer Compatible) No Skill Decay (seems fine, but given xenotype +8 aptitude helps reduce decay etc)
* remove Pets can Eat from Wall Refrigerator (it isn't tested and seems too risky for the limited gain)
* remove Vanilla Skills Expanded (seems cool, but kind of redundant with xenotype aptitudes and the new passion types don't show up in work tab psure)

## v0.1
* initial test
