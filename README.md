----
<div align="center">
<img src="https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/Skyrim25%20Steam%20Logo%20ALT.png?raw=true" Height=300><br>
</div>
<div align=center><i>Skyrim as Todd intended.</i></div>
<br>
<p align="center">
  [ <a href="https://www.nexusmods.com/skyrimspecialedition/mods/161779">Nexus Page</a> |
  README |
  <a href="https://loadorderlibrary.com/lists/skyrim25">Load Order Library</a> |
  <a href="https://discord.gg/Z99KaaGNgU">Join at Discord</a> ]
</p>

----

The bare minimum to make vanilla Skyrim playable in 2025 as it should have been at launch in 2011.

# Introduction
Built as a spiritual successor to SME, Skyrim25 aims to be a clean base to build upon or just to play as-is. On it's own, it provides a near-identical-to-vanilla experience, but with less bugs and crashes *(hopefully)*. Each mod has been chosen to stay out of your way and make room for you to add your own, or just play the damn game if that's what you're looking for. 

## Features and Notable Mods
Skyrim25 provides two profiles: Special Edition and Anniversary Edition. Predictably, these control what Creation Club content is enabled, and their assorted patches. To change profiles, click the profiles dropdown above the left pane in MO2:

<img src="https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/profiles%20dropdown.png?raw=true" Height=200><br>

**Some of the notable, largest mods included in the list are:**
 - Unofficial Skyrim Special Edition Patch - USSEP
   - Undo Certain USSEP Changes & Vanilla Purity Patch on top
 - Unofficial Skyrim Modder's Patch - USMP SE
   - USMP includes a lot of popular bugfixes! Before adding additional fixes and patches, make sure to check if USMP already includes them!
 - (AE Profile Only) Unofficial Skyrim Creation Club Content Patches (USCCCP)
 - Skyrim Misc Bugfix Compilation
 - Cleaned Skyrim SE/AE Textures
 - SkyUI
   - and it's assorted fixes
 - Unofficial High Definition Audio Project (UHDAP)

and many, many more!

### Optionals
Skyrim25 ships with a handful of optional mods you can choose to enable/disable as you see fit. These include:
 - SkyUI Vanilla Menus
 - Smaller Vanilla Cursors SE
 - NVIDIA Reflex Support
 - Modex - A Mod Explorer Menu (AddItemMenu)
 - Congruent Sensitivity - SSE - with Aiming

They can all be individually enabled or disabled as you see fit by clicking the checkbox to the left of the mod name in MO2:

<img src="https://github.com/Fauxvale/Skyrim25-Wabbajack/blob/main/optional%20selection.gif?raw=true" Height=200><br>

# Installation
### System Requirements
If your PC can run vanilla Skyrim, it should be able to run Skyrim25. Refer to the official system requirements on Steam.

* **Processor:** Intel i5-2400/AMD FX-8320
* **Memory:** 8 GB RAM
* **Graphics:** NVIDIA GTX 780 3GB/AMD R9 290 4GB

