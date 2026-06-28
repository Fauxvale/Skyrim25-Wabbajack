<div align="center">
<img src="https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Skyrim25%20Steam%20Logo%20ALT.png?raw=true" Height=300><br>
</div>
<div align=center><i>Skyrim as Todd intended.</i></div>
<br>
<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/161779">Nexus Page</a> |
  README |
  <a href="https://loadorderlibrary.com/lists/skyrim25">Load Order Library</a> |
  <a href="https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Reccomended%20Mods%20to%20Add%20to%20Skyrim25.md">Recommended Mods</a> |
  <a href="https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Mods%20to%20Avoid.md">Mods to Avoid</a> |
  <a href="https://discord.gg/Z99KaaGNgU">Join at Discord</a> ]
</p>

## Releases
# Version 2.1.2

## Summary
Fixed a bug where MO2's content filters weren't working properly. The culprit was FOMOD Plus' `show_fomod_filter` option, which was breaking other Content tags. Disabling it restores filter functionality - the tradeoff is that you can no longer filter by FOMODs or see the wizard hat icon on mods that have one.

- **Added:** 0 mods
- **Removed:** 1 mod
- **Updated:** 1 mod
### Added Mods

- No Mods Added
### Removed Mods
- Arcane Blacksmith's Apron - Hood Fixes - Adds a custom texture for the arcane blacksmith hood that clashes visually with mods like Robes Retexture SE by Xavbio. The improvement is marginal enough that it's better to skip it and let Robes Retexture handle coverage instead - there's no hard conflict, just an aesthetic mismatch. Keep it if you want, but its gone from Skyrim25 going forward.
### Updated Mods

- Assorted mesh fixes: 0.139.2 → 0.139.3

## Other Changes
- FOMOD Plus MO2 Plugin: set `show_fomod_filter` to `false` in config
- Added custom 1809 Dark Mode "Faux Edit" MO2 Theme - new Default
- Added Endorsement Helper Tool for Mod Organizer 2 Plugin

# Version 2.1.1

### Summary
- **Added:** 1 mod
- **Removed:** 0 mods
- **Updated:** 0 mods

## Added Mods

- Critter Fixes

## Removed Mods

No Mods Removed

## Updated Mods

No Mods Updated.

## Other Changes

- Fixed Consistent Sensitivity Overhaul not being properly installed.
- Wrote new [Recommended Mods to Add](https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Recommended%20Mods%20to%20Add%20to%20Skyrim25.md) and [Mods to Avoid](https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Mods%20to%20Avoid.md) docs at the top of the README. I hope these documents help you on your modding adventures! They will continue to be updated alongside the list as time goes on.


# Version 2.1.0

### Summary

Skyrim25 v2.1.0 is a save-safe update that brings many improvements, including but not limited to:
- SkyUI 6.11!
 - Ultrawide Support
- Removal of several redundant, useless, flawed, or otherwise undesireable mods
- Complete re-sorting of the load order in both the left and right panel for both profiles
- Better UX in MO2 thanks to some new plugins and updates
- Updated Synthesis
- Even moar fixes!!!!

### Mod Summary

- **Added:** 6 mods
- **Removed:** 15 mods
- **Updated:** 17 mods

### Misc Changes

 - Updated FOMOD Plus MO2 Plugin to 1.17 → 1.20.1
 - Fixed and Improved Various Issues With Load Order on Both Profiles
 - Fixed Some Inconsistencies Between the Two Profiles
 - Resorted Various Mods
 - Resorted Load Order by Hand for Better Clarity & Organization
 - Swapped Out Some Mods for Better Alternatives (Better Performance, Less Bugs, Lower Plugin Count)

## Added Mods

- SKYRIM25 DUMMY PLUGINS (just placeholder plugins for preserving load order with optional mods)
- Consistent Sensitivity Overhaul (should have less issues than previous sensitivity mod)
- Lingering Subtitles Fix
- ShowRaceMenu - NG
- Stuck on Screen Auto Load Door Fix SKSE
- Zero Bounty Hostility Fix SKSE

## Removed Mods

