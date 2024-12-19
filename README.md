

![](https://raw.githubusercontent.com/ElmoDFGD/ElmoRim/main/media/ElmoRimCover.webp)
# ElmoRim

## Contents
  - [What is ElmoRim?](#What-is-ElmoRim)
  - [Feature overview](#feature-overview)
  - [Pre-installation](#pre-installation)
    - [System requirements](#system-requirements)
    - [Software setup](#software-setup)
    - [Install Creation Kit:Special Edition](#install-creation-kit-special-edition)
    - [Setting up pagefile](#setting-up-pagefile)
    - [Setting shader cache size](#setting-shader-cache-size)
  - [Installation](#installation)
    - [Wabbajack installation](#wabbajack-installation)
    - [Downloading and installing ElmoRim](#downloading-and-installing-ElmoRim)
    - [Problems with installation](#problems-with-installation)
  - [Post-installation](#post-installation)
    - [Game folder](#game-folder)
    - [Antivirus exceptions](#antivirus-exceptions)
    - [Compatibility settings](#compatibility-settings)
    - [Optional: Gamepad support](#optional-gamepad-support)
    - [Optional: Widescreen support](#optional-widescreen-support)
  - [Playing the list](#playing-the-list)
    - [Starting the game](#starting-the-game)
  - [Removing the modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Credits and thanks](#credits-and-thanks)

## What is ElmoRim?  
 
ElmoRim is for players who want to **enhance their Skyrim experience** without adding massive amounts of content or complex mechanics. A **compact and performance-friendly** list that offers **improved visuals, modernized combat**, and **increased immersion**.

This readme provides instructions for installing and configuring ElmoRim. A detailed gameplay guide, issue tracker and options for tweaking game settings can be found in the [ElmoRim wiki](https://github.com/ElmoDFGD/ElmoRim/wiki).

## Pre-installation

### System requirements

First a word about performance. [QuagaarWarrior](https://www.nexusmods.com/skyrimspecialedition/users/6411808), author of [QW's Grass Patch 2](https://www.nexusmods.com/skyrimspecialedition/mods/67785) and more, sums it up perfectly:
>I find discussions of performance a little pointless.  
...   
saying whether an individual mod is performance heavy or not is difficult because there are so many other factors at play such as the other mods you use, ENB, resolution you play at and your system specs to name just a few. 
I encourage you to try the mod and see how it performs in your individual set up.

Key phrase being **"individual set up"**.

With that said, ElmoRim has been carefully designed to offer a balance between visual quality and performance.

The list was developed on an mid tier laptop with the following specs:

|   Category      |       Specs         |    
|     :---:       |       :---:         |    
| **CPU**         | AMD Ryzen 7 5800H   |      
| **Video Card**  | Nvidia RTX 3070     |    
| **Ram**         |       16GB          |    
| **Storage**     |        SSD          |  

With these specs the game runs at 60fps@1440p.

### Software setup 
The first step of installing ElmoRim is making sure all required software is installed and that Steam is configured correctly.

1. Install [Visual C++ x64](https://aka.ms/vs/16/release/vc_redist.x64.exe) & [.Net Runtime v6 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/6.0/runtime).
2. Install Skyrim Special Edition through Steam.
3. Disable Steam [auto-updates](https://help.steampowered.com/en/faqs/view/71AB-698D-57EB-178C#disable).
4. In Steam, right click on Skyrim SE and click on *Properties*, untick `Enable Steam Overlay while in-game`.
5. Start Skyrim through Steam. Exit after loading into the main menu.
  
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

</details>

### Optional: Gamepad & Ultrawide support
ElmoRim features mods that provide gamepad & ultrawide support. Activate the corresponding mods under the **Ultrawide & Gamepad Support** separator.

## Playing the list

### Starting the game

 - Navigate to the installation folder and launch *ModOrganizer.exe*.  
  If the message *Registry Key does not match* appears, press 
  `Yes`. Once it's launched, there will be a dropdown box on the top right and a big run button next to it.
 
 - Launch the *ElmoRim* executable in MO2

### MCM configuration
Almost all of ElmoRim's MCM menus are pre-configured. This section outlines the few mandatory manual settings that are required.

#### Skyrim Unbound
ElmoRim uses [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962) as the alternate start mod.
* Open up the Skyrim Unbound MCM menu after loading in. Customize Standing Stone, whether or not the player is a vampire/werewolf, equipment, spells and starting location.
  - It is possible to choose whether or not the player is the Dragonborn and, if they are not, whether or not they are able to use shouts. 
  
* Once finished setting up the MCM, click *Start Your Adventure* under the *Main* tab to start chargen.

* Once finished with chargen, choose *Continue* to start the game.

### Congratulations, ElmoRim is now ready to go!

## Updating the modlist

Before updating, please check the [changelog](https://github.com/ElmoDFGD/ElmoRim/blob/main/ElmoRim%20DD.md) and back up any saves. A new game may be required after certain updates. To check if an update is save safe or not, refer to the version number. The first digit indicates major version, second digit indicates minor version (these are unlikely to be save safe unless otherwise specified) and the third digit will represent bug fixes etc.
  - If the modlist is updated from *1.0.0* to *2.0.0*, then this version is likely a major overhaul of at least one system and **will not** be considered save safe.
  - If the modlist is updated from *1.0.0* to *1.1.0*, then this version is save safe **unless** the changelog states otherwise.
  - If the modlist is updated from *1.0.0* to *1.0.1*, then this version **is** save safe  
  
  >In cases where the update is save safe, performing additional steps my be needed to maintain the health of the save. These steps will be provided in the changelog.  
  

Updating is like installing the list. Simply check that the file paths are the same and tick `overwrite existing modlist`. **Note**: Any mods added to the installation will be deleted when updating. To ensure that Wabbajack does not delete added mods upon updating, prefix the mods with **[NoDelete]**.

**ALWAYS back up saves before an update.**

## Removing the Modlist
Delete the ElmoRim folder.

## Contact

[ElmoRim Discord](https://discord.gg/6gGVgDYnBW)

## Credits and thanks

- _YOU_ for reading this.
- Noggog for Mutagen and the xEdit team for xEdit and their tools.
- Halgari and the WJ Team
- Aljoxo, author of [Arisen](https://github.com/aljoxo/Arisen) for letting me use Arisens README as a template.
- Maia, for teaching me Git and Markdown.