Additionally, Skyrim25 requires approximately **57GB** of free disk space (around ~40GB for the install, and ~20GB for downloads, though you should probably have a little more than that to allow room for Wabbajack's temp files and such.
>[!TIP]
>You can choose separate locations for the modlist installation and the downloads folder – helpful if one of your drives is low on space. Note that after installation, downloads can be safely deleted, but will need to be re-downloaded if you update the list later.
### Prerequisites
- You must own [Skyrim Anniversary Edition](https://store.steampowered.com/sub/626153/) (the full upgrade, not just SE!) on Steam. While the AE Creation Club content is optional, it is still needed to properly install the list. Sorry!
- Download and install the [Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/) from Steam. Make sure to install to the same path as your Skyrim install.
- You are running an **up-to-date version of Windows**. Download and install the following dependencies:  
    - [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)  
    - [.NET 6.0 Runtime Desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-6.0.30-windows-x64-installer)  
    - [.NET Desktop Runtime 8.X.X x64](https://dotnet.microsoft.com/en-us/download/dotnet/8.0)

>[!WARNING]
>If you already have Visual C++ installed, ensure you run the installer again and select the `Repair` option to update to the latest redistributables. **Do NOT skip this step, or Mod Organizer 2 and the game may fail to launch.**

Then follow these steps:
1. **Run Skyrim Once:**
   - Launch the game to allow it to perform its initial graphics check. The settings will be replaced during installation, so there's no need to configure them now.
2. **Download AE CC content:**
   - Start the game, reach the main menu, and allow it to download the Creation Club content included with the Anniversary Edition. DO NOT ALT-TAB during this step, as it can cause the downloads to pause or outright fail!
3. **Exit the game:**
   - You are now ready to run Wabbajack!

### Running Wabbajack

>[!IMPORTANT]
>The installation **may fail on the first try**. This is normal, please refer to the **If Installation Fails section** below to solve the issues and proceed with the installation.

1. **Install Wabbajack:**
   - Download and install [Wabbajack](https://www.wabbajack.org/).
2. **Get Skyrim25:**
   - Method 1 (from Wabbajack): Open Wabbajack, click "Browse Lists" then search for "Skyrim25". ‼️NOT CURRENTLY AVAILABLE (yet)! USE METHOD 2 
   - Method 2 (from Nexus): Obtain the `Skyrim25.wabbajack` file from the [Nexus Page](https://www.nexusmods.com/skyrimspecialedition/mods/161779). Make sure to unzip the downloaded file.
3. **Follow the Wabbajack Installation Procedure:**
   - Refer to the section [_Installing a Modlist_](https://wiki.wabbajack.org/user_documentation/Installing%20a%20Modlist.html) in the Wabbajack Documentation.

### If Installation Fails:
Try *closing wabbajack completely* and restart the process from step 2 above ("Get Skyrim25"). Due to a bug with Wabbajack, using the "Retry" button is currently not reccomended and may cause unforseen issues.

**Having other problems? Want to report a bug or send suggestions/feedback? Join the [Discord](https://discord.gg/Z99KaaGNgU)!**

## Post-Installation
### Running the Game
1. Navigate to the installation location you selected earlier and launch `ModOrganizer.exe`.
2. Select a profile as described in the **Introduction -> Features** section above.
2. Choose any optionals you would like as detailed in the **Introduction -> Optionals** section above.
3. Change your FOV by expanding the **Finalization & Outputs** separator, double clicking on `Skyrim25 Mod Configs -> Text Files -> Autorun.txt` and change `fov 90 90` to whatever you want, e.g. `fov 105 105` and save
3. Hit the **Run** button in the top right corner and play! Or, alternatively, if you know what you're doing and want to use Skyrim25 as a base to build on, start modding!

### Modifying the List

Modifying the list should be pretty simple and the process is the same as using MO2 on your own. Download mod, install, organize, and sort. However, there are a few things specific to Skyrim25 you may want to note. 

First, Skyrim25 stores all of its Mod Configuration files in their own "mod" under **Finalization & Outputs -> Skyrim25 Mod Configs**. If you want to change a mod's settings or add new configuration files, do it here. It is safe to rename this mod, as well as changing the name of the MO2 profile if desired. Additionally, you may want to replace the splash screen images. The image that shows up when you launch MO2 is stored in `[Skyrim25 install folder]\splash.png`, and the image shown when launching the game itself is in `[Skyrim25 install folder]\mods\Skyrim25 Mod Configs\Interface\splash.png`. Replace these images with whatever you want. Finally, remember to re-run Synthesis when you're done adding mods. Have fun!

#### Credits
**The Entire Modding Community** - For making one of my favorite games last forever.

**The r/skyrimmods Discord** - For helping me learn how to mod and being a friendly place to hang out.

**SEEYOULHATER** - For making Mages & Vikings, a list with system requirements so ridiculous it partially inspired me to make this list, lol. Also their readme is really nice and I copied some formatting from there verbatim. Thanks!

**Bethesda Game Studios** - For making such an amazing, wonderfully broken game.
