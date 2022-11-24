# ElmoRim
 
![](https://staticdelivery.nexusmods.com/mods/1704/images/77787/77787-1666950756-1857011084.png)


# <ins>**NO CC-content required!**<ins>

## Contents
  - [What is ElmoRim?](#What-is-ElmoRim)
  - [Feature Overview](#feature-overview)
  - [System Requirements](#system-requirements)
    - [Minimum Specifications for ~60 fps gameplay at 1920x1080](#minimum-specifications-for-60-fps-gameplay-at-1920x1080)
    - [Setting Up Pagefile](#setting-up-pagefile)
  - [Installation](#installation)
    - [Pre-Installation](#pre-installation)
      - [Setting Shader Cache Size](#setting-shader-cache-size)
    - [Wabbajack Installation](#wabbajack-installation)
      - [Installing Wabbajack](#installing-wabbajack)
      - [Downloading and Installing ElmoRim](#downloading-and-installing-ElmoRim)
    - [Problems with installation](#problems-with-installation)
  - [Post-Installation and Optional Setup](#post-installation-and-optional-setup)
    - [Game Folder](#game-folder)
    - [Antivirus Exceptions](#antivirus-exceptions)
    - [Documentation](#documentation)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
    - [In-Game MCM options](#in-game-mcm-options)
    - [Anniversary Edition](#anniversary-edition)
    - [Updating the modlist](#updating-the-modlist)
  - [FAQ](#faq)
      - [Q: Should I be worried about the Form 43 Error in MO2?](#q-should-i-be-worried-about-the-form-43-error-in-mo2)
      - [Q: How do I change the bodyslide on my character/on NPCs?](#q-how-do-i-change-the-bodyslide-on-my-characteron-npcs)
      - [Q: I can't level up, what do I do?](#q-i-cant-level-up-what-do-i-do)
      - [Q: How do I start the main questline?](#q-how-do-i-start-the-main-questline)
      - [Q: When do dragons start spawning?](#q-when-do-dragons-start-spawning)
      - [Q: How do I become the Thane of Whiterun? How do I get Lydia?](#q-how-do-i-become-the-thane-of-whiterun-how-do-i-get-lydia)
      - [Q: How do I enable my crosshair?](#q-how-do-i-enable-my-crosshair)
      - [Tweaking the Game Settings](#tweaking-the-game-settings)
      - [BethINI](#bethini)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)

## What is ElmoRim?  
ElmoRim is a **compact**, **performance friendly** list that enhances rather than expands Skyrim. The list offers **improved visuals**, **modernized combat** and **increased immersion**. 
The list caters to those who want to play ***Skyrim, and nothing else, in the year 2022***. As such, the list does away with complex new mechanics and massive content additions and instead improves what is already there.

## Feature Overview
ElmoRim consists of around 600 mods. This overview provides an idea of what to expect from the list.
| Feature | Core Mods |
|     :---:    |     :---:     |
| **Visuals**   | Skyland AIO, Modular Armory, Patrician ENB |  
| **Combat**    | MCO, Valhalla, Precision, Valravn    |
| **Gameplay** | SimonRim, Experience, ElmoRim Lite Needs*|
| **Quests**    | Skyrim Unbound, JaySerpa's Quest Expansion-series     |
| **Immersion** | Animated interactions, EVGAT, Animated Eating Redux|
| **Audio**| AOS, ISC, Regional Sounds Expansion, YAMM|
|**UI**| Untarnished UI, BTPS|
| **New lands** | Nope |
|**Followers**| Nope|
| **NSFW** | Nope |

>Not a mod but a combination of features from several mods. Read [on](#gameplay-guide) to find out more.



## System Requirements

### Minimum Specifications for ~60 fps gameplay at 1920x1080

First a word about performance. [QuagaarWarrior](https://www.nexusmods.com/skyrimspecialedition/users/6411808), author of [QW's Grass Patch 2](https://www.nexusmods.com/skyrimspecialedition/mods/67785) and more, sums it up perfectly.
>"I find discussions of performance a little pointless.  
...   
saying whether an individual mod is performance heavy or not is difficult because there are so many other factors at play such as the other mods you use, ENB, resolution you play at and your system specs to name just a few. 
I encourage you to try the mod and see how it performs in your individual set up."

With that said, ElmoRim has been carefully designed to offer a balance between visual quality and performance.

The list was developed on an upper-mid tier laptop with the following specs:

| Spec Category | Default Profile |
|     :---:    |     :---:     |
| **CPU**   | R7 3700x / i5 10600k |  
| **Video Card**    | RTX 3060 Ti / RTX 2070 / RX 6700 XT       |
| **Ram**    | 16gb (2x16) DDR4 3200mhz RAM     |
| **Storage**    | SATA SSD     |

With these specs the game runs at 60 fps at 1080p and 45-50 fps (in exteriors, 60 fps in interiors) at 1440p.

Recommendations on how to change the balance between visual quality/performance are provided [below](#how-can-i-improve-performance)

Modlist size: 
- X GB (of which Y GB are downloads)
  
### Setting Up Pagefile

Due to the resources required to run modlists like these, the system pagefile needs to be configured in order to avoid crashes and bugs that may occur from running out of memory. This step is **NOT** optional. No matter how much RAM or VRAM is available, please do this step.
  
  ***A 40GB fixed-size pagefile for ElmoRim is recommended.***

To set up the pagefile:
1. Press **Win Key + R**
2. Type *sysdm.cpl ,3* and hit **ENTER**
3. Navigate to *Performance* and click the box "Settings..."
4. Click the *Advanced* tab at the top
5. Under *Virtual Memory* click the box "Change..."
6. Uncheck *Automatically manage* if it is checked
7. Select your disk drive, ideally your fastest solid state drive
8. Click the **Custom size:** button
9. In the box next to **Initial Size (MB)** type 40960
10. In the box next to **Maximum Size (MB)** type 40960
11. Click the *Set* button
12. Click *OK*
13. Click *Apply*
14. Click *OK*
15. Restart your computer in order for your new pagefile to take effect.

## Installation

Installing ElmoRim is a straightforward process. A Nexus Premium account is strongly advised.

### Pre-Installation

Prior to installing ElmoRim, complete the following steps.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
2. Change Skyrim so it does not [automatically update](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. Right click on Skyrim SE and click on properties, untick the "Enable Steam Overlay while in-game."

#### Setting Shader Cache Size
 For users with an NVIDIA GeForce Graphics Card: 

 1. Right-click on the desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings to **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner. 
 6. Exit out of the application.
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

### Wabbajack Installation

#### Installing Wabbajack

Once pre-installation is completed, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) on this github and place it in a folder such as `C:\Wabbajack`. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.), or in Skyrim's Steam folder**. Placing it on an SSD will speed up the installation process.

#### Downloading and Installing 

Downloading and installing ElmoRim can take a while depending on internet connection and computer. To install ElmoRim, complete the following steps.

1. Open Wabbajack and click `Browse Modlists`
2. Tick on the `Show Unofficial lists` option in the top right corner of Wabbajack
3. Press the download button on ElmoRim and wait for it to download.
4. Set the installation folder to be somewhere like C:\Games\ElmoRim. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.), or in your Skyrim's Steam folder**
> The download location does not need to be on a SSD, but it makes installing faster.
5. Press the play button to begin.
7. If the installation is successful, prosper and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

### Problems with installation

It is possible to encounter an error with Wabbajack when installing. Some common issues are listed below.

- Could not download x:
	- Big files can fail to download due to connection issues. Either run wabbajack again or download the file manually. If downloading manually, make sure to place it in the same place as the other downloads.

- **X** is not a whitelisted download:

	 - This may happen when the modlist is being updated. Please check if there is a new update or wait until for a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation and Optional Setup

### Game Folder

ElmoRim uses a Wabbajack feature called Stock Game to keep the Skyrim installation folder clean. All the files needed to run the list are in a folder called `Game Root`. No manual copying of files is required.

### Antivirus Exceptions

Generally speaking, using Windows Defender is advised as it is a solid antivirus software that will have minimal interference with the game. Antivirus programs can be notorious for false flagging MO2's VFS as problematic, causing crashes or other problems. 

If using Windows Defender, it is advised to set up an Exception for the modlist. To do this, follow these steps.
 1. Press the Windows Key.
 2. Type "Windows Defender" in the search bar and select *Windows Security*.
 3. Click *Virus & threat protection* in the left pane.
 4. Click the *Manage settings* option under *Virus & threat protection settings*.
 5. Scroll down to *Exclusions* and click *Add or remove exclusions*.
 6. Windows Defender will prompt with a run as administrator screen, select *Yes*.
 7. Click the *Add an exclusion*"* button at the top and choose *Folder*.
 8. Navigate to your Install folder for the list and click *Select Folder*.
 9. **(OPTIONAL)** Repeat these steps for the ModOrganizer.exe (`Path to Modlist`\ModOrganizer.exe), the Nemesis Executable (`Path to Modlist`\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe), and Synthesis (`Path to Modlist`\tools\Synthesis\Synthesis.exe)


 ### Compatibility settings
 Nemesis, xLODGen and DynDOLOD have a tendency to fail even when added to virus exceptions. To avoid this issue, follow theses steps:
 1. Navigate to the Nemesis Executable (`Path to Modlist`\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe).
 2. Right click on the Nemesis Executable, select Properties.
 3. Go to the Compatibility tab
 4. Under the Compatibility mode section, check the Run in comp.. and choose Windows 8 from the dropdown. 
 5. Click Apply and then OK.
 6. Repeat steps 1-5 for SSELODGenx64 and DynDOLODx64 (These are located in `Path to Modlist`\tools..)

### Widescreen Fixes

ElmoRim features mods that provide (potential) Ultrawide and Widescreen Support. Under the **(Possible) Ultrawide Support** Separator in MO2 you will find some mods that you will want to activate if you are playing on Ultrawide or Widescreen resolutions (21:9 or 32:9).

**IN ORDER FOR THESE FIXES TO WORK, DO THE FOLLOWING:**
 1. Search for **Nordic UI XXX Patch** (XXX being the "21 by 9" or "32 by 9" depending on screen resolution) in the left pane of MO2 and delete or hide the following files:  

    a. /interface/skyui/bottombar.swf  
    b. /interface/skyui/itemcard.swf  
 2. Search for **Experience** in the left pane of MO2 and delete or hide the following files:  
    a. /interface/statsmenu.swf  
 3. Search for **Compass Navigation Overhaul** in the left pane of MO2 and open the .ini file, `CompassNavigationOverhaul.ini` and edit the following line(s):  
    a. PositionX=-0.127  
![](https://github.com/aljoxo/Arisen/blob/main/Media/CNO%20UW%201.png)
 4. Once in game, navigate to the *TrueHUD* MCM Menu, and change the following values:
 ![](https://github.com/aljoxo/Arisen/blob/main/Media/TrueHUD%20UW%201.png)
 ![](https://github.com/aljoxo/Arisen/blob/main/Media/TrueHUD%20UW%202.png)
### Documentation
[Changelog](link)  
[Modlist](link)  
[Roadmap](link)  
## Playing the List

### Obligatory DAR Cache warning: due to the nature of this list and the amount of DAR based animations it uses, it does take some time (usually 15-30 seconds) at the start of each play session for DAR to cache all the folders and animations. Please note that this is an issue with DAR itself since it does not allow for pre-cacheing animations via Nemesis or during loading screens. If you complain about this in the discord, on nexus, or on the github page, you will be linked back here.

### Starting the Game

 - Navigate to the installation folder and locate *ModOrganizer.exe* and launch it. If a message Registry Key does not match appear, press *Yes*. Once it's launched, there will be a dropdown box on the top right and a big run button next to it.

![](https://cdn.discordapp.com/attachments/1008052853002219683/1020222827938463764/RegistryKey.png)

 
 - Launch the "ElmoRim" Executable in MO2

### Gameplay Guide

ElmoRim stays true to vanilla gameplay. As such, anyone familiar with Skyrim should be able to jump right in and start playing. The notable exceptions are listed below:

 ***Control map***
  - The ElmoRim keyboard control scheme might seem a bit unorthodox at a glance. It is inspired by the excellent [Streamlined Skyrim](https://github.com/TerribleBrad/Streamlined-Skyrim/blob/main/README.md) and offers a compact layout. While it certainly can modified, it is suggested that users give it a try. Much thought has gone into tweaking controls to allow quick and easy access to all necessary actions.  
  
  ***ElmoRim Keyboard Layout***
  ![](https://user-images.githubusercontent.com/118224262/203798608-b3ff4000-b3e0-422e-8159-1afaa94cee59.jpg) 
  
  ***ElmoRim Mouse Button Layout***
  ![](https://user-images.githubusercontent.com/118224262/203798474-0566bb92-4e11-4baf-9176-074f33738566.png).
  - ElmoRim features mods designed to support playing with a controller. However no pre-configured controlscheme is provided and users are encouraged to create theur own setup.

  ***Elden Equip***
  Ipsum


  ***MCO***
Ipsum

***Skyrim Unbound***
 - ElmoRim uses [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962) as the alternate start mod.
    - In order to start chargen hit *Enter* after loading in
        - If the player character seems to be frozen during RaceMenu, just swap race or gender and swap back, it should unfreeze them. This is an issue with DAR Cacheing.
    - Once finished with chargen, open up the *Skyrim Unbound* MCM menu and customize Standing Stone, whether or not the player is a vampire/werewolf, equipment, spells and starting location.
        - It is possible to choose whether or not the player is the Dragonborn; and if they are not, whether or not they are able to use shouts.
     - Once  finished, hit Enter again and choose *Continue*.

***ElmoRim Lite Survival***
Elmorim comes with a unique setup for survival elements, seamlessly integrated into the general gameplay. 

*Sleep*: The mod [Incremental Injuries](https://www.nexusmods.com/skyrimspecialedition/mods/55114) introduces the need to sleep organically by reducing total Magicka/Health/Stamina as they are spent. They are restored by sleeping 6+ hours in-game. 

By default, ElmoRim also uses the mods [Incremental Gains](https://www.nexusmods.com/skyrimspecialedition/mods/67270) & [Hardcore Level Up - Incremental Gains Addon](https://www.nexusmods.com/skyrimspecialedition/mods/72741) which make max Magicka/Health/Stamina increase by a small amount each time the player sleeps. The attributes increase proportionally to how much they were reduced before sleeping. **Selecting an attribute upon levelling up will now only increase that attribute by one point.** 

`These two mods can be disabled if the vanilla system i preferred.`

*Eat/Drink*: [Apothecary - Food and Drink Addon](https://www.nexusmods.com/skyrimspecialedition/mods/52130) alters food and drink to give long lasting passive regeneration buffs. The buffs are very well balanced to incentivize eating and drinking regularly without making the buffs OP.

*Cold*: The cold system from [Sunhelm - Survival and Needs](https://www.nexusmods.com/skyrimspecialedition/mods/39414) is used to reward preparation. Other Sunhelm mechanics are disabled.

*Camping*: [Camping Lite](https://www.nexusmods.com/skyrimspecialedition/mods/2370) is an excellent, lightweight mod that provides an option for pitching a tent & lighting a fire for warmth/cooking. 

***Experience***
[Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) changes how levelling works in Skyrim. Instead of player level being tied to skill level, experience is now earned through completing quests, discovering new locations and killing enemies.

***Simplest Horse***
Ipsum
### In-Game MCM options

 - **Skyrim Unbound**: 
     - Dragons are set to appear after 7 to 21 days by default. They will appear at word walls before appearing in the wild. They can be configured to spawn faster/slower/instantly or spawn based on level instead.
 - **Better Third Person Selection**: Enables the filters to reduce the possibility that the player character accidentally steals items when trying to interact with the world. Turn these filters off here if preferred.
 - **Favourite Howls Menu**: Customize which powers will be in the favorites menu (for werewolves).
 - **Hide Your Quests**: Allows filtering quests from the journal (not useful on startup, obviously).
 - **Improved Alternate Conversation Camera**: Tweak the dialogue camera here.
     - Notable settings include: Switch Target (for Witcher-Style Dialogue Camera), Force Third/First Person, Camera Offsets.
 - **Optimal Potion Hotkey**: Change *Health potion hotkey* (Default: `H`). Add a hotkey for stamina/magicka potions.
 - **Simplest Horses**: Change *Horse Control hotkey* here (Default: `V`).
 - **SmoothCam**: By default the list uses [Adventurer's Preset](https://www.nexusmods.com/skyrimspecialedition/mods/59997).
 - **SunHelm**: Only Cold enabled as part of the ElmoRim Lite Survival setup.
 - **Survival Control Panel**: Optionally disable Sleep to level up.   
 - **True Directional Movement**: Change your *Target Lock* keybind here.
 - **Valhalla Combat**: The core of the combat balance in the list. 
    - Stamina: The settings here have been configured for what has been determined to be the most balanced gameplay. Feel free to tweak them to your liking. Please note that dTry's Exhaustion system is disabled due to causing enemy aggression problems and it was decided it would be better if it was off.
    - Timed Block: Enable or disable the *Tackle* mechanic (Default: `Disabled`).
    - Compatibility: Choose whether or not to use animations from [Poise](https://www.nexusmods.com/skyrimspecialedition/mods/72653).
      - *TrueHUD API* should say `Not Obtained` next to it, this is due to disabling the Stun System. 
      - If *Special Meter Control* says `Not Obtained`, do not worry about this. As of current the Stun System is disabled due to balancing reasons.

### Anniversary Edition

Wabbajack automatically [downgrades](https://www.nexusmods.com/skyrimspecialedition/mods/57618) the Skyrim installation version 1.5.97. **Do not** downgrade the steam install or the modlist yourself.

## Updating the modlist

Before updating, please check the [changelog](https://github.com/aljoxo/ElmoRim/blob/main/ElmoRimChangelog.md) and back up any saves. A new game may be required after certain updates. To check if an update is save safe or not, refer to the version number. The first digit indicates major version, second digit indicates minor version (these are unlikely to be save safe unless otherwise specified), the third digit will represent bug fixes etc.
  - If the modlist is updated from `1.0.0` to `2.0.0`, then this version is likely a major overhaul of at least one system and **will not** be considered save safe.
  - If the modlist is updated from `1.0.0` to `1.1.0`, then this version is **not** save safe.
  - If the modlist is updated from `1.0.0` to `1.0.1`, then this version is save safe **unless** the changelog specifically states otherwise. In cases where the update **is** save safe, performing additional steps my be needed to maintain the health of the save. Theses will be provided in the changelog.  
  

Updating is like installing the list. Simply check that file paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods added to the installation will be deleted when updating. To ensure that Wabbajack does not delete added mods upon updating, prefix the mods with **[NoDelete]**.

**ALWAYS** back up saves before an update. Because of the method Wabbajack uses to include the start save, any save within the profile will be wiped. 

*Please make sure to back up saves when continuing a playthrough across a **save safe** update.*

## FAQ 

#### Q: I can't level up, what do I do?  
A: You have Sleep to level up enabled, go sleep in a bed or disable it through Survival Control Panel in the MCM.

#### Q: How do I start the main questline?  
A: If you have chosen to be Dragonborn in the Skyrim Unbound MCM settings, then upon killing your first dragon, you will be summoned by the Greybeards. If you have chosen to not be the Dragonborn, then you can not proceed with the main questline.

#### Q: When do dragons start spawning?  
A: By default, dragons are set to be delayed in their spawns from 7 to 21 days after you leave the starting room. By default, dragons will begin showing up at their Word Walls before you will encounter them in the wild.

#### Q: How do I become the Thane of Whiterun? How do I get Lydia?  
A: You must complete [The Blessings of Nature](https://en.uesp.net/wiki/Skyrim:The_Blessings_of_Nature) quest and talk to Jarl Balgruuf when the Gildergreen tree is repaired/the sappling blooms. He'll thank you and allow you to buy the Breezehome, and the standard thaneship quest (help people of the hold and buy a house to become a thane) will be available.

#### Q: How do I enable my crosshair?
A: Disable the `Contextual Crosshair` mod, under the "Heads Up Display (HUD)" Separator in MO2.

### Tweaking the Game Settings

#### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 1024
- `Grass Density`: 60
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

If you want to tweak your ENB to improve performance, consider looking at Annakin's [ENB Tips](https://github.com/The-Animonculory/Modding-Resources/blob/main/ENB%20Tips.md) guide. 

To quote her, here is a short answer to improve performance with an ENB turned on.
> #### How can I improve performance?
> - Uncheck `EnableLens`.
> - Uncheck `EnableBloom`.
> - Uncheck `EnableDepthofField`.
> - Uncheck `EnableTessellation` in `WATER`.
> - Uncheck `ComplexFireLights` and `ComplexFireLights` OR
>   - Uncheck `EnableBigRange` in these two settings.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Contact


## Credits and Thanks

- _YOU_ for reading this.
- Noggog for Mutagen and the xEdit team for xEdit and their tools.
- Halgari and the WJ Team for this amazing platform.