- Better Dialogue Controls (redundant with SkyUI 6)
- Better MessageBox Controls (redundant with SkyUI 6)
- Congruent Sensitivity - SSE - with Aiming (redundant)
- Dwemer Ballista Crash fix (completely redundant with Skyrim Misc Bugfix Comp. Oops.)
- Favorite Things - Extended Favorites Menu for SkyUI (breaks with SkyUI6)
- Master Occlusion Field (shows up in crash logs a lot for obvious reasons, which may confuse the end user and provides little to zero perf gains)
- NVIDIA Reflex Support (breaks with latest CS, better to just not use it at all to avoid confusion for end user)
- Fullscreen MCM Menu for SkyUI (redundant with SkyUI 6)
- Quest Journal Fix for SkyUI (redundant with SkyUI 6)
- SkyUI - Ghost Item Bug Fix (redundant with SkyUI 6)
- SkyUI - Survival Mode Integration (redundant with SkyUI 6)
- SkyUI 3D Item Offset Fix (Centered Item Card - Script Fix - Improvement) (incompatible with SkyUI6)
- SkyUI Vanilla Menus (breaks some features of SkyUI6)
- Stuck on Screen Load Door Prompt Fix (redundant)
- Zero Bounty Hostility Fix (redundant)

## Updated Mods

- SkyUI: 5.2SE → 6.11 (yipee!)
- MCM Helper: 1.5 → 1.6.2
- Unofficial Skyrim Special Edition Patch - USSEP: 4.3.6c → 4.3.8alpha
- Assorted mesh fixes: 0.139.1 → 0.139.2
- Crash Logger SSE AE VR - PDB support: 1.20.1 → 1.23.2
- Creation Kit Platform Extended for Skyrim: 0.6-b434 → 0.6-b550
- Disable USSEP Unwanted Effects Book Updated & Expanded: 4.3.6c → 4.3.8alpha
- Fish Plaque Fixes and Improvements: 0.2 → 0.3
- LeveledList Crash Fix: 1.1.1 → 2.0
- Load Screen Shading Fix: 0.4 → 0.5
- Mfg Fix NG: 1.0.7alpha → 1.0.9
- Modex - A Mod Explorer Menu (AddItemMenu): 2.2 → 3.0
- Navigator - Navmesh Fixes: 1.8 → 1.8.1
- powerofthree's Papyrus Extender: 6.3 → 6.4
- Robber's Gorge Fixes: 2.3 → 2.4
- SkyPatcher: 6.3.1 → 6.4.2
- Spell Perk Item Distributor (SPID): 7.1.3 → 7.3.1







### __Skyrim25 2.0.7:__
#### MODS

**UPDATED**
 - None

**REMOVED**
  - Item Stacking Tweaks SKSE (buggy, pretty sure it was causing duplication glitches 💀)

**ADDED**
 - None

**Other Changes** 
 - None

### __Skyrim25 2.0.6:__
#### MODS

**UPDATED**
 - Kezyma's Root Builder for Mod Organizer 5.0.5 -> 5.1.1
 - SSE Engine Fixes 7.0.19 -> 7.0.20
 - Crash Logger SSE AE VR - PDB support 1.16 -> 1.20.1
 - Modex - A Mod Explorer Menu (AddItemMenu) 1.2.3 -> 2.2.0 
 - Ultimate Optimized Scripts Compilation 1.6 -> 1.83
 - Robber's Gorge Fixes 2.2 -> 2.3
 - Assorted mesh fixes 0.136 ->  0.139.1
 - Save and Load Accelerator for SKSE Cosaves - S.L.A.C.K. 1.3.1 -> 1.3.2
 - Comprehensive Attack Rate Patch - SKSE 1.1.2.14 -> 1.1.2.15
 - Alt-Tab Stuck Key Fix NG 1.1 -> 1.3.1
 - Stagger Effect Fix 1.0.2 -> 1.0.3
 - Mfg Fix NG 1.0.4 -> 1.0.7a
 - Exit Sneak On Sprint 1.2 -> 1.2.1

**REMOVED**
 - Optional Quick Start - SE (out of scope)
 - Optional Quick Start - Immersive and Sensible Gear (out of scope)

**ADDED**
 - Item Stacking Tweaks SKSE
 - Hide Buttons Mod Organizer 2 Plugin - Biggie Edition
 - Bethesda Plugin Manager MO2 Plugin

 **Other Changes** 
 - `always_restore_choices` in FOMOD Plus config set to `false`
 - Bethesda Plugin Manager `external_change_warning` and `enable_sort_button` set to false
 - Resorted Plugin Load Order by hand

### __Skyrim25 2.0.5:__
#### MODS

