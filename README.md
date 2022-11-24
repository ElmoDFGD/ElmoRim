
 
![](https://staticdelivery.nexusmods.com/mods/1704/images/77787/77787-1666950756-1857011084.png)


# ElmoRim

## Contents
  - [What is ElmoRim?](#What-is-ElmoRim)
  - [Feature Overview](#feature-overview)
  - [Pre-Installation](#pre-installation)
    - [System Requirements](#system-requirements)
    - [Software Setup](#software-setup)
    - [Setting Up Pagefile](#setting-up-pagefile)
    - [Setting Shader Cache Size](#setting-shader-cache-size)
  - [Installation](#installation)
    - [Wabbajack Installation](#wabbajack-installation)
    - [Downloading and Installing ElmoRim](#downloading-and-installing-ElmoRim)
    - [Problems with installation](#problems-with-installation)
  - [Post-Installation](#post-installation)
    - [Game Folder](#game-folder)
    - [Antivirus Exceptions](#antivirus-exceptions)
    - [Compatibility Settings](#compatibility-settings)
    - [Widescreen Fixes](#widescreen-fixes)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
    - [Gameplay Guide](#gameplay-guide)
    - [MCM Customization](#mcm-customization)
    - [Updating the modlist](#updating-the-modlist)
  - [FAQ](#faq)
      - [Q: Why does the list claim to be vanilla when it clearly isn't.](#q-why-does-the-list-claim-to-be-vanilla-when-it-clearly-isnt)
      - [Q: I can't level up, what do I do?](#q-i-cant-level-up-what-do-i-do)
      - [Q: How do I start the main questline?](#q-how-do-i-start-the-main-questline)
      - [Q: When do dragons start spawning?](#q-when-do-dragons-start-spawning)
      - [Q: How do I become the Thane of Whiterun? How do I get Lydia?](#q-how-do-i-become-the-thane-of-whiterun-how-do-i-get-lydia)
      - [Q: How do I enable my crosshair?](#q-how-do-i-enable-my-crosshair)
  - [Tweaking the Game Settings](#tweaking-the-game-settings)
      - [BethINI](#bethini)
      - [ENB Settings](#enb-settings)
  - [Documentation](#documentation)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)

## What is ElmoRim?  
ElmoRim is a **compact**, **performance friendly** list that enhances rather than expands Skyrim. The list offers **improved visuals**, **modernized combat**, **increased immersion** and unique, lightweight survival setup. 
The list caters to those who want to play ***Skyrim in 2022***. A carefully curated selection of tweaks and fixes for the vanilla content allows the player to take full control of their story.

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

>*Not a mod but a combination of features from several mods. Read [on](#gameplay-guide) to find out more.



## Pre-Installation

### System Requirements

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

With these specs the game runs at 60fps@1080p and around 45fps@1440p (in exteriors, 60 fps in interiors).

Recommendations on how to tweak the balance between visual quality/performance are provided [below](#tweaking-the-game-settings)

Modlist size: X GB (of which Y GB are downloads)

### Software Setup 
The first step of installing ElmoRim is making sure all required software is installed and that Steam is configured correctly.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
2. Disable Steam [auto-updates](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
3. In Steam, right click on Skyrim SE and click on *Properties*, untick *Enable Steam Overlay while in-game*.
  
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
7. Choose a disk drive, ideally the fastest solid state drive
8. Click the **Custom size:** button
9. In the box next to **Initial Size (MB)** type 40960
10. In the box next to **Maximum Size (MB)** type 40960
11. Click the *Set* button
12. Click *OK*
13. Click *Apply*
14. Click *OK*
15. Restart the computer in order for the changes to take effect.

### Setting Shader Cache Size
 For users with an NVIDIA GeForce Graphics Card: 

 1. Right-click on the desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings to **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner. 
 6. Exit the application.
![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)
## Installation


### Wabbajack Installation


Once pre-installation is completed, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Wabbajack`. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.) or in Skyrim's Steam folder**. Placing it on an SSD will speed up the installation process.

### Downloading and Installing ElmoRim

Installing ElmoRim is a straightforward process. A Nexus Premium account is strongly advised. Download and installation can take a while depending on internet connection and computer specs. To install ElmoRim, complete the following steps.

1. Open Wabbajack and click `Browse Modlists`
2. Tick the `Show Unofficial lists` option in the top right corner of Wabbajack
3. Press the download button on ElmoRim and wait for it to download.
4. Set the installation folder to be somewhere like C:\Games\ElmoRim. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.), or in Skyrim's Steam folder**
> The download location does not need to be on a SSD, but it makes installing faster.
5. Press the play button to begin.
7. If the installation is successful, prosper and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.
>Wabbajack automatically [downgrades](https://www.nexusmods.com/skyrimspecialedition/mods/57618) the Skyrim installation version 1.5.97. **Do not** downgrade the steam install or the modlist yourself.

### Problems with installation

It is possible to encounter errors when installing with Wabbajack. Some common issues are:

- Could not download x:
	- Big files can fail to download due to connection issues. Either run wabbajack again or download the file manually. If downloading manually, make sure to place it in the same place as the other downloads.

- **X** is not a whitelisted download:

	 - This may happen when the modlist is being updated. Please check if there is a new update or wait until for a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in windows defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

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
 1. Navigate to the Nemesis Executable (`Path to Modlist`\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe)
 2. Right click on the Nemesis Executable, select Properties.
 3. Go to the Compatibility tab
 4. Under the Compatibility mode section, check the Run in comp.. and choose Windows 8 from the dropdown. 
 5. Click Apply and then OK
 6. Repeat steps 1-5 for xLODGenx64 and DynDOLODx64 (These are located in `Path to Modlist`\tools..)

### Widescreen Fixes

ElmoRim features mods that provide (potential) Ultrawide and Widescreen Support. The **(Possible) Ultrawide Support** separator in MO2 contains mods for playing on Ultrawide or Widescreen resolutions (21:9 or 32:9).

**IN ORDER FOR THESE FIXES TO WORK, DO THE FOLLOWING:**
 1. Search for **Experience** in the left pane of MO2 and delete or hide the following files:  
    a. /interface/statsmenu.swf  
 2. Search for **Compass Navigation Overhaul** in the left pane of MO2 and open the .ini file, `CompassNavigationOverhaul.ini` and edit the following line(s):  
    a. PositionX=-0.127  
![](https://github.com/aljoxo/Arisen/blob/main/Media/CNO%20UW%201.png)
 3. Once in game, navigate to the *TrueHUD* MCM Menu, and change the following values:
 ![](https://github.com/aljoxo/Arisen/blob/main/Media/TrueHUD%20UW%201.png)
 ![](https://github.com/aljoxo/Arisen/blob/main/Media/TrueHUD%20UW%202.png)

## Playing the List

##### Obligatory DAR Cache warning: due to the nature of this list and the amount of DAR based animations it uses, it does take some time (usually 15-30 seconds) at the start of each play session for DAR to cache all the folders and animations. Please note that this is an issue with DAR itself since it does not allow for pre-cacheing animations via Nemesis or during loading screens.

### Starting the Game

 - Navigate to the installation folder and locate *ModOrganizer.exe* and launch it.  
  If a message: *Registry Key does not match* appears, press *Yes*. Once it's launched, there will be a dropdown box on the top right and a big run button next to it.
 
 - Launch the *ElmoRim* executable in MO2

### Gameplay Guide

ElmoRim is centered around vanilla content. As such, anyone familiar with Skyrim should be able to jump right in and start playing after reading about the mods listed below (and visiting their nexus page!):

 #### ElmoRim Control scheme
  - The ElmoRim keyboard control scheme might seem a bit unorthodox at a glance. It is inspired by the excellent [Streamlined Skyrim](https://github.com/TerribleBrad/Streamlined-Skyrim/blob/main/README.md) modlist and offers a compact layout. While it certainly can be modified, it is recommended that users give it a try. Much thought has gone into tweaking the controls to allow quick and easy access to all necessary actions.  

  - ElmoRim features mods that support playing with a controller. However, no pre-configured control scheme is provided and users are encouraged to create their own setup.
  
  ![](https://user-images.githubusercontent.com/118224262/203798608-b3ff4000-b3e0-422e-8159-1afaa94cee59.jpg) 
  
  ![](https://user-images.githubusercontent.com/118224262/203798474-0566bb92-4e11-4baf-9176-074f33738566.png).

  #### Elden Equip
  Ipsum


  #### ElmoRim Combat
Ipsum

#### Skyrim Unbound
ElmoRim uses [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962) as the alternate start mod.
* In order to start chargen hit *Enter* after loading in. If the player character seems to be frozen during RaceMenu, just swap race or gender and swap back, it should unfreeze them. This is an issue with DAR Cacheing.
* Once finished with chargen, open up the *Skyrim Unbound* MCM menu and customize Standing Stone, whether or not the player is a vampire/werewolf, equipment, spells and starting location.
It is possible to choose whether or not the player is the Dragonborn and, if they are not, whether or not they are able to use shouts.
* Once finished, hit Enter again and choose *Continue*.

#### ElmoRim Lite Survival
Elmorim comes with a unique setup for survival elements, seamlessly integrated into the general gameplay. 

* *Sleep*: The mod [Incremental Injuries](https://www.nexusmods.com/skyrimspecialedition/mods/55114) introduces the need to sleep organically by reducing max Magicka/Health/Stamina as they are spent. They are restored by sleeping 6+ hours in-game. 

    >By default, ElmoRim also uses the mods [Incremental Gains](https://www.nexusmods.com/skyrimspecialedition/mods/67270) & [Hardcore Level Up - Incremental Gains Addon](https://www.nexusmods.com/skyrimspecialedition/mods/72741) which increases max Magicka/Health/Stamina by a small amount each time the player sleeps. The attributes increase proportionally to how much they were reduced before sleeping. **Selecting an attribute upon levelling up will now only increase that attribute by one point.** 
    >These two mods can be disabled if the vanilla system is preferred.

* *Eating/Drinking*: [Apothecary - Food and Drink Addon](https://www.nexusmods.com/skyrimspecialedition/mods/52130) alters food and drink to make them give long lasting passive regeneration buffs. The buffs are very well balanced and incentivize eating and drinking regularly without making the buffs OP.

* *Cold*: The cold system from [Sunhelm - Survival and Needs](https://www.nexusmods.com/skyrimspecialedition/mods/39414) is used to reward preparation and increase immersion. Other Sunhelm mechanics are disabled.

* *Camping*: [Camping Lite](https://www.nexusmods.com/skyrimspecialedition/mods/2370) is a lightweight mod that provides an option for pitching a tent & lighting a fire for warmth/cooking. 

#### Experience
[Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) changes how levelling works in Skyrim. Instead of player level being tied to skill level, experience is now earned through completing quests, discovering new locations and killing enemies.

#### Simplest Horses
The best mod for horse management in Skyrim. [Simplest Horses](https://www.nexusmods.com/skyrimspecialedition/mods/54225) gives the player the ability to have the horse follow/wait and open stash items with a single button. If the crosshair is aimed at the horse, pressing the button opens the horses inventory. Otherwise it triggers the horse whistle, telling the horse to wait/follow.
### MCM Customization
Almost all of ElmoRim's MCM menus are pre-configured. This section outlines the few mandatory manual tweaks that are required and lists a few optional ones.
#### Mandatory

*SunHelm*: Disable powers under *General>Enable/Disable powers*. Only Sunhelms Cold system is enabled as part of the ElmoRim Lite Survival setup. 

*Valravn*: Disable (or set to 0) everything except *Attacks of Opportunity* and *Bow Stamina Cost*.

*Incremental Gains*: Set Soft Cap Base to 125.

#### Optional
*Skyrim Unbound*  
Dragons are set to appear after 7 to 21 days by default. They will appear at word walls before appearing in the wild. They can be configured to spawn faster/slower/instantly or spawn based on level instead.
 
 *Better Third Person Selection*  
 Enable/disable the filters that prevent the player from accidentally stealing items when trying to interact with the world.
 
 *Favourite Howls Menu*  
 Customize which powers will be in the favorites menu (for werewolves).
 
 *Hide Your Quests*  
  Allows filtering quests from the journal (not useful on startup, obviously).
 
 *Improved Alternate Conversation Camera*  
  Tweak the dialogue camera. Notable settings include *Switch Target* (for Witcher-Style Dialogue Camera), *Force Third/First Person* and *Camera Offsets*.
 
 *Optimal Potion Hotkey*  
Customize *Health potion hotkey* (Default: `H`). Add a hotkey for stamina/magicka potions.

*Simplest Horses*  
 Customize *Horse Control hotkey*(Default: `V`).
  
*SmoothCam*  
By default the list uses [Adventurer's Preset](https://www.nexusmods.com/skyrimspecialedition/mods/59997).

*Survival Control Panel*  
Optionally disable *Sleep to level up*.   

*True Directional Movement*  
Customize *Target Lock* keybind here (Default `MB4`).

*Valhalla Combat*  
The core of the combat balance in the list. 
  * Stamina: The settings here have been configured for what has been determined to be the most balanced gameplay. Feel free to tweak them. 
  * Timed Block: Enable or disable the *Tackle* mechanic (Default: `Disabled`).
  
  * Compatibility: Choose whether or not to use animations from [Poise](https://www.nexusmods.com/skyrimspecialedition/mods/72653).
      - *Special Meter Control* should say `Not Obtained`. The special meter is reserved for displaying poise values.

## Updating the modlist

Before updating, please check the [changelog](https://github.com/aljoxo/ElmoRim/blob/main/ElmoRimChangelog.md) and back up any saves. A new game may be required after certain updates. To check if an update is save safe or not, refer to the version number. The first digit indicates major version, second digit indicates minor version (these are unlikely to be save safe unless otherwise specified), the third digit will represent bug fixes etc.
  - If the modlist is updated from `1.0.0` to `2.0.0`, then this version is likely a major overhaul of at least one system and **will not** be considered save safe.
  - If the modlist is updated from `1.0.0` to `1.1.0`, then this version is **not** save safe.
  - If the modlist is updated from `1.0.0` to `1.0.1`, then this version **is** save safe **unless** the changelog states otherwise. In cases where the update is save safe, performing additional steps my be needed to maintain the health of the save. These steps will be provided in the changelog.  
  

Updating is like installing the list. Simply check that file paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods added to the installation will be deleted when updating. To ensure that Wabbajack does not delete added mods upon updating, prefix the mods with **[NoDelete]**.

**ALWAYS** back up saves before an update. Because of the method Wabbajack uses to include the start save, any save within the profile will be wiped. 

*Please make sure to back up saves when continuing a playthrough across a **save safe** update.*

## FAQ 

#### Q: Why does the list claim to be vanilla when it clearly isn't.

A: No such claims are made. The list is centered around vanilla content and provides a platform for enjoying said content over a decade after it's creation.

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

## Tweaking the Game Settings

### BethINI

To get some more FPS, tweak the following value in the detail section in BethINI.

- `Shadow Resolution`: 1024
- `Grass Density`: 60
- `Remove Shadows`: I really don’t recommend turning this on, but if you must, then you can.

### ENB Settings
If you want to tweak your ENB to improve performance, consider looking at Annakin's [ENB Tips](https://github.com/The-Animonculory/Modding-Resources/blob/main/ENB%20Tips.md) guide. 

To quote her, here is a short answer to improve performance with an ENB turned on.
> - Uncheck `EnableLens`.
> - Uncheck `EnableBloom`.
> - Uncheck `EnableDepthofField`.
> - Uncheck `EnableTessellation` in `WATER`.
> - Uncheck `ComplexFireLights` and `ComplexFireLights`   
>OR  
>   - Uncheck `EnableBigRange` under each of these two settings.

To open the editor, press *F11* in-game.

## Documentation
* [Changelog](link)  
* [Modlist](link)  
* [Roadmap](link)  
## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Contact


## Credits and Thanks

- _YOU_ for reading this.
- Noggog for Mutagen and the xEdit team for xEdit and their tools.
- Halgari and the WJ Team for this amazing platform.