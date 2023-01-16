

![](https://raw.githubusercontent.com/ElmoDFGD/ElmoRim/main/media/ElmoRimCover.webp)
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
    - [Users with a 10-series Nvidia card or lower: Disable DLAA](#users-with-a-10-series-nvidia-card-or-lower-disable-dlaa)
    - [Compatibility Settings](#compatibility-settings)
    - [Optional: Resolution settings](#optional-resolution-settings)
    - [Optional Widescreen & gamepad support](#optional-widescreen--gamepad-support)
  - [Playing the List](#playing-the-list)
    - [Starting the Game](#starting-the-game)
    - [MCM Configuration](#mcm-configuration)
  - [FAQ](#faq)
    - [Q: This isn't vanilla!?](#q-why-does-the-list-claim-to-be-vanilla-when-it-clearly-isnt)
    - [Q: BUG!](#q-bug)
    - [Q: Why do all daedra sound like they're on *Insert Illicit Substance*?](#q-why-do-all-daedra-sound-like-theyre-on-insert-illicit-substance)
    - [Q: I can't level up, what do I do?](#q-i-cant-level-up-what-do-i-do)
    - [Q: How do I start the main questline?](#q-how-do-i-start-the-main-questline)
    - [Q: When do dragons start spawning?](#q-when-do-dragons-start-spawning)
    - [Q: How do I become the Thane of Whiterun? How do I get Lydia?](#q-how-do-i-become-the-thane-of-whiterun-how-do-i-get-lydia)
    - [Q: How do I enable my crosshair?](#q-how-do-i-enable-my-crosshair)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and Thanks](#credits-and-thanks)
 
## What is ElmoRim?  

ElmoRim is for players who want to **enhance their Skyrim experience** without adding massive amounts of content or complex mechanics. A **compact and performance-friendly** list that offers **improved visuals, modernized combat**, and **increased immersion**. NO CC-MODS REQUIRED.

This readme provides instructions for installing and configuring ElmoRim. A detailed gameplay guide, issue tracker and options for tweaking game settings can be found in the [ElmoRim wiki](https://github.com/ElmoDFGD/ElmoRim/wiki).

> Disclaimer: ElmoRim puts vanilla content at center stage. However, it is first and foremost Skyrim the way I, Elmo, want it. So if a certain mod is included, it is because I want it there.

## Feature overview
ElmoRim consists of around 600 mods. This overview provides an idea of what to expect from the list.
|    Feature    |                                     Core Mods                                             |  
|     :---:     |                                      :---:                                                |  
| **Visuals**   | Skyland AIO, Modular Armory, Sswaye's "Cabbage" Reshade                                   |    
| **Combat**    | MCO, Valhalla, Precision, Valravn, Hand Placed Enemies                                    |  
| **Gameplay**  | SimonRim, Experience, ElmoRim Lite Needs*                                                 |  
| **Quests**    | Skyrim Unbound, JaySerpa's Quest Expansion-series, At Your Own Pace, College For Non-Mages|  
| **Immersion** | Immersive interactions, EVG Animated Traversal, Animated Eating Redux                     |  
| **Audio**     | AOS, ISC, Regional Sounds Expansion, Yet Another Music Merge                              |  
|   **UI**      | Untarnished UI, BTPS, Lamas Tiny HUD                                                      |  
| **New lands** |                                       Nope                                                |  
|**Followers**  |                                       Nope                                                |  
| **NSFW**      |                                       Nope                                                |  

>*Not a mod but a combination of features from several mods. Read the [wiki](https://github.com/ElmoDFGD/ElmoRim/wiki/Welcome-to-the-ElmoRim-wiki#gameplay) to find out more.

## Pre-installation

### System requirements

First a word about performance. [QuagaarWarrior](https://www.nexusmods.com/skyrimspecialedition/users/6411808), author of [QW's Grass Patch 2](https://www.nexusmods.com/skyrimspecialedition/mods/67785) and more, sums it up perfectly:
>I find discussions of performance a little pointless.  
...   
saying whether an individual mod is performance heavy or not is difficult because there are so many other factors at play such as the other mods you use, ENB, resolution you play at and your system specs to name just a few. 
I encourage you to try the mod and see how it performs in your individual set up.

Key phrase being **"individual set up"**.

With that said, ElmoRim has been carefully designed to offer a balance between visual quality and performance.

The list was developed on an upper-mid tier laptop with the following specs:

|   Category      |       Specs         |    
|     :---:       |       :---:         |    
| **CPU**         | AMD Ryzen 7 5800H   |      
| **Video Card**  | Nvidia RTX 3070     |    
| **Ram**         |       16GB          |    
| **Storage**     |        SSD          |  

With these specs the game runs at 60fps@1440p.
> ElmoRim uses the [Skyrim Upscaler](https://www.nexusmods.com/skyrimspecialedition/mods/80343). This feature requires an RTX 20-series card or higher. Users with [potato](#users-with-a-10-series-nvidia-card-or-lower-disable-dlaa) cards need to use TAA instead. 

Recommendations on how to tweak the balance between visual quality and performance are provided [in the wiki](https://github.com/ElmoDFGD/ElmoRim/wiki/Welcome-to-the-ElmoRim-wiki#tweaking-the-game-settings).

Modlist size: 127 GB (of which 46 GB are downloads)

### Software setup 
The first step of installing ElmoRim is making sure all required software is installed and that Steam is configured correctly.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
2. Install Skyrim Special Edition through Steam.
3. Install [Skyrim Special Edition: Creation Kit](https://store.steampowered.com/app/1946180/Skyrim_Special_Edition_Creation_Kit/) through Steam. 
4. Disable Steam [auto-updates](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
5. In Steam, right click on Skyrim SE and click on *Properties*, untick `Enable Steam Overlay while in-game`.
6. Start Skyrim through Steam. Exit after loading into the main menu.
> Make sure to install the correct version of the Creation Kit. It should be named exactly as the link in step 2!
  
### Setting up pagefile

Due to the resources required to run modlists like these, the system pagefile needs to be configured in order to avoid crashes and bugs that may occur from running out of memory.

  ***A 40GB fixed-size pagefile for ElmoRim is recommended.***

To set up the pagefile, complete the following steps:

<details>
<summary><strong>Click to see required steps</strong></summary>  

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

</details>

### Setting shader cache size
 Users with an NVIDIA GeForce Graphics Card need to complete the following steps: 

<details>
<summary><strong>Click to see required steps</strong></summary>  

 1. Right-click on the desktop and select **NVIDIA Control Panel**
 2. Navigate and click on **Manage 3D settings**. It is the 2nd one to the top.
 3. Scroll down in Global Settings to **Shader Cache Size**
 4. Double Click **Driver Default** to the right of Shader Cache Size and select **10 GB**
 5. Click **Apply** in the bottom right hand corner. 
 6. Exit the application.


![](https://raw.githubusercontent.com/iAmMe27/Tahrovin/main/img/ShaderCache.png)

</details>

## Installation


### Wabbajack installation

Once pre-installation is completed, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Wabbajack`. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.) or in Skyrim's Steam folder**. Placing it on an SSD will speed up the installation process.

### Downloading and installing ElmoRim

Installing ElmoRim is a straightforward process. A Nexus Premium account is strongly advised. Download and installation can take a while depending on internet connection and computer specs. To install ElmoRim, complete the following steps.

>Wabbajack automatically [downgrades](https://www.nexusmods.com/skyrimspecialedition/mods/57618) the Skyrim installation version 1.5.97. **Do not** downgrade the steam install or the modlist manually.

1. Open Wabbajack and click `Browse Modlists`.
2. Tick the `Show Unofficial lists` option in the top right corner of Wabbajack.
3. Press the download button on ElmoRim and wait for it to download.
4. Set the installation folder to be somewhere like C:\Games\ElmoRim. **DO NOT place it in Program Files, User folders (such as Desktop, Documents, Downloads, etc.), or in Skyrim's Steam folder**
> The download location does not need to be on a SSD, but it makes installation go a lot faster.
5. Press the play button to begin.
7. If the installation is successful, prosper, and move onto [Post-installation](#post-installation). If the installation is unsuccessful, follow what is below.


### Problems with installation

It is possible to encounter errors when installing with Wabbajack. 

<details>
  <summary><strong>Click here to see common issues</strong></summary>  

- Could not download x:
	- Big files can fail to download due to connection issues. Either run wabbajack again or download the file manually. If downloading manually, make sure to place it in the same folder as the other downloads.

- **X** is not a whitelisted download:

	 - This may happen when the modlist is being updated. Please check if there is a new update or wait for a release ping.

- Wabbajack could not find the game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- Windows 10/11 may automatically quarantine a key file which is needed for Mod Organizer. You can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

  </details> 

## Post-installation

### Game folder

ElmoRim uses a Wabbajack feature called *Stock Game* to keep the Skyrim installation folder clean. All the files needed to run the list are in a folder called *Game Root*. No manual copying of files is required.

### Antivirus exceptions

Generally speaking, using Windows Defender is advised as it is a solid antivirus software that will have minimal interference with the game. Antivirus programs can be notorious for false flagging MO2's VFS as problematic, causing crashes or other problems. 

If using Windows Defender, it is advised to set up an Exception for the modlist. To do this, complete the following steps:

<details>
  <summary><strong>Click here to see required steps</strong></summary>  
 1. Press the Windows Key.
 
 2. Type "Windows Defender" in the search bar and select *Windows Security*.
 
 3. Click `Virus & threat protection` in the left pane.
 
 4. Click the `Manage settings` option under *Virus & threat protection settings*.
 
 5. Scroll down to *Exclusions* and click `Add or remove exclusions`.
 
 6. Windows Defender will prompt with a run as administrator screen, select `Yes`.
 
 7. Click the `Add an exclusion` button at the top and choose *Folder*.
 
 8. Navigate to your Install folder for the list and click `Select Folder`.
 
 9. **(OPTIONAL)** Repeat these steps for the ModOrganizer.exe ("Path to Modlist"\ModOrganizer.exe), the Nemesis Executable ("Path to Modlist"\mods\Project New Reign - Nemesis Unlimited Behavior Engine\Nemesis_Engine\Nemesis Unlimited Behavior Engine.exe), and Synthesis ("Path to Modlist"\tools\Synthesis\Synthesis.exe)

</details>

 ### Compatibility settings
 Nemesis, xLODGen and DynDOLOD have a tendency to fail even when added to virus exceptions. To avoid this issue, complete the following steps:

 <details>
  <summary><strong>Click here to see required steps</strong></summary> 

 1. Navigate to the Nemesis Executable.
 
 2. Right click on the Nemesis Executable, select *Properties*.
 
 3. Go to the *Compatibility* tab.
 
 4. Under the *Compatibility mode* section, check `Run this program in compatibility mode for:` and select  
  *Windows 8* from the dropdown menu. 
 
 5. Click `Apply` and then `OK`.
 
 6. Repeat steps 1-5 for xLODGenx64.exe and DynDOLODx64.exe (These are located in "Path to Modlist"\tools..)

 </details>


 ### Users with a 10-series Nvidia card or lower: Disable DLSS

 Users who do **not** have a RTX 20-series or higher card need to rely on Skyrims native antialiasing. Perform the following steps:

<details>
  <summary><strong>Click here to see required steps</strong></summary> 

- Disable the mods *UpscalerBasePlugin* and *Skyrim Upscaler* under the Framework-separator.
- Open BethINI.
- Under *Basic>Antialiasing*: Choose *TAA*.
- Press `Save and Exit`.
</details>

>Users with non-Nvidia cards need to use the XeSS or FSR2 upscaling method instead. Press `End` to open up the upscaler GUI and use the *Upscale Type* dropdown.

### Optional: Widescreen & gamepad support

ElmoRim features mods that provide widescreen & gamepad support. Activate the mods under the **Ultrawide & Gamepad Support** separator and complete the following steps:
<details>
<summary><strong>Click here to see required steps</strong></summary>

From [Untarnished UIs](https://www.nexusmods.com/skyrimspecialedition/mods/75188) modpage:

>
>"Most menus have native ultrawide support, thanks to Dear Diary Dark Mode. However, you will need to position some of the elements from SkyHUD and TrueHUD manually.
>
>SkyHUD (located in Data/interface/skyhud/skyhud.txt) (requires a restart)
fMessageInfoPosX (right-aligned, increase).
>
>TrueHUD (located in the MCM)
>Player Widget Anchor X (left-aligned, decrease).
>Recent Loot Anchor X (right-aligned, increase).
>
>21:9 configurations
>* fMessageInfoPosX=1030
>* Player Widget Anchor X = -0.155
>* Player Loot Anchor X = 1.17"
>


From [Lamas Tiny HUD]
>"Position of Image Width" and "Position of Image Height" moves the whole HUD
2560x1440 should be around 2425 and 1250 (position I have in the Videos)
Config default values are 140 and 140.
1920x1080 the right Bottom should be something like at 1780-1.785 and 890-940
</details>

## Playing the list

### Starting the game

 - Navigate to the installation folder and launch *ModOrganizer.exe*.  
  If the message *Registry Key does not match* appears, press 
  `Yes`. Once it's launched, there will be a dropdown box on the top right and a big run button next to it.
 
 - Launch the *ElmoRim* executable in MO2

### MCM configuration
Almost all of ElmoRim's MCM menus are pre-configured. This section outlines the few mandatory manual tweaks that are required.

#### Skyrim Unbound
ElmoRim uses [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962) as the alternate start mod.
* Open up the Skyrim Unbound MCM menu after loading in. Customize Standing Stone, whether or not the player is a vampire/werewolf, equipment, spells and starting location.
  - It is possible to choose whether or not the player is the Dragonborn and, if they are not, whether or not they are able to use shouts. 
  
* Once finished setting up the MCM, click *Start Your Adventure* under the *Main* tab to start chargen.
  - If the player character is frozen in RaceMenu, swap race or gender and swap back to unfreeze them. This is an issue with DAR Cacheing.


* Once finished with chargen, choose *Continue* to start the game.

#### Valravn
Disable (or set to 0) everything except *Attacks of Opportunity* and *Bow Stamina Cost*.


#### Optional MCM Settings
In addition to the mandatory settings, several optional tweaks are available:

<details>
  <summary><strong>Click here to see optional MCM Tweaks</strong></summary>


##### AYOP - College of Winterhold
Non-mages looking to access Saarthal and the Archmages quarters should make the following changes:
- Starting Requirements>First Lessons: Set to 0
- Starting Requirements>Under Saarthal: Set to 0

##### SunHelm 
Disable powers under *General>Enable/Disable powers*. Only Sunhelms Cold system is enabled as part of the ElmoRim Lite Survival setup. 

##### Elden Equip
Set up hotkeys to manage cycles for spells/shouts/weapons. See [modpage](https://www.nexusmods.com/skyrimspecialedition/mods/74220) for details.

##### Incremental Gains
Set *Soft Cap Base* to 125.

##### Skyrim Unbound  
Dragons are set to appear after 7 to 21 days by default. They will appear at word walls before appearing in the wild. They can be configured to spawn faster/slower/instantly or spawn based on level instead.
 
##### Better Third Person Selection
Enable/disable the filters that prevent the player from accidentally stealing items when trying to interact with the world.
 
##### Favourite Howls Menu  
Customize which powers will be in the favorites menu (for werewolves).
 
##### Improved Alternate Conversation Camera
Tweak the dialogue camera. Notable settings include *Switch Target* (for Witcher-Style Dialogue Camera), *Force Third/First Person* and *Camera Offsets*.
 
##### Optimal Potion Hotkey
Customize *Health potion hotkey* (Default: `H`). Add a hotkey for stamina/magicka potions.

##### Simplest Horses
Customize *Horse Control hotkey*(Default: `V`).

##### Sidequests Of Skyrim
Configure available quests. Set quest chance. Limit questgivers to unique NPC's.

>The ingredient/shopping quests can be rather tedious and are disabled by default.
  
##### SmoothCam
By default the list uses [Adventurer's Preset](https://www.nexusmods.com/skyrimspecialedition/mods/59997). Feel free to download and install other presets.

##### Survival Control Panel
Enable/disable *Sleep to level up*.   

##### True Directional Movement  
Customize *Target Lock* keybind here (Default `MB4`).

##### XPMSSE
Customize equipment slots, such as placing one-handed swords on the players back. 

##### Valhalla Combat
  * Stamina: The settings here have been configured for what has been determined to be the most balanced gameplay. Feel free to tweak them. 
  * Timed Block: Enable or disable the *Tackle* mechanic (Default: `Disabled`).

</details>


### Congratulations, ElmoRim is now ready to go! Check out the [wiki](https://github.com/ElmoDFGD/ElmoRim/wiki/Welcome-to-the-ElmoRim-wiki) for a detailed gameplay guide, beginner tips and customization options.

## Updating the modlist

Before updating, please check the [changelog](https://github.com/ElmoDFGD/ElmoRim/blob/main/ElmoRim%20DD.md) and back up any saves. A new game may be required after certain updates. To check if an update is save safe or not, refer to the version number. The first digit indicates major version, second digit indicates minor version (these are unlikely to be save safe unless otherwise specified) and the third digit will represent bug fixes etc.
  - If the modlist is updated from *1.0.0* to *2.0.0*, then this version is likely a major overhaul of at least one system and **will not** be considered save safe.
  - If the modlist is updated from *1.0.0* to *1.1.0*, then this version is save safe **unless** the changelog states otherwise.
  - If the modlist is updated from *1.0.0* to *1.0.1*, then this version **is** save safe  
  
  >In cases where the update is save safe, performing additional steps my be needed to maintain the health of the save. These steps will be provided in the changelog.  
  

Updating is like installing the list. Simply check that the file paths are the same and tick `overwrite existing modlist`. **Note**: Any mods added to the installation will be deleted when updating. To ensure that Wabbajack does not delete added mods upon updating, prefix the mods with **[NoDelete]**.

**ALWAYS back up saves before an update.**

## FAQ 

#### Q: I get CTD when starting the game

A: You have a [potato](#users-with-a-10-series-nvidia-card-or-lower-disable-dlaa) graphics card. Follow the link for instructions on how to fix this.

#### Q: This isn't vanilla?!

A: Indeed not. It is about experiencing vanilla content in 2023.

#### Q: BUG!

A: If a suspected bug or weird behavior is encountered, check the [issue tracker](https://github.com/ElmoDFGD/ElmoRim/issues). If the issue isn't listed there, please register a new one.

#### Q: Why do all daedra sound like they're on *Insert Illicit Substance*?

A: One of the most daunting things about starting a new playthrough is the prospect of having to listen to all the unskippable dialogue in the daedric quests. The mod [Speedy Daedric Dialogue](https://www.nexusmods.com/skyrimspecialedition/mods/32459) alleviates this by making all dialogue play at 2x speed. To revert to vanilla, simply disable the mod.

#### Q: I can't level up, what do I do?  
A: You have Sleep to level up enabled, go sleep in a bed or disable it through Survival Control Panel in the MCM.

#### Q: How do I start the main questline?  
A: If you have chosen to be Dragonborn in the Skyrim Unbound MCM settings, then upon killing your first dragon, you will be summoned by the Greybeards. If you have chosen to NOT be the Dragonborn, then you can not proceed with the main questline.

#### Q: When do dragons start spawning?  
A: By default, dragons are set to be delayed in their spawns from 7 to 21 days after you leave the starting room. By default, dragons will begin showing up at their Word Walls before you will encounter them in the wild.

#### Q: How do I become the Thane of Whiterun? How do I get Lydia?  
A: You must complete [The Blessings of Nature](https://en.uesp.net/wiki/Skyrim:The_Blessings_of_Nature) and talk to Jarl Balgruuf when the Gildergreen tree is repaired/the sappling blooms. He'll thank you and allow you to buy the Breezehome after which the standard thaneship quest (help people of the hold and buy a house to become a thane) will be available.

#### Q: How do I enable my crosshair?
A: Disable the [Contextual Crosshair](https://www.nexusmods.com/skyrimspecialedition/mods/63980) mod, under the *Interface* separator in MO2.

## Removing the Modlist
Delete the ElmoRim folder.

## Contact

[ElmoRim Discord](https://discord.gg/6gGVgDYnBW)

## Credits and thanks

- _YOU_ for reading this.
- Noggog for Mutagen and the xEdit team for xEdit and their tools.
- Halgari and the WJ Team for this amazing platform.
- Aljoxo, author of [Arisen](https://github.com/aljoxo/Arisen) for letting me use Arisens README as a template.
- Phoenix, author of [The Phoenix Flavour](https://thephoenixflavour.com/) for letting me use the Appearance setup from [LotF](https://thephoenixflavour.com/skyrim-se/lotf/introduction/).
- Maia, for teaching me Git and Markdown.