**UPDATED**
 - powerofthree's Papyrus Extender 6.2.1 -> 6.3.0
 - SkyPatcher 6.2.1 -> 6.3.1
 - Lightened Skyrim - Base Object Swapper edition 1.09 -> 1.10
 - Assorted mesh fixes 0.131 -> 0.136
 - Favorite Misc Items 3.7.1 -> 4.0.0

**REMOVED**
 - None

**ADDED**
 - None

**Other Changes** 
 - Fixed Load Order

### __Skyrim25 2.0.4:__
#### MODS

**ADDED**
 - Survival Mode - Weapon Speed Patch
 - Save and Load Accelerator for SKSE Cosaves - S.L.A.C.K.

### __Skyrim25 2.0.3:__
#### MODS
**UPDATED**
 - Ultimate Immersion Toggle 1.4 -> 1.5
 - Navigator 1.71 -> 1.80
 - Undo Certain USSEP Changes 2.6 -> 2.8
 - Skypatcher 6.2 -> 6.2.1
 - powerofthree's Papyrus Extender 6.1.1 -> 6.2.1
 - Optional Quick Start 1.2.0 -> 1.2.1

**REMOVED**
 - Unofficial Skyrim Modders Patch - USMP
 - Unofficial Skyrim Modders Patch - USMP - Patch Emporium

**ADDED**
 - Raven Rock - Fix Exit on Horseback
 - Drunk Sinking Head Idle Fix SE
 - No Pause Between Dialogue Lines - GSO (custom for Skyrim25)
 - Don't Talk With Your Mouth Full
 - Charge Dialogue Fix
 - Dragonborn Black Book Fix
 - Butterflies Unchained
 - Vampire Lord Transform FX Fixed
 - Solitude Lighthouse Fix
 - Missing in Action - Dialog Condition Removed
 - Stamina of Steeds
 - Dustman's Cairn Farkas Scene Fix
 - Butterflies Land True - ESPFE Alternate Version
 - Sound Hammering Sounds
 - MQ105SprintTriggerScript Fix
 - The Taste of Death Improved Shutdown
 - Shroud Hearth Barrow Script Fix
 - DLC2AudioRepeaterActivator01Script Tweak
 - Soul Cairn Script Tweaks
 - DLC2PillarBuilderActorScript Tweak
 - DLC2dunFrostmoonTriggerScript Optimization
 - DLC2dunSeekerInvisScript Fix
 - DLC2dunNchardakDoorSeal Script Infinite Loop Fix
 - DLC2MiraakScript Fix
 - DLC2TribalWerebearScript Fix
 - Dragonactorscript infinite loop fix
 - dunFolgunthurBossBattle Script Fix
 - Robber's Gorge Fixes
 - FUS RO DON'T - PushActorAway Crash Prevention Script Tweak
 - CritterSpawn Congestion Fix
 - Unnecessarily Fixed Fixed Dragon Stalking Fix
 - Mannequin Management
 - Greybeard Robe Fix
 - Tavern AI fix
 - Hired Thugs Fixed SSE
 - Improved Weapon Impact EFFECTS Correct Metal SE
 - Modern Clap Bug Fix
 - Scripts Carefully Reworked Optimized and Tactfully Enhanced (SCROTE) - Simply Optimized Scripts AIO
 - Ultimate Optimized Scripts Compilation

#### Other Changes 
 - Re-ran synthesis patcher


### __Version 2.0.2 (Save Safe):__
#### MODS
**UPDATED**
 - None

**REMOVED**
 - Rogue Master Detector 
   - Functionality is already included in MO2. I didn't know. oops

**ADDED**
 - Unofficial Skyrim Modders Patch - USMP - Patch Emporium
   - Added for it's USCCCP Patch

#### Other Changes 
 - None

### Version 2.0.1 (Save Safe):
#### MODS
**UPDATED**
 - Papyrus Tweaks 4.1 -> 4.1.1
 - Skypatcher 6.0 -> 6.2
 - Sovngarde Meshes - FIXES - 1.3 -> 1.4
 - Assorted mesh fixes - 0.130 -> 0.131
 - Enhanced Invisibility - 1.3.0 -> 1.4.1
 - Navigator - Navmesh Fixes - 1.6.3 -> 1.7.1

**REMOVED**
 - Sound Hammering Sounds (included in USMP)

**ADDED**
 - None

- Other Changes - 
 - Updated README to include that you need the Creation Kit. Oops!
 - Re-organized various mods into more new separators for better clarity

### Version 2.0.0 - Initial Release.
