# Skyrim25 - Mods to Avoid

The following mods are flagged as redundant, incompatible, buggy, or otherwise undesirable. Avoid adding these to any load order built on or inspired by Skyrim25.

### Refer to Moddinglinked's [Safe Modding Practices](https://dragonbornsfate.moddinglinked.com/safe-modding.html) page (especially the Mods to Avoid) for even more helpful info and tips.

## Big Mods to Avoid

- **Unofficial Skyrim Modders Patch (USMP)** - and its Patch Emporium companion were also removed from Skyrim25 during development - for good reason. They were replaced by a large collection of individual, targeted bugfix mods. USMP as a whole is too broad and includes many subjective changes - it bundles changes that may not be desirable alongside the ones that are, and individual standalone fixes give more control and transparency over what is actually being changed in your game. DO NOT USE IT. Instead, read the description of USMP and opt-in to the changes you want based on need.
- **Any AI-slop vibe-coded MO2 or SKSE Plugins** - Avoid any mod that appears to be vibe coded or has an AI-generated thumbnail. These are strong signals that the author put little effort into understanding what their mod actually does, which means it is likely poorly written, undertested, and potentially dangerous to your save or your system - AI-generated thumbnails in particular have become a common marker for low-effort or outright malicious uploads on modding platforms. Avoid them.
- **Skyrim Crash Guard** - A mod that claims to let you continue playing through crashes rather than fixing them. It has been taken down twice for not working and has since been re-uploaded. [Per a detailed technical breakdown by Shekhinaga](https://www.reddit.com/r/skyrimmods/comments/1ruffcy/crash_guard_update/), the mod was largely AI-generated with minimal human oversight, its source code was deliberately hidden and sanitized, and several of its advertised features either do nothing or actively corrupt your game state. Its "crash recovery" works by zeroing registers and resuming execution - which doesn't address the underlying cause of the crash and leaves your process in a broken state. Its "memory leak prevention" frees any allocation older than 60 seconds, which is a fundamental misunderstanding of how memory management works. Bug reports and criticism have been actively removed by the author on Nexus. Do not use it under any circumstances. If you are found to be using it, any support is void and you will be asked to remove Crash Guard and reinstall the list from scratch.
- **Open Cities** - needs patches for basically anything that touches a city's worldspace. [SR Exterior Cities](https://www.nexusmods.com/skyrimspecialedition/mods/87954) is a more modern alternative with much better compatibility.

## Redundant with SkyUI 6.x

These mods were written to fill gaps in older versions of SkyUI. As of SkyUI 6.x, their functionality is either fully built in or they serve no purpose. Using them alongside SkyUI 6 wastes plugin slots and may cause unexpected behavior, such as broken widescreen or missing fixes.

- **Better Dialogue Controls** - Functionality is natively handled by SkyUI 6. No longer needed.
- **Better MessageBox Controls** - Same situation as Better Dialogue Controls. SkyUI 6 covers this.
- **Fullscreen MCM Menu for SkyUI** - SkyUI 6 includes this behavior out of the box.
- **Quest Journal Fix for SkyUI** - Fixed in SkyUI 6 itself. Redundant.
- **SkyUI - Ghost Item Bug Fix** - The ghost item bug is addressed in SkyUI 6. Redundant.
- **SkyUI - Survival Mode Integration** - SkyUI 6 handles Survival Mode integration on its own.


## Incompatible or Problematic with SkyUI 6.x

These mods were designed for older versions of SkyUI and actively break or conflict with SkyUI 6. Do not use them if you are running SkyUI 6.

- **Favorite Things - Extended Favorites Menu for SkyUI** - Breaks when used with SkyUI 6.
- **SkyUI 3D Item Offset Fix (Centered Item Card - Script Fix - Improvement)** - Directly incompatible with SkyUI 6.
- **SkyUI Vanilla Menus** - Breaks certain features of SkyUI 6.

## Redundant with Other Included Fixes

These mods duplicate functionality already provided by other mods in a well-built load order. Including them just bloats the list.

- **Congruent Sensitivity - SSE - with Aiming** - Redundant. Replaced by a better-behaved sensitivity overhaul (Consistent Sensitivity Overhaul).
- **Dwemer Ballista Crash Fix** - Completely redundant with Skyrim Miscellaneous Bugfix Compilation, which already covers this crash.
- **Stuck on Screen Load Door Prompt Fix** - Redundant. Replaced by a more robust SKSE-based alternative (Stuck on Screen Auto Load Door Fix SKSE).
- **Zero Bounty Hostility Fix** - Redundant. Replaced by the SKSE version of the same fix (Zero Bounty Hostility Fix SKSE).
- **Rogue Master Detector** - Its functionality is already built into Mod Organizer 2 itself. No need to install it separately.


## Causes Bugs or Active Problems

These mods were removed specifically because they introduced crashes, duplication glitches, or misleading output that could interfere with troubleshooting.

- **Item Stacking Tweaks SKSE** - Buggy. Suspected cause of item duplication glitches. Not worth the risk.
- **Master Occlusion Field** - Appears frequently in crash logs due to its nature, which makes crash analysis harder and more confusing for end users. Provides little to no real performance benefit in exchange.
- **NVIDIA Reflex Support** - Already included with the latest version of Community Shaders. I've found it is better to simply not use this mod at all rather than troubleshoot compatibility going forward. You can use it if you're not using CS upscaling, I just removed it to avoid confusion for people who do.

### Also see [Recommended Mods to Add](https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Reccomended%20Mods%20to%20Add%20to%20Skyrim25.md)
