

Purpose

A dedicated ward mod aimed at improving the way wards work in Valheim.

# Update Information
### v1.8.0
- Compile against latest game version. Exploit fixes, File watcher added. (You can now directly change the configs on the server via the file...and they will update for all clients connected.)
### v1.6.5/1.7.0
- Update to ServerSync.
- If you have configuration manager and are an admin on a dedicated server, you can now change the options from within the game.
- Config options now say in their descriptions if they sync with the server or not. Just to add additional help if you're confused.
- Please note: This is probably the last update I am going to make to this version of code. There will be a new mod released by me that has a new name, but all (and more) of the same features. Some that you have wanted for ages. See you on the other side.

### v1.6.4
- Added Oven & HotTub unlimited fuel options
- Added Crafting Station & Smelter interaction options (denied by default if not permitted)
- Continuous Interaction fix with hearths, smelters, etc.
- Additonal overlap checking to fix "clipping" a ward into something to still allow placement when not permitted

### v1.6.3
- Fix issue with structural integrity found on some servers.
- Attempt to fix previous ability to overlap a ward you aren't permitted on.
- Attempt to fix issues with ServerSide Simulations compatibility.
- Pull code from my test environment to fix other issues, commands being the top one.
- Will look into the interaction issue with SeedTotem for the next update.
### v1.6.2
- No food drain fix after Hearth & Home
- Commented out Changelog patch, might make my own for updates
### v1.6.1
- BepInEx update
- Compatibility with Hearth & Home
- Auto close door time control
- Show Flash config option added
- Fireplace Buff Bug fixed
- BIG UPDATE coming soon!!!

Known Mod Conflicts


* Anything that toggles PvE/PvP and forces the value will conflict if you have this mod toggle the values. Current known mods that do this are:
﻿World of Valheim - Zones
﻿PvP-Always-On

Features

* The hotkey can be adjusted by the configuration file.
*  Changelog on main menu shows updates for your version
*  Allow permitted users on the ward to toggle the ward on and off
*  PvP/PvE forced configurations
*  Ward Range configuration (Enemy spawns will query the range to prevent spawning inside base)
* Health/Stamina Boosts for all players inside ward
* Show area marker for the ward (configurable)
* Indestructible structures can be defined for further custom config (inside ward) (FULL LIST)
* Auto Close Doors inside ward (configurable)
* Enforced Config with server (besides client custom configs)
* Reduce damage to player structures inside ward from other players, or increase default health of structure (applies to all inside ward)
* Notification of being inside a ward and who the owner is (configurable)
* Sync Admin list from server for additional configurations (auto permit on nearby wards, permit/unpermit/enable/disable/destroy/flash with command)
* Damage boosts to Players against NPCs while inside ward (configurable)
* Server version checking, must have mod & must be same version as server
* Warded portal interact/teleport configurable
* Ward pushout
* Unlimited fireplace fuel in warded area configurable
* Configurable interaction in warded area
* No Weather Damage
* Visual Bubble
* Offline Raid protection
* Configurable ward recipe for Better Wards
* Auto repair structures inside ward
* No food drain inside ward
* Call to Arms PvP (BETA Phase!)

Client Custom Config Options

* Hotkey option for ward toggle (Default is "G").
* Auto Close Doors (enable/disable)
* Notification of being inside a ward and who the owner is (enable/disable)
* Show area marker for the ward (enable/disable)

Admin Only


* Hotkeys are UpArrow for enabling a ward, DownArrow for disabling a ward (must be looking at it)
* Auto permit on enabled wards nearby (client configurable)
* Admin only chat/console(F5) commands (permit, unpermit, enable, flash, disable)


Installation Instructions
NOTE: The archive comes with the default config file and DLL inside the correct folder structure.

Windows (Steam)
1. Locate your game folder manually or start Steam client and :
   a. Right click the Valheim game in your steam library
   b. "Go to Manage" -> "Browse local files"
   c. Steam should open your game folder
2. Extract the contents of the archive into the game folder.
3. Locate azumatt.BetterWards.cfg under BepInEx\config and configure the mod to your needs

Server
﻿Must be installed on both the client and the server for syncing to work properly.
1. Locate your main folder manually and :
   a. Extract the contents of the archive into the main folder that contains BepInEx
   b. Launch your game at least once to generate the config file needed if you haven't already done so.
   c. Locate azumatt.BetterWards.cfg under BepInEx\config on your machine and configure the mod to your needs
2. Reboot your server. All clients will now sync to the server's config file even if theirs differs. Config Manager mod changes will only change the client config, not what the server is enforcing.


Feel free to reach out to me on discord if you need manual download assistance.


What if the game updates?

Game updates are unlikely to do more than partially break Better Wards at worst. In case you encounter any issues, please reach out to the me.


Where is the configuration file?

The Config file's name is "azumatt.BetterWards.cfg" it needs to be placed in "BepInEx\config"




Open to suggestions (drop them in the suggestion box)!








# Author Information

### Azumatt

`DISCORD:` Azumatt#2625

`STEAM:` https://steamcommunity.com/id/azumatt/﻿

For Questions or Comments, find me﻿ in the Odin Plus Team Discord:
[![https://i.imgur.com/XXP6HCU.png](https://i.imgur.com/XXP6HCU.png)](https://discord.gg/Pb6bVMnFb2)