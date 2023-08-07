# Table of Contents
    
- [The Hitchhikers Guide to ElmoRim](#the-hitchhikers-guide-to-elmorim)
    - [Controls](#controls)
        - [Keyboard and mouse](#keyboard-and-mouse)
        - [Gamepad](#gamepad)
        - [Lamas Tiny HUD](#lamas-tiny-hud)
    - [Gameplay](#gameplay)
        - [ElmoRim combat](#elmorim-combat)
        - [ElmoRim Lite Needs](#elmorim-lite-needs)
        - [Gameplay mechanics](#gameplay-mechanics)
    - [What I wish I knew when I first played ElmoRim](#what-i-wish-i-knew-when-i-first-played-elmorim)
    - [Tweaking the game settings](#tweaking-the-game-settings)
        - [Resolution](#resolution)
        - [LOD](#LOD)
        - [Grass](#grass)
    - [Troubleshooting](#troubleshooting)
        - [Brute force method](#brute-force-method)    
    - [Development](#development)
        - [Known issues](#known-issues)
        - [Roadmap](#roadmap)


# The Hitchhikers Guide To ElmoRim


## Controls
The ElmoRim keyboard control scheme might seem a bit unorthodox at a glance. It is inspired by the excellent [Streamlined Skyrim](https://github.com/TerribleBrad/Streamlined-Skyrim/blob/main/README.md) modlist and offers a compact layout. While it certainly can be modified, it is recommended that users give it a try. Much thought has gone into tweaking the controls to allow quick and easy access to all necessary actions.  

### Keyboard and mouse
![Keyboard](https://raw.githubusercontent.com/ElmoDFGD/ElmoRim/1.4.0/media/keyboard-layout.jpg)  
>  Non-vanilla keybinds in blue.  
>    
> Abbreviations:  
> LTH = Lamas Tiny HUD  
> SOS = Swiftly Order Squad  
  
![Mouse](https://raw.githubusercontent.com/ElmoDFGD/ElmoRim/1.4.0/media/ElmoRim140%20Mouse.png)

  >* Hotkeys 1-4 are dedicated to managing equip sets. F1-F4 + 5-8 allows binding favorites the same way as in vanilla. Read more [below](#lamas-tiny-hud).
  >* Target lock is defined in the True Directional Movement MCM.
  >* Power attacks are configured in the One Click Power Attack MCM. Change *ForceRightKey* to the appropriate key. 
  >* Dodge key is configured in the TK Dodge RE.ini. Default key: `Spacebar`.
  >* One feature of Attack - MCO|DXP is that all non-power attacks are now performed via `LMB`. `RMB` is for blocking and casting spells equipped in the left hand.
  >* Actions in Immersive Interactions, such as petting your horse, are triggered by using the [Dynamic Activation Key](https://www.nexusmods.com/skyrimspecialedition/mods/96273) + Activate. Default: `LCtrl + E`
  >* The Wait command can only be triggered inside the Tween menu.
  >* Disclaimer: Keybinds may differ due to keyboard and mouse layout.

### Gamepad
ElmoRim features mods that support playing with a controller, [Custom Gamepad Control Map](https://www.nexusmods.com/skyrimspecialedition/mods/16057) provides a base setup for users to configure.

### Lamas Tiny Hud
The combat in ElmoRim is a lot more fast paced than vanilla Skyrim. This means a new system for smoothly switching between sets of weapons/spells/powers on the fly is needed. [Lamas Tiny Hud](https://www.nexusmods.com/skyrimspecialedition/mods/82545) is compact, responsive and easy to configure.

 > Read the modpage, experiment in-game and check out [the videos](https://www.nexusmods.com/skyrimspecialedition/mods/82545?tab=videos) provided by the author.

 > Pro tip: Support spells such as Oakflesh are excellent candidates for the top slot. This frees up space in the Left/Right slots, allowing for a better experience when switching mid-combat.

## Gameplay
ElmoRim is centered around vanilla content. As such, anyone familiar with Skyrim should be able to jump right in and start playing after reading about the mods listed below.

### ElmoRim Combat 
ElmoRim comes with all the bells and whistles in this department. 
* [Attack - MCO|DXP](https://www.skyrim-guild.com/mods/attack) creates a smooth flow by adding movement to all attack animations. 
* [Precision](https://www.nexusmods.com/skyrimspecialedition/mods/72347) provides a sense of impact by fixing hitboxes, adding weapon trails and implementing hitstop animations.
* [Valhalla Combat](https://www.nexusmods.com/skyrimspecialedition/mods/64741) overhauls Stamina management to encourage a high paced playstyle. It also features an unparallelled timed block function and and a stun/execute system.  
* [One Click Power Attack](https://www.nexusmods.com/skyrimspecialedition/mods/60878) introduces a separate key for performing power attacks, giving the player control over what happens and when. Default key: `MB4`
* [SCAR - Skyrim Combos AI Revolution](https://www.nexusmods.com/skyrimspecialedition/mods/72014) makes enemies use attacks in the same way that MCO does for the player.
* [TK Dodge RE](https://www.nexusmods.com/skyrimspecialedition/mods/56956) adds dodging. 
* [Elden Counter](https://www.nexusmods.com/skyrimspecialedition/mods/65579) Adss the ability to perform a counter attack after blocking a hit, akin to Elden Rings guard counter. Simply press the power attack button after a successful block.

### ElmoRim Lite Needs
One goal of ElmoRim is to increase immersion without adding complexity. To this end, ElmoRim comes with a unique setup for survival elements, seamlessly integrated into the general gameplay. 

#### Sleep
The mod [Incremental Injuries](https://www.nexusmods.com/skyrimspecialedition/mods/55114) introduces the need to sleep organically by reducing max Magicka/Health/Stamina as they are spent. They are restored by sleeping 6+ hours in-game. 

  >By default, ElmoRim also uses the mods [Incremental Gains](https://www.nexusmods.com/skyrimspecialedition/mods/67270) & [Hardcore Level Up - Incremental Gains Addon](https://www.nexusmods.com/skyrimspecialedition/mods/72741) which increase max Magicka/Health/Stamina by a small amount each time the player sleeps. The attributes increase proportionally to how much they were reduced before sleeping. 
  >
  >This replaces the vanilla attribute progression. Selecting an attribute upon levelling up will now only increase that attribute by one point.
  >
  >These two mods can be disabled if the vanilla system is preferred.

#### Eat/Drink
[Apothecary - Food and Drink Addon](https://www.nexusmods.com/skyrimspecialedition/mods/52130) alters food and drink to make them give long lasting, passive regeneration buffs. The buffs are balanced to incentivize eating and drinking regularly without being OP.   

#### Cold
The cold system from [The Frozen North - Minimalistic Survival Overhaul](https://www.nexusmods.com/skyrimspecialedition/mods/33068) is used to reward preparation and increase immersion. Other TFN mechanics are disabled.

#### Camping 
[Camping Lite](https://www.nexusmods.com/skyrimspecialedition/mods/2370) is a lightweight mod that provides an option for pitching a tent & lighting a fire for warmth/cooking. 

#### Carry Weight 
ElmoRim limits the player to 200 points of carry capacity. The only way to increase this limit is through perks, gear, standing stones, spells **or** crafting a [Simple Leather Backpack](https://www.nexusmods.com/skyrimspecialedition/mods/42455). Be wary though, while backpacks help fit that final piece of sliced cheese into the players inventory, they also come with a [Backpack Penalty](https://www.nexusmods.com/skyrimspecialedition/mods/57206). This penalty heavily reduces stamina regeneration in combat. *In essence, backpacks are meant to carry loot out of dungeons - not into them.*

### Gameplay mechanics

#### Experience
[Experience](https://www.nexusmods.com/skyrimspecialedition/mods/17751) changes how levelling works in Skyrim. Instead of player level being tied to skill level, experience is now earned through completing quests, discovering new locations and killing enemies.

#### Simplest Horses
The best mod for horse management in Skyrim. [Simplest Horses](https://www.nexusmods.com/skyrimspecialedition/mods/54225) gives the player the ability to have the horse follow,wait and stash items with a single button. If the crosshair is aimed at the horse, pressing the button opens the horses inventory. Otherwise it triggers the horse whistle, telling the horse to wait/follow.

#### Quest mods
ElmoRim does not bring any massive new quest mods to Skyrim. Instead the list improves vanilla quests by enhancing consistency, timing and player choices.

- [At Your Own Pace](https://www.nexusmods.com/skyrimspecialedition/mods/52704) improves the pacing of the game by delaying quest progression until certain conditions are met. The conditions can be tweaked in the MCM.

- [Skyrim Unbound](https://www.nexusmods.com/skyrimspecialedition/mods/27962) is an alternate start mod that allows the player to choose starting gear, spells and location along with many other options.

- [JaySerpa](https://www.nexusmods.com/skyrimspecialedition/users/5201727) has built a suite of mods that expand and improve quests that are somewhat lackluster in vanilla. This is done in a simple, immersive and unintrusive manner.
## What I wish I knew when I first played ElmoRim
***GET OP EARLY ESSENTIAL BEGINNERS TIPS ONE SHOT GUIDE***

In all seriousness, ElmoRim plays pretty close to vanilla and this wiki accounts for any notable differences. However it always helps to have a plan when starting a new playthrough.

 1. Craft a Camping Kit ASAP.
* 2 x Iron Ingot
* 6 x Leather
* 12 x Leather Strips
* Craft at any forge

2. The manual for crafting Backpacks can be found outside the Drunken Huntsman in Whiterun.  
   
3. Bring a Woodcutter's Axe & gear suitable for cold weather.

4. Buy a horse - they are good for traversing the landscape and can carry a good bit of loot.

5. Don't loot everything in sight - carry weight is limited.

6. Quick Light is useful - use it.

8. Vampires assaulting the Dawnguard base should bring a bow.

9. Enemies with a gray stamina bar can easily be staggered while they are blocking.

10. Don't try and tackle vampire lairs at level one. Check the [Arena](https://www.nexusmods.com/skyrimspecialedition/mods/33487) modpage to get a sense of approriate levels for different dungeons/quests.

11. Skyrim is a troubled place - [Sidequests Of Skyrim](https://www.nexusmods.com/skyrimspecialedition/mods/54245?tab=description) let's the player ask anyone if they need help.

12. [Dragon Claws Auto-Unlock](https://www.nexusmods.com/skyrimspecialedition/mods/47329) all puzzle doors. Just activate the keyhole while carrying its matching claw.

## Tweaking the game settings

### Resolution
The best AA in Skyrim is higher resolution. If the game runs smoothly at 1080p@60FPS, increasing the resolution is an option. This is done in *SSEDisplayTweaks.ini* in the mod *SSE Display Tweaks - High Performance Configuration*.
- `Resolution`: Change to 2560x1440

### LOD
By default, ElmoRim ships with an LOD based on the *High* settings profile in DynDOLOD. This is a massive improvement over vanilla LOD, both in terms of visual consistency as well as quality. Users looking to increase FPS can [generate](https://www.youtube.com/watch?v=encZYHEeQrQ) new LODs with *medium* or *low* settings.
> DyndDOLOD sometimes breaks the map mods. If the map is purple after generating new LODs, reinstall all paper map mods.

### Grass
 Users who want to completly tank their FPS can generate LODs with distant grass. To generate grass LOD, follow these [instructions](https://dyndolod.info/Help/Grass-LOD). ElmoRim comes with a grass cache already set up. 
 Those looking to improve performance can make the following changes to *Grasscontrol.config.txt* in the mod *No Grass In Objects*:
- `UseGrassCache`: Set to false
- `ExtendGrassDistance`: Set to false
- `OnlyLoadFromCache`: Set to false
- `DynDOLODGrassMode`: Set to 0

## Troubleshooting
If an error/weird behavior/poor performance is encountered that can't be reproduced by other users on the ElmoRim discord, check the following:

* Launch Skyrim via Steam to ensure the base game runs OK.
* Double check that all installation instructions were followed correctly. 9 out of 10 errors are caused by missing a step.
* Something was corrupted during the WJ installation. Reinstall the list.
* If all else fails, use the Brute force method below.
### Brute force method
All user setups are different, sometimes certain mods simply don't play nice for some users. To identify what mods are causing issues, perform the following steps:
1. Create a new profile in MO2
2. Disable all mods **EXCEPT Skyrim Textures Upscaled - Complete Vanilla Upgrade**
3. Run a Clear-command via the Root Builder plugin  
![RootClear](https://github.com/ElmoDFGD/ElmoRim/blob/main/media/RootClear.png?raw=true) 
4. Empty the MO2 Overwrite folder
5. Launch the ElmoRim executable
6. If the game still crashes then this error is unrelated to ElmoRim and no further support will be offered.
7. If the game launches:  Enable all mods one separator at a time
8. Run a Build command
9. Sync all plugins via the Sync Plugins plugin
10. Rinse and repeat until the game crashes. 
11. Disable half of the mods under the separator>Launch>Repeat until the culprit is found.
12. Switch back to the ElmoRim profile>Disable the problematic mod>Launch.
13. Repeat steps 7-12 until all problematic mods have been found.  

## Development
### Known Issues
Everything is tracked using the GitHub [Issue Tracker](https://github.com/ElmoDFGD/ElmoRim/issues). Check this page before reporting any suspected bugs. If the issue in question isn't listed, feel free to register a new one.

### Roadmap
ElmoRim is considered feature complete. Any updates will be aimed at fixing bugs, improving on existing gameplay/combat mechanics and reducing complexity.

* Xavbio's retextures
* Make the list as lean as possible



