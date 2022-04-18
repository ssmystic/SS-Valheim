# Purpose

A minor anti-dickhead mod. Server files dictate what is blacklisted/not allowed. Admins/Moderators bypass the check for plugins.

# Video Explanation (3 Videos)
[![AzuAnticheat Demonstration Videos](https://img.youtube.com/vi/pd1dhX7Orxg/0.jpg)](https://youtube.com/playlist?list=PLyVQ1HvkGPdp5KET83-PfuPubdbiE-Zot)
## v1.6.0
- Compile against latest version of the game, Update BepInEx/ServerSync.
## v1.5.0
- Important Internal changes.
## v1.4.1 (Quality of life update)
- Show Server name above world name in discord output.
- SteamID section in discord output name changed to Steam Information. It will now include SteamAccountName and SteamID
- Fixed some discord output randomly saying the world name for PlayerLocation
- Additional checks when using Multiverse mod.
## v1.4.0 
- ***MAJOR INTERNAL CODE REWORK*** - Please **PLEASE** regenerate your whitelist, greylist, etc files. They now only look at loaded plugins (and more efficiently) and does not load all DLLs found in the folder. If you do not heed this warning, you will have a lot of false positives for cheating!!!
- Internal GreyList Updates/Fixes. This should help eliminate some issues users were having.
- Reminder, do not have dlls and BepInEx plugin names on the whitelist AND the greylist. Whitelist is only for mods you want to enforce on the client, the greylist is for additional mods found on the client that you don't care if they have. Some servers were doing this, and it would give blank results on "DLLs Missing"
## v1.3.0 
- "Grey List" addition. Put your optional mods in "aac_greyList.txt"
- Comments in the text file starting with "//" shouldn't matter anymore. Left the comments in there to remove it just in case there are issues.
## v1.2.8 
- Serverside Simulations Damage fix. Heavily tested with and without SSS. We should be good now :)
## v1.2.7 
- Serverside Simulations fix
- Bug fix
## v1.2.6 
- Fix for killing yourself causing a kick from the server
## v1.2.5 
- Bug fixes
## v1.2.4 
- Hearth & Home Update/Compatibility
## v1.2.3 
- Fix console check issue with certain servers using Better Continents and CLLC with console enabled.
## v1.2.2 
- Fix admin check for whitelist on serverside
## v1.2.1 
- Fix compatibility with MagicOverhaul (again)
- Add more Moderator config options
- Update to the AntiCheat checks
- Whitelist mode will now require clients to have all mods on the whitelist.
- Color code some output to discord.
- Additional logging for DLLs. Client and Server side to help with issues reported.
## v1.2.0 
- Fix compatibility with MagicOverhaul
- REMOVED THE NEED TO RUN AS ADMIN 
- Update to the AntiCheat checks
## v1.1.0 
- Begin adding configuration options (AzuAntiCheat.cfg)
- Remove creation of config folder, files will now be created directly in config folder with "aac_" prefix
- Default to whitelist option, can be changed back. If using whitelist, you must include all DLL and BepInNames
- Generate BepInNames and DLL names to files in BepInEx/AzuAntiCheat/ folder
  - Files will be repopulated each time you load the game
- Fix errors with File not found on System files
- Log to server logs when webhook is null with information that would have been in webhook
- Eliminate need for litJSON dependency.
- Change format of discord output to be embedded message
  - Swapped player id to now be player location, so you know where they were when the cheat occurred
- Custom disconnect codes to provide compatibility with other mods invoking similar methods
- Prevent and penalize user for attempting to use ExploreAll map cheat
- Code cleanup/optimizations and encoding changes to files
***
## Disclaimer

I do not claim that this will block all cheats, especially for those that are more tech savvy than the average user. Therefore, if you do some hacky things to bypass this, you can either help fix it, or not claim it's a bug/issue. This mod attempts to block and help maintain quality of life on a server that prefers to check for as much cheating as they can. I'll eventually add more features to this one as it's a light version of my existing that I use.



## Features

* Logging to discord using the Webhook.txt file
* Checks for common cheats activated in game
* Can check for WeMod, CheatEngines etc.
* Blacklist/Whitelist on server, preloaded with recommended dlls to block/whitelist

## Admin Only
* Can cheat and bypass DLL/Plugin Checks

## Moderator
* Only bypasses DLL/Plugins by default. Can't activate common cheats or use cheat engines unless allowed by the server configs.

***
```Must be installed on the client and the server.```



Feel free to reach out to me on discord if you need manual download assistance. https://discord.gg/KKHujtRGvB


Open to suggestions!

***
### Author Information

Azumatt
DISCORD: Azumatt#2625

STEAM: (https://steamcommunity.com/id/azumatt/﻿)


Special thanks to KG for some of the mod features!