# ElmoRim Wabbajack Dev-Diary
## backlog
## Version update checklist
1. Re-compile w/ new version number
2. Upload new file to CDN
3. Update modlists.json w/ jsonlint + new link
4. pray  

## Update message
* Switched back to Wander for a simpler weather setup. The new Wander HDR does wonders.
* Updated Mo2 and plugins.
* Reinstalled arctic to fix visual bug. Credit to Dex!
* Fixed double poison crash. Credit to haho123!
* New fancy widgets by switching to STB Widgets.
* Cleaned up wiki and readme.

Save safe.


## Changelog
---2.3.0---  
* Edge UI
---2.2.0--- 
* Quests: Jayserpa, cult of worldeater, defeat dragon cult 
* test cult of worldeater, AYOP & defeat dragon cult
* Bounty quests redone
* movesets: vampire, werewolf, unarmed, katana
* Werewolf encounters + canis
---2.1.1---
*added*  
* Wander & Wander HDR
* FOMOD plus MO2 plugin
* STB Widgets

*removed*  
* NAT.CS and related mods
* Edryu's widget and dependencies

*updated*  
* Reinstalled arctic to fix visual bug. Credit to Dex!
* Updated Community Shaders and features
* Set SSGI quality to low in CS to improve performance
* Set poison=false in yesimsure.toml to fix poison crash.
* updated MO2
* updated bsplugins.dll with Aglowinthefields recompiled version and added link to source on githhub to comply with GPLv3


---2.1.0---  
*added*  
Terrain Shadows - Heightmaps  
Terrain Shadows  
Screen Space Global Illumination (SSGI)  
Cloud Shadows  
Skylighting  
Vibrant Weapons EAE - Enchantment Lights  
PG Patcher  
Better Dynamic Snow SE  
Better Dynamic Ash SE  
Happy Little Trees - Better Dynamic Ash Patch  
Skyland PBR  
Light Placer  
CS Lights  
Placed Light  
Embers XD Patched meshes for Light Placer  
NAT.ENB - ESP WEATHER PLUGIN v3.1.1C - Fixed  
NAT.CS III  
Mists of Tamriel  
Mists of Tamriel NAT III patch  
Mist of Tamriel - NAT CS Patch  
[O] PG Patcher Output  

*removed*  
Shadow Boost  
TAA Sharpen  
Grass Sampler Fix  
Simplicity of Snow  
Simplicity of Snow - Parallax Meshes  
Skyland Landscapes Complex Parallax  
Soft Shadows  
[R] Reshade Shaders & dll  
SSE ReShade Helper  
Auto Parallax  
Tree LOD Lighting  
Vanilla HDR  
Light Limit Fix - Candle Glow  
Water Parallax  
Water Caustics  
Sky Reflection Fix  
Dynamic Cubemaps  
Dynamic Cubemaps - Metals  
Vende's The Most Unimpressive Reshade Presets - Azurite Weathers II  
ENB Lights For Effect Shaders  
Misc Effects ENB Light  
LLF Particle Lights instead of Fake Glow - Embers XD Static Flame Fix  
Extra Particle Lights Pack - No Meshes (LLF)  
Realistic Skin And Hair Shaders - Giants  
Realistic Skin Shaders - Falmer and Hagravens  
Azurite Weathers II  
Azurite Mists  
Standard Lighting Templates  
Some Standard Lighting Templates patches - Saints and Seducers Extended Cut  
Water blending  

*updated* 
Po3 Tweaks  
Community Shaders  
Grass Lighting  
Grass Collision  
Screen-Space Shadows  
Light Limit Fix  
Subsurface Scattering  
Wetness Effects  
Water Effects  
SkyPatcher  
Synthesis  

*config*  
Reinstalled embers xd to comply with placed lights  
set fSkyCellRefFadeDistance=655360.0000 in skyrimprefs.ini according to Mists of Tamriel  
Removed standard lighting templates patch  


---2.0.2---
* Fixed Pandora output path
* Disabled Precision weapon capsules
---2.0.1---  
* Set gamepad mods to *Always enabled* in compiler
---2.0.0e---
*Balance & fixes*
* Tidied up mod version/update management
* Restored hotkey 1-9 functionality in controlmap.txt
* Enabled reduced player poise damage in chocolate poise to fit with heavy armor perks
* Timed blocks with a shield now properly give bonus xp
* Max magicka now decreases faster upon magicka expenditure (Incremental Injuries). The purpose is to increase the magicka stat faster (Incremental Gains).
*mod changes*
* Updated powerofthree's Papyrus Extender
* Updated Unofficial Skyrim Special Edition Patch - USSEP
* Updated powerofthree's Tweaks
* Upated CrashLogger
* Updated Open Animation Replacer
* Updated Spell Perk Item Distributor
* Updated SkyPatcher 
* Updated FormList Manipulator
* Updated Keyword Item Distributor
* Updated More Informative Console
* Updated Better Third Person Selection - BTPS
* Updated Clutter Filter for BTPS
* Updated Infinity UI
* Updated Compass Navigation Overhaul
* Updated OxygenMeter2
* Updated HD Local Map
* Updated Simpler Knock (and leaflet patch) 
* Updated Particle Patch
* Updated Static Mesh Improvement Mod Improvement Mod
* Updated Simplicity of Snow
* Updated Simplicity of Snow - Parallax meshes
* Updated Happy Little Trees
* Updated Missile's IED Preset  
* Updated Bloodskal Blade - Tweaks and Enhancements
* Updated Happy Little Trees Add-On - DynDOLOD 3   
* Updated Skyland Bits and Bobs - A Clutter Overhaul
* Updated ENB Lights For Effect Shaders
* Updated Embers XD
* Updated Vibrant Weapons EAE
* Updated Faster HDT-SMP
* Updated Adamant - A Perk Overhaul
* Updated Mysticism - A Magic Overhaul
* Updated Mundus - A Standing Stone Overhaul
* Updated Artificer - Xavbio Textures Addon
* Updated Run For Your Lives
* Updated Detection Meter
* Updated Misc Dialogue Edits
* Updated Experience
* Updated Incremental Gains
* Updated aljo's Artificer Patches
* Updated Skyrim Unbound Reborn
* Updated EVG Conditional Idles
* Updated Modern Combat AI
* Updated Precision Creatures
* Added Vanilla Hair Remake
* Added Vanilla hair remake SMP - NPCs
* Added the _ResourcePack because USSEP now requires it
* Added Azurite Mists
* Added Azurite Weathers II
* Added Simpler Knock - USSEP Patch
* Added Artificer - USSEP
* Added Edryu's Widget
* Added IWant Widgets NG
* Added IWant Widgets
* Added Open World Loot - Encounter Zone and Loot Overhaul
* Added OWL Randomized Special Loot
* Added Animals Report No Crime - SkyPatcher
* Added Torch Bash Ignites Traps
* Added True Directional Movement Lock-On Fixes
* Added Skyrim De-bearer
* Added sneak Alarm Time Tweak SE
* Added Immersive Sounds - Compendium
* Added Immersive Sounds Compendium - Sound Record Distributor...ded
* Added Audio Overhaul Skyrim - Immersive Sounds Compendium Integration
* Added Nordic Faces - FaceGen - BSA
* Added Nordic Faces
* Added SUEMR No Beast Race Glow SSE
* Added High Poly Vanilla Body
* Added Faithful Faces - Creation Club NPC Overhaul
* Added Expressive Facial Animation -Male Edition-
* Added Expressive Facial Animation -Female Edition-
* Added Closed Mouths for Orcs FOMOD
* Added ADXP MCO Attack Data Transition Fix (ADTF)
* Added Pandora Output
* Added TK Dodge Animation Pandora Fix Patch
* Added TK Dodge NG
* Added TK Dodge RE Pandora
* Added Pandora Behaviour Engine Plus
* Added EVG Conditional Idles - Settings Loader
* Added Unarmed Weapon Speed Scaling
* Added Autosave After Combat
* Added Untarnished UI - Unsquished Fix - C.O.C.K.S
* Added C.O.C.K.S. for Skyrim 1.5
* Added Constructible Object Custom Keyword System
* Removed SoulsyHUD
* Removed SoulsyHUD icon pack
* Removed Keyword Patch Collection
* Removed Object Categorization Framework
* Removed Wheeler - Quick Action Wheel Of Skyrim
* Removed Wheeler - Untarnished UI Edit
* Removed Kill Caps Lock NG
* Removed Vanilla Hair Fixes
* Removed Natural Hair Colors
* Removed [E] ElmoRim Experience Preset
* Removed Wander - A Weather Mod
* Removed True Storms Special Edition - Thunder Rain and Weather Redone
* Removed True Storms Special Edition - No Fog
* Removed dMenu
* Removed Open World Loot - SkyPatched by SICreef
* Removed [E] Adamant - Poise Integration. Replaced with Chocolate poise patch in [E] ElmoRim Patches
* Removed Open World Loot - SkyPatched by SICreef
* Removed OWL - SkyPatched Test Update
* Reinstalled Extra Particle Lights Pack - No Meshes (LLF) to avoid redundant files due to Embers XD incompatibility
*Tools*
* Added Experience Synthesis patcher
* Added Quests are in Skyrim Synthesis patcher
* Updated xEdit
* Updated Bethini
* Reran Bethini w/ shadow resolution 1024. 64bit render disabled and grass density 60
* Removed Curation Club
* Added Creation Organizer
* Swapped from Nemesis to Pandora

---2.0.0d---
*balance & fixes*  
* tweaked rotation mults for TDM for smoother combat feel
* Bumped up bonus per book to 50% for Reading is Good
* Swapped greatsword sprint attack animation to warhammer/battleaxe due to timing issue were attacking too quickly after a sprint power attack would mean npc didn't get hit by follow up attacks.
*mod changes*   
* Added Stamina of Shooting - drawing bow costs stamina
* Swapped Loki poise for chocolate poise due to better creature compatibility and smoother regen system.
* Added Bloodskal Blade - Tweaks and Enhancements to fix (somewhat) Bloodskal/MCO incompatibility.
* Added SB - Better Blending Helgen Mud
* Added Skip Time Wound Scene
* Added Simplicity of Seeding
* Added LeveledList Crash Fix
* Added LeveledList Crash Fix for Skyrim 1.5
* Added Alchemy XP Fix
* Fixed dependencies for [E] Easier harder quests
* Removed some quest mods to be added in later update
* Removed Skyvalor and related mods
* Removed My Minimalistic Autosave Mod, will use game autosaves instead
* Removed Enemy Magelock
* Removed TK Dodge RE (Shorter step dodge). Thank you nomad for bringing this to my attention!
* Removed Sekiro Combat S - Poise Compatibility Patch
* Removed [E] AOS - EBT - Dynamic Impact Patch. Letting DI win all conflicts because works well and can't be bothered to patch
* Swapped to new Oxygen Meter 2 UI patch
---2.0.0c---  
*fixes*
* Improved performance by hiding SmokeParticles01.ini in Extra Particle Lights Pack - No Meshes (LLF)
* Finally remembered to turn off Precision debug before uploading
* Better targeting by tweaking attack rotation mults in TDM
* Fixed sprint attack transitions(!!!) by adding ADXP 1.6.0.6 Bug fix (Unfortunately not compatible with Smooth Input but I prefer this for consistency)
* Left hand sheaths by adding IEDmesh synthesis patcher
* Hid skyhud charge meter to avoid duplicate function with SoulsyHUD

*mod changes*
* Added Enhanced Blood Textures LITE
* Added Less Blinding Deflickered Light Spells Mysticism
* Added Armor Rating Recalculator - SkyPatcher - Basic
* Added OCPA and MCO bugfixes
* Added Splashes Of Storms because it is neat
* Added CFTO
* Added Immersive patrols
* Removed [E] No directional power attacks

---2.0.0b---  
*fixes*  
* sword light sprint attack window by using different animation
* Killmove bug by switching to nemesis
* freeze on cell change by switching to load screen truce  
* Sprint power attacks inconsistency by switching to ocpa-ng 1.11  
* Proper stat gain on levelup by loading hardcore gains after skyvalor
* No simpler knock pamphlet to player by editing and recompiling script
* replaced Curios with curios by running Skyrim through Steam and downloading the correct version - Credits to Biggie
* removed vanargand sneak attacks due to not working well with mco and converter being down

*mod changes*  
* Added appearance mods
* Updated community shaders
* Added Skyrim Unbound and AYOP - Skyrim Unbound  
* Added texture packs such as aMidianborn Book of Silence SE

*ini edits*  
* Skyrimprefs.ini
* fLightingOutputColourClampPostEnv = 9999.0000
* fLightingOutputColourClampPostLit = 9999.0000
* fLightingOutputColourClampPostSpec = 9999.0000

* skyrimcustom.ini
* bIBLFEnable=1
* uIBLFBlurRadiusX = 9.0000
* uIBLFBlurRadiusY = 9.0000
* fIBLFLightsRangeDownshift = 0.0000
* fIBLFGlobalIntensity = 0.3000

---2.0.0a---  
*Install and downgrade to 1.5.97*  
Clean install of Skyrim (not CK) https://thephoenixflavour.com/bg/additional-modules/clean-install/  
Downloaded and Ran Keyzma's MO2 installer https://www.nexusmods.com/site/mods/599    
* Portable
* Stock game
* Keep installers
* Wabbajack
* Curation Club MO2 plugin
* Root Builder MO2 plugin
Added binkw64.dll, old exes and old steam_api.dll from old ElmoRim     
Removed bink2w64.dll    
Removed all texture .bsas  
Ran curation club and deleted everything except 4 free cc 
Switched to dark1809 theme in mo2  
Enabled archive parsing in mo2 settings  


*Install Creation Kit & Fixes*
Downloaded latest CK on Steam
Created [R] Creation Kit
Moved files/folders to Root folder in mod:
* lex
* papyrus compiler
* Tools
* Bink2w64.dll
* CreationKit.exe
* CreationKit.ini
* flowchartx64.dll
* p4com64.dll
* SkyrimReservedAddOnIndexes.txt
* Steam_api64.dll
Unpacked scripts.zip in mod folder
Added three lines to creationkit.ini:
* bAllowMultipleMasteFiles=1
* bAllowMultipleMasterLoads=1
* sScriptSourceFolder = ".\Data\Scripts\Source"
Rearranged CK scripts structure to match ini setting    

*Added mods & tools*   
xEdit w/ -c:"C:\ElmoRim 2\Tools\SSEEdit 4.1.5\cache\" -IKnowWhatImDoing command line  
Complete Papyrus Syntax Highlighting for NotepadPlusPlus to NPP install dir   
[R]Skyrim Script Extender (SKSE64)  
Bethesda Plugin Manager for Mod Organizer (MO2 plugin)  
BethIni + ran w/ high settings   
Installed HavokPcXsContentTools_X64_2010-2-0_20101115 to C:\Tools from link in https://www.youtube.com/watch?v=U88C9K-mSHs  
Downloaded and installed hkanno64 to general Skyrim modding folder
hkanno64 Batch cmd dump or update: created Source folder in hkanno64 root + placed batch files in hkanno64 root  
* Additional note: Moved mco_sprintpowerattack (Eivor Sprint attack mod, battleaxe/warhammer) to source folder
* ran dump.bat
* edited precision-annotations to remove weapon nod earlier (see precision mod page)
* Ran update.bat
* Moved updated file back to mod folder
Installed Backported Extended ESL Support  
Installed reshade w/ addon support from reshade.me
* Shaders downloaded separately from respective github page->get static link via latest commit->view code->download zip
Downloaded and installed SkyUI 5.1 & 5.2 Source (not included in WJ list)  to general Skyrim modding folder
Pandora behavior engine from monitor144hz's github  
fBookOpenTime=200 added to skyrim.ini  
Draft Whatever.ini - Main (xEdit Script)  
Draft Whatever.ini - Example - Preset  
Untelden's xEdit Script Library  

*Ini edits*
Skyrim.ini
* [VATS]
* bVATSDisable=1
---1.3.0RC3---

-Tweaks & Settings-  
Changed layout of changelog  
Switched version of glamarye shader  
Enabled Parallax setting in Community Shaders  
 


---1.3.0RC2---  
Added Enhanced Blood Textures    
Added Dynamic Activation Key  
Added No Edge Glow - Magic and Transformations UPDATED ESL  
Added DPI Scaling Fix  
Added DAR to OAR Converter  

Removed Enhanced Blood Textures LITE  
Removed Optional files for blood splatter sizes (LITE version ONLY)  
Removed Animated Ingredients  
Removed Animated Ingredients - Settings Loader  
Removed Animated Poisons  
Removed Animated Poisons - Settings Loader  
  
Updated Immersive Interactions - Animated Actions to 1.71  
Updated Immersive Interactions - Legacy Settings Loader to 1.40  
Updated Slim & Glamarye reshade shaders  
Updated Reshade to 5.9.0  

Switched EBT patches to Main variants  
Increased carry weight to 200  
Patched Bound Animated Armory weapon speeds  
Regenerated Nemesis Output  
Set Shadow Resolution to 1024 in skyrimprefs.ini  
Enabled DOF in skyrimprefs.ini    
Added NoStartingMapMarker Synthesis patcher  
Removed Castle Dour map marker esp  
Fixed duplicate Armors of the Velothi recipes
Reinstalled Crossbow Integration  
Replaced No map marker esp with Synthesis patcher  
Regenerated Synthesis Output  
Regenerated Nemesis Output  
Converted ADXP I MCO ER Katana (SCAR) to OAR structure  

  
---1.3.0RC1---  
Added Vikings Weaponry - Johnskyrim  
Added Mikhails Reshade for ElmoRim  
Added [R] Reshade Shaders  
Added TAA Sharpen    
Added Grass Sampler Fix  
Added Visibility - Performance-Friendly Lighting Mod  
Added Standard Lighting Templates  
Added At Your Own Pace - Thane Overhaul  
Added [E] WAAT - ArteFake Patch  
Added Vikings Weaponry - Johnskyrim  
Added Taunt Your Enemies - Taunting Matters  
Added Remote Interactions  
Added Remote Interactions - Settings Loader  
Added Spaghetti's Towns - AIO  
Added Azurite Weathers  
Added True Storms Special Edition - Thunder Rain and Weather Redone  
Added Vocaris - Conjuration Sounds Overhaul  
Added Hibernus - Frost Magic Sounds Overhaul  
Added Hyperion - Restoration Sounds Overhaul  
Added See Time Remaining for Rested Effects  
Added Wait Menu Redirected  
Added Skyrim on Skooma  
Added Wait I know You - Forcegreet Tweak  
Added Skyrim Textures Upscaled - Complete Vanilla Upgrade  
Added Immersive Hunting Overhaul  
Added [E] Immersive Hunting Consistency Patch  
Added Carriage and Ferry Travel Overhaul - Fixes and Winterhold
Added R.A.S.S. - Rain Ash And Snow Shaders  
Added Lawless - A Bandit Overhaul  
Added Lawless Simonrim  
Added Lawless Patch FOMOD  
Added [E] ElmoRim OAR Configuration  
Added Open Animation Replacer  
Added Goetia Animations - Alternate Movement For All Staves  
Added Weapon Styles - DrawSheathe Animations  
Added Immersive Equipment Displays - Extra Skeleton Nodes  
Added Dual Casting Fix  
Added Screen-Space Shadows  
Added Skóglendi - A Grass Mod  
Added Realistic High Altitude Treeline  
Added ADXP l MCO Imperium Animation Complete Pack OAR  
Added Smooth Moveset - Grip fix  
Added For Honor in Skyrim I Nobushi OAR  
Added For Honor in Skyrim I Lawbringer OAR  
Added Runic Mage Armor- Flesh Replacer 2  
Added Simplicity of Sea  
Added Water Effects Brightness and Reflection Fix  
Added Grass FPS Booster  
Added Complex Parallax Materials  
Added Water Blending  
Added Dynamic RaceMenu Interface Patcher - DRIP  
Added RaceMenu - Untarnished UI Patch - DRIP Patch  
Added DRIP - Untarnished UI  
Added [NoDelete] Fishing  
Added [NoDelete] Rare Curios  
Added [NoDelete] Saints and Seducers  
Added [NoDelete] Survival Mode  
Added Rogue Master Detector  
Added Inmortui - Undead SFX Replacer  
Added Simple Dual Sheath - XPMSSE Left Hand Sheath Rotation Fix  
Added Conditional Expressions Extended  
Added Conditional Expressions Extended - Settings Loader  
Added [E] Gameplay Fixes & Tweaks
Addded SPID-ified - HDT-SMP for Cloaks and Capes  
Added Spectris - Illusion SFX Overhaul  
Added The Heart of Dibella - Quest Expansion  
Added Survival Mode Prompt Removed  
Added Fishing - Reduced Cut  
Added Skyrim Extended Cut - Saints and Seducers  
Added Some Standard Lighting Templates patches  
Added CC Integration separator  
Added MCO Universal Support  
Added MCO Block Recovery  

Removed [O] Synthesis - NPC Stat Rescaler  
Removed [E] Rescaler - Skyrim Unbound Patch  
Removed [E] IED Left Hand Meshes  
Removed Nordic Round Shields (Viking shields)  
Removed [E] OWL - Nordic Round Shield Patch  
Removed [O] Synthesis - NPC Stat Rescaler  
Removed [E] Rescaler - Skyrim Unbound Patch  
Removed Imperium Combat Animations for Player No Locomotions  
Removed College for Non-Mages  
Removed Harder Thaneships - Globals Only  
Removed Improved College Entry - Questline Tweaks  
Removed WAAT Custom Artifact Patch  
Removed Artifacts - The Tournament of the Ten Bloods (Goldbrand 2H Only)  
Removed Bloodskal Blade - Tweaks and Enhancements - Reliquary of Myth Patch  
Removed Modular Armory - Reliquary of Myth Patch  
Removed Reliquary of Myth - Artifact Overhaul  
Removed Nightsky via Silver  
Removed Skyrim Textures Redone - Stars  
Removed Cathedral Weathers MCM - Settings Loader  
Removed Cathedral Weathers MCM  
Removed Cathedral Weathers Unofficial Update   
Removed Cathedral Weathers and Seasons  
Removed Improved colors Reshade for Vanilla HDR   
Removed [R] Reshade  
Removed Vanilla HDR  
Removed UpscalerBasePlugin  
Removed Skyrim Upscaler - DLSS FSR2 XeSS  
Removed Mundus USSEP patch  
Removed unofficial performance optimized textures AKA (UPOT)  
Removed Project Clarity AIO Half Res Loose  
Removed Skygazer Moons SSE 2K - No Glow  
Removed HD Quality Cubemaps  
Removed Animated Armoury - Open World Addon  
Removed Dynamic Animation Replacer  
Removed [E] Draw 2 Addon - Axes on Back  
Removed Draw 2 - Dual Weapon Equip-Unequip Animations  
Removed Folkvangr - Grass and Landscape Overhaul  
Removed Bears of the North  
Removed Maximum Skeletons - Rougeshot  
Removed SSE Parallax Shader Fix v1.0 (BETA)  
Removed SSE Parallax Shader Fix v1.0 (BETA) - Parallax Terrain Addon Beta  
Removed ADXP I MCO ER Spear Basic Animation (SCAR)  
Removed Smart NPC Potions - Enemies Use Potions and Poisons - Settings Loader  
Removed Realistic Halberd Poleaxe Animation(MCO SCAR)  
Removed Community Shaders - Parallax  
Removed Community Shaders - Enable Terrain Parallax  
Removed Barenziah's Glory  
Removed High Gate Ruins Puzzle Reset Fix  
Removed Conditional Expressions - Subtle Face Animations - Settings Loader 
Removed Inferno - Fire Effects Redux   
Removed No Edge Glow - Magic and Transformations UPDATED ESL  
Removed [E] Backpack Penalty Tweaks  
Removed [E] Camping Lite Tweaks  
Removed Miscellaneous Tweaks Collection - Realistic Animal Loot  
Removed [E] ElmoRim Cloaks Lite  
Removed Ghosu's Leviathan Axe - Retexture and Remodel by Akarsil  
Removed God of War Leviathan Axe  
Removed Dark Brotherhood Rising Revengeance  
Removed Skeletons don't breathe SSE  
Removed Player Spell Lighting - Mysticism Patch (now handled in the ElmoRim CRP)  
Removed [E] Restore Crossbow Fire Sound  
Removed Mount Anthor Dragon Fix  

Updated At Your Own Pace - College of Winterhold to 2.0.1  
Updated DynDOLOD Resources SE 3 to alpha-36  
Updated DynDOLOD 3 to alpha-127  
Updated Synthesis to 0.25.4  
Updated xLODGen to beta-98  
Updated Mundus - A Standing Stone Overhaul to 1.10.2    
Updated Mysticism - A Magic Overhaul to 2.3.1  
Updated Adamant - A Perk Overhaul to 5.8.3  
Updated Aetherius - A Race Overhaul to 2.11.7  
Updated Apothecary - An Alchemy Overhaul to 1.3.4  
Updated Thaumaturgy - An Enchanting Overhaul to 1.3.3   
Updated Hand to Hand - An Adamant Addon to 1.5.5  
Updated Conditional Armor Type Animations to 1.3c  
Updated Goetia Animations - Female Idle Walk And Run to 1.2c  
Updated Goetia Animations - Male Idle Walk And Run to 1.3c    
Updated Goetia Animations - Sprint to 1.0c
Updated Leviathan Animations II - Female Idle Walk And Run to 2.3c  
Updated Leviathan Animations II - Male Idle Walk And Run to 2.3c  
Updated Leviathan Animations II - Sprint to 2.4c  
Updated Vanargand Animations - Female Idle Walk and Run to 1.3c  
Updated Vanargand Animations - Male Idle Walk and Run to 1.3c  
Updated Vanargand Animations - Sprint to 1.3c  
Updated Dynamic Random Spell Idle to 1.4  
Updated Grass Lighting to 1.1.1  
Updated Tree LOD Lighting to 1.0.1  
Updated Community Shaders to 0.4.2  
Updated Xenius Character Enhancement to 1.3  
Updated Unofficial Skyrim Special Edition Patch to 4.2.9alpha  
Updated Spell Perk Item Distributor to 6.6.1  
Updated Payload Interpreter to 1.1  
Updated Papyrus Ini Manipulator to 1.9.2  
Updated ConsolePlusPlus 1.3  
Updated Mannequin Management to 4.0  
Updated Dragonactorscript infinite loop fix to 1.3.2  
Updated Compass Navigation Overhaul to 1.2.1  
Updated Clutter Filter for BTPS to 1.0.1  
Updated Untarnished UI to 1.1.6
Updated The Elder Scrolls Legends - Loading Screens to 2.1.1  
Updated Keyboard Shortcuts Fix to 1.0.0.4  
Updated Audio Overhaul for Skyrim SE to 4.1.3  
Updated AOS - EBT Lite & True Storms Patch to 4.1.3  
Updated Deadeye - Bow SFX to 1.2  
Updated Infernorum - Fire Magic Sounds Overhaul to 1.0  
Updated Fulminis - Shock Magic Sounds Overhaul to 1.0  
Updated Hibernus - Frost Magic Sounds Overhaul to 1.0  
Updated Yet Another Music Merge to 1.3  
Updated Chapter II - Jeremy Soule Inspired Music to 3.2  
Updated Assorted mesh fixes to 0.85  
Updated DynDOLOD Resources SE 3 to alpha-37  
Updated Simplicity of Snow to 0.12.1  
Updated SkySight Skins - Ultra HD Male Textures and Real Feet Meshes (4K2K HIGH) to 1.1.0  
Updated Dynamic Impact - Slash Effects X to 1.02  
Updated Misc Dialogue Edits to 1.9.2  
Updated Swiftly Order Squad - Simply Order Summons integration to 1.7  
Updated Simply Order Summons to 0.11  
Updated Remote Interactions to 1.02  
Updated Simple Crossbow Integration (SPID) to 1.0.1  
Updated Arena - An Encounter Zone Overhaul to 1.2  
Updated Paarthurnax - Quest Expansion to 1.12  
Updated At Your Own Pace - Companions to 3.0CP  
Updated At Your Own Pace - Thieves Guild to 2.1.1TG  
Updated At Your Own Pace - College of Winterhold to 2.1MG  
Updated Sidequests of Skyrim to 0.8.2  
Updated Precision Creatures to 2.3  
Updated Maximum Skeletons D-Won Edition to 1.3  
Updated Gesture Animation Remix (DAR) to 2.0  
Updated NPC Animation Remix (DAR) to 1.5  
Updated Skyrim Unbound Reborn to 2.0.5  
Updated Community Shaders to 0.4.3  
Updated TAA Sharpen to 1.0.1  
Updated Grass Sampler Fix to 1.0.1  
Updated Embers XD to 2.7.8  

Restructured Synthesis Outputs  
Configured IED mesh generator synthesis patch path   
Moved Open World Loot - Encounter Zone and Loot Overhaul to Late Loaders-separator  
Moved OWL Randomized Special Loot  to Late Loaders-separator  
Moved Open World Loot - Better Civil War Reward Addon  to Late Loaders-separator  
Moved Arena - An Encounter Zone Overhaul to Lates Loaders-separator
Removed dependencies and cleaned masters from ElomRim CRP  
Added new Synthesis patcher for OWL integrations  
Reset Wait to T key   
Moved NordwarUA Scaled Armor to Equipment - Textures & Meshes-separator  
Enabled TAA in skyrimprefs.ini  
Deleted Misc Tweaks - More Expensive Player Homes.esp from Miscellaneous Tweaks Collection  
Deleted Misc Tweaks - Night Eye Redux.esp from Miscellaneous Tweaks Collection  
Renamed Miscellaneous Tweaks Collection to Miscellaneous Tweaks Collection - Realistic Animal Loot  
Renamed Cities-separator to Cities & Towns  
Deleted [E] College for Non Mages Tweaks from [E] Quest Fixes & Tweaks  
Added [E] ElmoRim Pilgrim Consistency Patch.esp to [E] SimonRim Fixes & Tweaks  
Cleaned upp the inlined files by deleting a bunch of logs  
Reinstalled Untarnished UI w/o map markers to improve world map visibility  
Deleted aMidianBorn Armor Variants Lite - OWL Patch.esp from aMidianborn Armor Variants Lite  
Tweaked attack speeds for Animated Armory  
Regenerated LOD
Regenerated facegen
Reverted to vanilla difficulty multipliers  
Removed NPC Stats rescaler Synthesis patcher  
Made crossbow steel/dwarven bolts craftable anywhere  
Rebalanced Adamant Overpower & Overrun perks to fit with ElmoRim combat tempo  
Renamed Cumulative fix for Eye Meshes - Alternate - Only black eye fix to Cumulative fix for Eye Meshes - Only black eye fix  
Updated several [E]-patches  
Updated ElmoRim CRP - Disables all form of Nighteye  
Reinstalled Simple Crossbow Integration (SPID) since Rare Curios is now integrated with ElmoRim  
Merged Andrealphus' Harder Quest-mods into single mod  
Split Quests & Encounters-separator into separate separators  
Moved Hand placed enemies - No Ambushes Version to Encounters separator  


---1.2.1--  
Switched xLODGen link    
Updated modlist description  

---1.2.0---  
Added Simple Crossbow Integration (SPID)  
Added SSE Parallax Shader Fix v1.0 (BETA)  
Added SSE Parallax Shader Fix v1.0 (BETA) - Parallax Terrain Addon Beta  
Added Auto Parallax  
Added Skyland Landscapes Parallax  
Added Improved colors Reshade for Vanilla HDR  
Added Community Shaders  
Added Tree LOD Lighting  
Added Grass Lighting  
Added Grass Collision  
Added Twilight  
Added Enhanced Volumetric Lighting and Shadows (EVLaS)  
Added Ambiance - A Vanilla+ Ambient Lighting Overhaul  
Added Combat Pathing Revolution  
Added Behavior Data Injector  
Added Realistic Halberd Poleaxe Animation(MCO SCAR)  
Added Vibrant Weapons - Animated Armoury Patch  
Added ADXP I MCO ER rapiers (SCAR)  
Added ADXP I MCO ER Katana (SCAR)  
Added ER Spear Basic Animation walk and run  
Added ADXP I MCO ER Spear Basic Animation (SCAR)  
Added Animated Armoury - Open World Addon  
Added Animated Armoury - Clean Edition 2.3  
Added Animated Armoury - DAR Version - New Weapons with animations  
Added The Frozen North - Cold Standalone  
Added [E] Camping Lite Tweaks  
Added Hand placed enemies - No Ambushes Version  
Added Chillwind Depths CTD Fix  
Added Hearthfires Houses Building Fix  
Added Scare my Enemy Bug Fix  
Added Mount Anthor Dragon Fix  
Added Source of Stalhrim Quest Fix  
Added WE05 Script Fix  
Added Magic Student (WIChangeLocation04) Quest Fix  
Added Stamina of Steeds  
Added Rock Traps Trigger Fixes  
Added Fnar Combat - Increased Damage  
Added Fnar Combat - No Killmoves and No Killcams  
Added Fnar Combat - Draugr Don't Shout  
Added Fnar Combat - No BS AI Projectile Dodge  
Added Fnar Combat - Reduce Archer Accuracy  
Added Fnar Combat - Blocking More Effective  
Added Dynamic Impact - Slash Effects X  
Added [O] Synthesis - NPC Stat Rescaler  
Added NordwarUA Scaled Armor  
Added [E] Rescaler - Skyrim Unbound Patch  
Added Instantly Skip Dialogue NG  
Added Clutter Filter for BTPS  
Added Merchant - A Trading Expansion  
Added Merchant - Prices Addon  
Added Maximum Carnage for SkySA and MCO  
Added Hand to Hand - Jump Perks Addon  
Added Nemesis Creature Behaivour - WereWolf Addon  
Added Imperium Combat Animations for Player No Locomotions  
Added Maximum Skeletons Rougeshot  
Added powerofthree's Tweaks  
Added Adamant - Animated Armory Bound Weapons - No Whips  
Added Dragonactorscript infinite loop fix  
Added [E] Untarnished UI ElmoRim Config  
Added Terrain Parallax Blending Fix


Removed Lux - FWMF Fantasy Paper Maps Patch  
Removed Lux Patches  
Removed Lux  
Removed Lux Via - Resource Pack (No ENB Light)  
Removed Hyperborean Snow 4K  
Removed TB's 8K Immersive Caves  
Removed TB's 8K Immersive Mines  
Removed Skyland Watercolor  
Removed ShaderTools Updated  
Removed Crossbow Integration (Including Creation Club)  
Removed Obscure's College of Winterhold  
Removed Obscure's College of Winterhold NPC Stuck in Staircase Fix  
Removed Obscure's College of Winterhold - Patches  
Removed eFPS - Official Patch Hub  
Removed [R] Reshade - dxgi.dll  
Removed Sswaye's "Cabbage" Reshade  
Removed Sunhelm - Patches  
Removed SunHelm Survival  
Removed Sunhelm - Simple weather icons  
Removed SunHelm Survival and needs Alternate Start Mods - Settings Loader  
Removed Sunhelm - Experience Patch  
Removed Hand Placed Enemies - More populated spawns dungeons and POIs  
Removed Elder Creed - Blade  
Removed Valravn - Integrated Combat of Skyrim  
Removed Valravn SPID Uncloak  
Removed Subtle but Aetherius  
Removed 3rd Person Dual Wield Animation Fix SSE  
Removed AC Valhalla Inspired Animations For Player Only  
Removed [E] Scaled Armor Clipping Fix  
Removed Speedy Daedric Dialogue (2x)  
Removed Allow Dialogue Progress Bugfix  
Removed Misc Tweaks - More Expensive Inns  
Removed Tyrannical Trolls  
Removed Smooth Random Blocking Animation 3.0  
Removed Move it Dammit - SSE All-in-One Insaller  


Updated ElmoRim CRP to 1.3.0
Updated LamasTinyHUD to 1.4.4   
Updated DynDOLOD Resources SE 3 to alpha-34  
Updated DynDOLOD to alpha-122  
Updated Skyland AIO to 4.1  
Updated FSR dll's for UpscalerBasePlugin  
Updated UpscalerBasePlugin to 1.1.0  
Updated XeSS dll's to 1.1.0  
Updated [O] ElmoRim - Facegen to 2.2  
Updated [O] ElmoRim - SSELODGen Output to 2.1  
Updated [O] Elmorim - TexGen Output to 2.4  
Updated [O] ElmoRim - DynDOLOD Output to 2.4  
Updated Untarnished LamasTinyHUD Reskin to 1.4  
Updated powerofthree's Papyrus Extender to 5.5.0  
Updated Nemesis Creatures BEHAVIOUR compatibility to 1.4  
Updated Skyrim Upscaler - DLSS FSR2 XeSS to 1.1.3  
Updated Spell Perk Item Distributor to 6.5.2  
Updated Keyword Item Distributor to 3.0.2  
Updated Scrambled Bugs (Merged new optional files into main mod)
Updated Papyrus Tweaks NG to 4.1  
Updated QuickLoot EE to 1.2.1  
Updated QuickLoot EE - Settings Loader to 1.1  
Updated Untarnished UI to 1.1.5  
Updated Infernorum - Fire Magic Sounds Overhaul to 0.5    
Updated Static Mesh Improvement Mod Improvement Mod to 1.7.1  
Updated Skyrim Landscape and Water Fixes to 7.9  
Updated Forgotten Retex Project to 8.3  
Updated Icy Windhelm to 2.2  
Updated Spaghetti's Cities - AIO to 1.3  
Updated Reverie Skin to 1.10.14  
Updated Maximum Carnage to 7.7  
Updated Maximum Carnage - Settings Loader to 1.2  
Updated AI Overhaul SSE to 1.8.3  
Updated Misc Dialogue Edits to 1.8.6  
Updated Bandit Lines Expansion to 1.07  
Updated Civil War Lines Expansion to 1.06  
Updated Mysticism - A Magic Overhaul to 2.2.3  
Updated Adamant - A Perk Overhaul to 5.7.6  
Updated Hand to Hand - An Adamant Addon to 1.4.6  
Updated Aetherius - A Race Overhaul to 2.10.4  
Updated Mundus - A Standing Stone Overhaul to 1.9.2  
Updated Forceful Tongue - Shouts Overhaul to 3.0.9.1  
Updated Faster HDT-SMP to 1.50.9rc-1    
Updated Reliquary of Myth - Artifact Overhaul to 4.6.7  
Updated Simple Dual Sheath to 1.5.6  
Updated Timing is Everything SE - Settings Loader to 1.0.1  
Updated At Your Own Pace - Companions to 2.0.7CP  
Updated At Your Own Pace - Skyrim Unbound to 1.1SU  
Updated Dawnguard - Tweaks and Enhancements to 0.21  
Updated TK Dodge RE to 0.50Final  
Updated Precision Creatures to 2.1  
Updated Maximum Skeletons D-Won Edition to 1.2  
Updated NPC Animation Remix (DAR) to 1.4  
Updated Improved Table Transition Animations to 1.1  
Updated Conditional Expressions - Subtle Face Animations to 1.27  
Updated Community Shaders to 0.1.0  
Updated Embers XD to 2.7.3  
Updated My Minimalistic AutoSave Mod to 5.0  
Updated Reshade to 5.8.0  

Regenerated Nemesis output  
Regenerated SSELODGen output  
Regenerated TexGen output  
Regenerated DynDOLOD output    
Regenerated Synthesis output  
Added recommended Vanilla HDR ini-tweaks  
Set TreeNormalMaps=1 in TexGEN_SSE.ini  
Set TreeLODComplexAtlas=1 in DynDOLOD_SSE.ini  
Restructured [R] Reshade to match new functionality  
Renamed Lighting & Reshade-separator to Community shaders, Lighting & Reshade  
Moved Map-separator  
Moved Dragon War - A Dragon Overhaul to Combat-separator  
Moved [E] Dragon War No Killmoves to Combat-separator  
Moved MCM Helper to Framework-separator  
Exported new IED default config  
Changed controlmap to allow for more hotkeys  
Reconfigured the controlmap 
Renamed & moved Misc Dialogue Edits Patches to Late loaders-separator  
Moved dodge mods below Precision  
Added Mortal Enemies Synthesis patcher  
Merged several [E]-mods under their respective separators    
Merged several mods w/ their patches and optional files  
Recompiled [E] Remove Maximum Carnage Message script  
Disabled a broken mesh in Major Cities Mesh Overhaul  
Hid Verolevi idles to enable other npc idles  
Merged AMB Variants Lite Patches into single mod  
Merged Frankly HD Miraak hotfix with main mod  
Merged Mundus w/ patch   
Merged Hand to Hand addons into single mod  
Merged Apothecary - Food & Drink w/ patch  
Merged Forceful Tongue w/ patches  
Merged Miscellaneous Tweaks Collection mods into single mod  
Merged Fnar Combat mods into single mod  
Merged Yet another music merge w/ chapter II patch  
Merged Caught Red Handed w/ USSEP patch  
Split Loot, Gear & Encounters-separator into Equipment - Loot & Gear and Equipment - Textures and Meshes  
Renamed Quests separator Quests & Encounters  
Moved encounter mods to Quests & Encounters-separator  
Added Toggle Run/Walk back to [E] Controlmap - Num 0  


---1.1.1---  
Added [E] Listen Dead Drop Fix    
Added [E] Remove Adamant Thrall Dialogue  
  
Updated Modular Armory - Armor Mesh Fixes Patch to 1.1  
Updated Modular Armory to 1.3.1  
Updated Reshade to 5.7.0  
Updated Vampire Feed Improved to 1.3  

Disassembled Vibrant Weapons scripts, removed powers & recompiled  
  
---1.1.0---  
Added Vanargand Animations - One Handed Mid Stance  
Added ConsolePlusPlus  
Added HelpExtender  
Added Vampire Feed Improved  
Added Cities-separator  
Added Capital of the Pale  
Added Capital of the Pale - CFTO Patch  
Added Capital of Winterhold  
Added Capital of Hjaalmarch  
Added Capital of Hjaalmarch - CFTO Patch    
Added Capital of Falkreath  
Added Icy Windhelm  
Added Spaghetti's Cities - AIO  
Added Vampire Lines Expansion  
Added Orc Addon for Vampire Lines Expansion  
Added Locational Encounter Zones  
Added Vibrant weapons - Fire Frost Shock  
Added Improved weapons enchantments FX SE  
Added [E] Thaumaturgy VFX Patch  
Added Infernorum - Fire Magic Sounds Overhaul  
Added Fulminis - Shock Magic Sounds Overhaul  
Added Swiftly Order Squad - Simply Order Summons integration  
Added Simply Order Summons

Removed Copy and Paste in Console  
Removed Maleficus' MCM Framework for EVGAT Mods  
Removed Maleficus' Traversal (EVGAT)  
Removed Visual Animated Enchants - VAE  
Removed QRVAE - Qwinn's Refined Visual Animated Enchants  
Removed Thaumaturgy - Visual Animated Enchantment Patch  
Removed [E] VAE - RoM Patch  

Updated Lamas Tiny HUD to 1.2.2  
Updated Untarnished LamasTinyHUD Reskin to 1.2  
Updated Skyrim Unbound Reborn to 1.12.3  
Updated At Your Own Pace - Companions to 2.0.5CP  
Updated At Your Own Pace - Thieves Guild to 2.1TG  
Updated [E] No starting Castle Dour Map Marker to 1.1: Forwarded records from USSEP  
Updated [E] ElmoRim CRP to 1.2: Resolved conflict between Caught Red Handed QE and Skyrim Unbound  
Updated Paper Sovngarde Map for FWMF to 1.72  
Updated Paper Blackreach Map for FWMF to 1.75  

Added Shield+Sword on back Draw2 animation    
Added accidentally removed Custom IED profile    
Disabled Animated Eating Redux NPC animations: Caused NPC to stand in weird places  
Increased I-frames of Elden counter for balancing purposes  
Increased stun damage in Valhalla Combat for balancing purposes  
Reduced camera shake when sprinting  
Regenerated LOD
Reinstalled Elder Creed - Odyssey Dual Wield Dagger Moveset to reset priorities  
Tweaked Incremental Injuries for mage QoL. Reduced magicka damage rate. Slightly increased helath damage rate.     
Tweaked Sunhelm settings for QoL  

---1.0.2---  
Fixed AstrayFX shader download link  

---1.0.1---  
Fixed broken shader download link  
 

  

---1.0.0 RC6----  
Removed Elder Creed - Valhalla Axe Moveset AIO  
Updated [E] Attack MCO-DXP Sprint attack fix to 1.1: Credits to fiorezy for finding a fix for the animation snapping  


---1.0.0 RC5----  
Removed Skyrim Platform: Elden Equip was the only dependency.   



----1.0.0 RC4----  
Added [E] Scaled Armor Clipping Fix: Not perfect but the best I can do in a reasonable time frame.
Added 3rd Person Dual Wield Animation Fix SSE  
Added BodySlide and Outfit Studio  
  
Fixed female weapon positioning in IED + Checked Sync flag for equipment positioning. 
Set ResumeAfter=2.0 in Pause After Load Unscripted NG to avoid breaking scenes that start right after loading into a cell. Credits to Zé for testing.    


----1.0.0 RC3----    
Added [E] IED Left hand meshes  
Added Missile's Immersive Equipment Display Presets  
Added [R] SSE Parallax Shader Fix - d3dcompiler_47: Turns out it is needed ATM   
  
Updated Infinity UI to 2.0.1  
Updated Untarnished UI to 1.1.4  
Updated Compass Navigation Overhaul to 2.1  

Removed QuickLoot EE - Dynamic Resize and Value-Weight Patch: Now included in Untarnished UI  
Removed Whiterun Market - A Map Marker: Redundant with CoMAP Jorrvaskr marker   
  
Added ImmersiveEquipmentMeshGen Synthesis patcher  
Fixed some IED weapon rotations  
Regenerated Synthesis output   
Regenerated LOD
set bForceNPCSsUseAmmo to 1 via BethINI  

----1.0.0 RC2----  
Special update instructions:
* Open RaceMenu. Set all XPMSSE related sliders in RaceMenu and XPMSSE styles to to default in MCM. 
* Press uninstall in your mod manager for XPMSSE.

Added DART - Dynamic Animation Replacer Tool (beta)  
Added Reshade - DXGI.dll: Moved to separate mod for easier distribution   
Added Animations - Movement separator  
Added Animations - Idles & Interactions separator 
Added [E] Attack MCO-DXP Sprint attack fix: Sprintpowerattack = sprintattack for maces/axes. Sprintattack from greatsword for warhammers/battleaxes. Fix for GitHub issue #13  
Added One Click Power Attack MCM  
Added Papyrus Ini Manipulator  
Added Elder Creed - Valhalla Axe Moveset AIO  
Added MCO - ADXP - Elder Creed - Blade 
Added Champollion  
Added Champollion - Graphical User Interface   
Added [E] Draw 2 Addon - Axes on Back  

Updated NPC Animation Remix (DAR) to 1.2.1  
Updated EVG Animated Traversal Skyrim Integration Patch to 1.2.3: Switched to non-mcm version  
Updated Reshade to 5.6.0  

Removed Animations separator  
Removed SSE Parallax Shader Fix v1.0 (BETA): Not needed ATM  
Removed [R] SSE Parallax Shader Fix - d3dcompiler_47: Not needed ATM    
Removed XP32 Maximum Skeleton Special Extended  
Removed XP32 Maximum Skeleton Special Extended - Fixed Scripts  
Removed XPMSSE - Nemesis - Papyrus Stack Fix  
Removed XPMSSE Weapon Styles Uncloaked  


Moved Cumulative fix for Eye Meshes - Alternate - Only black eye fix to Appearance-separator  
Now distributing dxgi.dll directly since licence allows it  
Regenerated Nemesis output  
 

----1.0.0 RC1----  
Added Untarnished LamasTinyHUD Reskin  
Added Unarmed Weapon Speed Scaling   
Added SmoothCam Vanilla Enhanced 2  
Added SmoothCam - Galuna's Preset  
Added Dialogue Movement Enabler  
Added Camera Noise  
Added Cinematic Sprint  
Added TK Dodge RE (Shorter Step Dodge)  
Added QRVAE - Qwinn's Refined Visual Animated Enchants 
Added [E] VAE - RoM Patch   
Added Frozen Electrocuted Combustion  
Added Improved Table Transition Animations  
  
Removed [E] LamasTinyHUD - ElmoRim Preset  
Removed SPID for Footprints Fix  
Removed Hand to Hand - Armor Addon  
Removed Vampire Feeding Tweaks: Can bug out at times + new Scion update makes blood potions more common  
Removed Vampire Feeding Tweaks - Show Feed Option Patch  
Removed Improved Alternate Conversation Camera: Causes some issues with SmoothCam.
Removed Maximum Destruction   
Removed Smart Optimal Salves - Optimal Potion Hotkey MCM: Replaced by Lamas Tiny HUD
Removed Smart Optimal Salves - A Patch for All Potions
Removed Smart Optimal Salves - Optimal Potion Hotkey MCM - Settings Loader

Updated LamasTinyHud to 1.1.12    
Updated Papyrus Tweaks NG to 4.0  
Updated CritterSpawn Congestion Fix to 1.3  
Updated Reverb Interior Sounds Expansion to 1.5.0  
Updated Flickering Meshes Fix to 2.1  
Updated Assorted mesh fixes to 0.78  
Updated Forgotten Retex Project to 8.2  
Updated Cathedral Weathers Unofficial Update to 2.40  
Updated Deathrattle - Maximum Carnage Audio Replacer to 1.1  
Updated SPID for Footprints to 3.4  
Updated Hand to Hand - An Adamant Addon to 1.4.0  
Updated Aetherius - A Race Overhaul to 2.10.2  
Updated Mundus - A Standing Stone Overhaul to 1.9.1  
Updated Pilgrim - A Religion Overhaul to 1.1.2  
Updated Faster HDT-SMP to 1.49.3  
Updated The Choice is Yours to 2.7  
Updated The Innocence Lost - Quest Expansion to 1.01  
Updated SCAR - Skyrim Combos AI Revolution to 1.06b  
Updated Precision to 2.0.4  
Updated Mysticism spells for spellcasters to 1.9  
Updated Leviathan Animations II - Female Idle Walk And Run to 2.3    
Updated Leviathan Animations II - Male Idle Walk And Run to 2.3  
Updated Leviathan Animations II - Sprint to 2.4  
Updated Skyrim Unbound Reborn to 1.11.14  

Regenerated Nemesis output  
Regenerated Synthesis output  
Renamed SKSE to ElmoRim + added icon  
Rearranged Smoothcam presets

----0.2.4----
Added xLODGen back in - Elmo needs to remember to check his meta files  
Cleaned up WJ-folder settings  

----0.2.3----  
Removed xLODGen97 due to refusing to be compiled   
Downloaded [O] ElmoRim - SSELODGen Output from nexus to ensure version sync  

----0.2.2----  
> Special update instruction:  
> Remove and add perks affected by speedmult via console to apply new setup.
> The following perks are affected
> * Flourish  
> * Quick Draw  
> * Bloodlust  

Added SimonRim Attack Speed Fix  
Added Bears of the North  
Added Tyrannical Trolls  

Updated Adamant - A Perk Overhaul to 5.7.4  
Updated Pilgrim - A Religion Overhaul to 1.1.1  
Updated Hand to Hand - An Adamant Addon to 1.3.6  
Updated Aetherius - A Race Overhaul to 2.9.1  
Updated LamasTinyHUD to 1.0.8  

Removed Weapon Speed Mult Fix  
Removed Weapon SPID Mult Fix  

Corrected name of Bloodlust perk in [E] Adamant - Precision Consistency Patch    
Disable Bear gore in Maximum Carnage - conflict with Bears of the North  
Implemented SimonRim Attack Speed Fix in [E] Adamant - Precision Consistency Patch    
Removed records from ElmoRim CRP related to attack speed  

----0.2.1----
Added Skyland Watercolor  

Removed Water for ENB  
Removed Water for ENB Patches   

Updated Untarnished UI to 1.1.1  
Updated [O] ElmoRim - TexGen Output to 2.1  
Updated [O] ElmoRim - DynDOLOD Output to 2.1  


Hid files conflicting w/ Untarnished UI  
Moved Ultrawide & Gamepad Support-separator above Interface-separator  
Removed patches for Water for ENB from Lux and FWMF  
Removed version number from profile name - it was a stupid idea  


----0.2.0----  
Added [R] SSE Parallax Shader Fix + d3dcompiler_47.dll  
Added ShaderTools Updated  
Added SSE Reshade Helper  
Added Vanilla HDR   
Added QuickLoot EE -  Dynamic Resize and Value-Weight Patch  
Added Subsurface Scattering Shaders for Skins  
Added Soaking Wet - Character Wetness Effect  
Added [R] Reshade   
Added Cathedral Weathers and Seasons  
Added Cathedral Weathers Unofficial Update  
Added Cathedral Weathers MCM  
Added Cathedral Weathers MCM - Settings Loader   
Added ESO Armor Collection - The Legends Breton Knight  
Added ESO The Breton Knight HDT-SMP  
Added LamasTinyHUD  
Added Reverie Skin  
Added SkySight Skins - Ultra HD Male Textures and Real Feet Meshes (4K2K HIGH)  
Added Feminine Khajiit Textures (Grey Cat and Leopard) [Vanilla]  
Added Masculine Khajiit Textures (Grey Cat and Leopard) [Vanilla]  
Added Flawn's Vanilla Argonians Redux  
Added FVAR - Weight Slider Affected Tails Patch  
Added Deadeye - Bow SFX  
Added Deathrattle - Maximum Carnage Audio Replacer  
Added Water for ENB Patches  
Added Forsworn and Thalmor Lines Expansion  
Added Forceful Tongue - Audio Overhaul for Skyrim Patch  
Added Maleficus' Traversal (EVGAT)  
Added Maleficus' MCM Framework for EVGAT Mods  
Added [E] FWMF Brightness Fix  
Added Visual Animated Enchants - VAE  
Added Thaumaturgy - Visual Animated Enchantment Patch  
Added Thaumaturgy - Player Spell Lighting Patch  
Added Strange Runes  
Added Strange Runes - No ENB Lights  
Added Hand placed enemies  
Added Animation Queue Fix  
Added Obscure's College of Winterhold - Patches  
Added The Innocence Lost - Quest Expansion  
Added Dark Brotherhood Rising Revengeance  
Added Airgetlam -Modern Magic Sounds Rework-  
Added Airgetlam RE4.1 -ISC Compatibility Patch -  
Added Leviathan Animations II - Female Idle Walk And Run  
Added Leviathan Animations II - Male Idle Walk And Run  
Added Leviathan Animations II - Sprint  
Added LamasTinyHUD
Added [E] LamasTinyHUD - ElmoRim Preset


Removed Rudy HQ - More Lights for ENB SE - Glowing Mushrooms  
Removed Meridia Clutter ENB Light (WIP)  
Removed Rudy HQ - More lights for ENB - Daedric weapons  
Removed Rudy HQ - More Lights for ENB SE - Chaurus Eggs and Sacs  
Removed Rudy HQ - More Lights for ENB SE - Soul Gems  
Removed Rudy HQ - More Lights for ENB SE - Bthardamz  
Removed Rudy HQ - More Lights for ENB SE - Deathbells and Nirnroots  
Removed Rudy HQ - More Lights for ENB SE - Torchbugs and Moths  
Removed Near Vanilla Project - Control Cube Redone - ENB Light  
Removed ENB lights for Aetherium shards  
Removed Misc Effects ENB Light - Leanwolf's Better-Shaped Weapons  
Removed Misc Effects ENB Light - Obscure's College of Winterhold  
Removed ENB lights for Volendrung  
Removed White Phial Replacer SE - ENB Light Addon  
Removed White Phial Replacer4K-2K  
Removed Kanjs - Queen Bee Meshes Particle light ENB  
Removed Kanjs - Queen Bee 2k  
Removed Elegant Magelight - Mysticism  
Removed Apocrypha ENB Light  
Removed ENB Particle Lights - Dwemer Lanterns  
Removed Barenziah's Glowing SE  
Removed Spiders of Solstheim - ENB Light  
Removed Elegant Magelight (with ENB Light)  
Removed Sprites or Specters - ENB Light  
Removed Particle Lights For ENB SE - Bugs in a Jar  
Removed Particle Lights For ENB SE - Ingredients  
Removed Particle Lights For ENB SE - Paragon Gems  
Removed Misc Effects ENB Light - Hotfix  
Removed Misc Effects ENB Light  
Removed Kanjs - Soul Husk Reimagined and Vanilla Meshes High Poly - Particle Lights - 1k - 2k - 4k - 8k  
Removed Particle Lights for ENB - Light Orbs - Motes  
Removed Particle Lights for ENB - Wisps - Witchlight  
Removed Kanjs - Vanilla Staff - Glow Map and Particle Lights  
Removed Particle Lights for ENB - Staff Enchanter  
Removed Particle Lights for ENB - Nordic Ruins Candles - Lux Patch  
Removed Particle Lights for ENB - Nordic Ruins Candles  
Removed ENB Particle Lights for Alchemy and Enchanting Tables  
Removed ENB Particle Lights for Gemstones  
Removed Particle Lights for ENB - Moon Crests  
Removed Particle Lights for ENB - Stalhrim Deposits and Ore  
Removed Particle Lights for ENB - Dwarven Spiders  
Removed Particle Lights for ENB - Ice Torches  
Removed Particle Lights for ENB - Standing Stones  
Removed Particle Lights for ENB - Ebonmere  
Removed Particle Lights for ENB - Falmer Drips  
Removed Particle Lights for ENB - Fire Traps  
Removed Particle Lights for ENB - Spectral Warhound Eyes  
Removed Particle Lights for ENB - Riekling Outposts  
Removed Rally's Riekling Outposts  
Removed Particle Lights for ENB - Falmer Things  
Removed Particle Lights for ENB - Luminous Ground Cover  
Removed Particle Lights For ENB SE - Undead Creatures  
Removed ENB Lights For Effect Shaders  
Removed ENB Particle Lights_separator  
Removed Bright Waterfall Fix for ENB - DynDOLOD Fix  
Removed Bright Waterfall Fix for ENB - Water for ENB  
Removed Folkvangr for ENB Complex Grass  
Removed Berserkyr ENB - Plugin  
Removed NAT.ENB - ESP WEATHER PLUGIN v3.1.0  
Removed Berserkyr ENB  
Removed ENB Particle Lights-separator  
Removed Particle Patch for ENB  
Removed Skyrim Particle Patch for ENB - Assorted Mesh Fixes - Solitude Mesh Fixes Patch  
Removed Ghost Pile Seam Fix (Skyrim Particle Patch)  
Removed ENB Helper SE  
Removed ENB Helper Plus  
Removed ENB Input Disabler    
Removed Rudy fix for Splashes of Storms and ENB   
Removed Tempered Skins for Males  
Removed Tempered Skins for Females  
Removed Tempered Racial Textures  
Removed EVG Traversal Animations - Dungeons addons
Removed Better FaceLight and Conversation Redux  
Removed Serio's Cycle Hotkeys  
Removed WM's Flora Fixes - SMIM Patch  
Removed Simplest Horses - Far Distance  
Removed Embers XD - Inferno Patch  (Now part of main mod)  
Removed Males Of Skyrim - High Poly Hands  
Removed Vanilla Body with UNP Textures  
Removed At Your Own Pace - Dark Brotherhood  
Removed Leviathan Animations - Male Idle Walk And Run  
Removed Leviathan Animations - Female Idle Walk And Run  
Removed Leviathan Animations II - Sprint  
Removed Simple Werewolf Favourite Howls Menu  
Removed Simple Werewolf Favourite Howls Menu - Settings loader  
Removed Modern Toggle Walk-Run Fix SE

Updated Soft Shadows to 1.1  
Updated UpscalerBasePlugin to 1.0.6.1    
Updated Skyrim Upscaler to 1.1.1   
Updated powerofthree's Papyrus Extender to 5.4.1  
Updated Spell Perk Item Distributor to 6.3.0     
Updated Base Object Swapper to 2.5.1  
Updated HD Local Map to 1.0.2  
Updated Papyrus Tweaks NG to 3.3  
Updated Better Third Person Selection - BTPS to 0.5.8  
Updated moreHUD SE to 4.1.2.0  
Updated moreHUD Inventory Edition to 1.0.20  
Updated Untarnished UI to 1.1  
Updated Pause After Load Unscripted NG to 1.1.1  
Updated Immersive Sounds Compendium - Sound Record Distributor...ded to 2.2  
Updated ISC SRDified - Clean esp to 2.0  
Updated Regional Sounds Expansion to 2.0  
Updated Reverb Interior Sounds Expansion to 1.4.0  
Updated Chapter II - Jeremy Soule Inspired Music to 3.1  
Updated Yet Another Music Merge - Chapter II Patch to 1.2.[E] - [E] is for ElmoRim edit  
Updated Static Mesh Improvement Mod Improvement Mod to 1.6  
Updated Assorted mesh fixes to 0.77  
Updated DynDOLOD Resources SE 3 to Alpha-30  
Updated Forgotten Retex Project to 8.0  
Updated Skyrim Landscape and Water Fixes to 7.4  
Updated Simplicity of Snow to 0.10  
Updated Water for ENB to 1.72  
Updated Maximum Carnage to 7.2  
Updated Maximum Carnage - Settings Loader to 1.1.0  
Updated Maximum Destruction to 1.3  
Updated Complemented Vanilla Smithing to 1.1
Updated Experience to 3.1.0  
Updated Simplest Horses (and other mounts) to 0.9.5  
Updated Bandit Lines Expansion to 1.06  
Updated Civil War Lines Expansion to 1.05  
Updated Mysticism - A Magic Overhaul to 2.1.6  
Updated Forceful Tongue - Shouts Overhaul to 3.0.8  
Updated Reliquary of Myth - Artifact Overhaul to 4.6.3  
Updated The Whispering Door - Quest Expansion to 1.10    
Updated The Whispering Door QE - EVGAT Patch to 1.10  
Updated SCAR - Skyrim Combos AI Revolution to 1.06a  
Updated Valhalla Combat to 1.3.3  
Updated Precision Creatures to 2  
Updated Conditional Expressions - Subtle Face Animations - Settings Loader to 1.1  
Updated Animated Eating Redux to 4.6  
Updated Animated Eating Redux SE edition - Settings Loader to 1.1  
Updated EVG Animated Traversal Skyrim Integration Patch to 1.2.2  
Updated Skyrim Unbound Reborn to 1.11.13  
Updated Lux to 5.3.1  
Updated Embers XD to 2.7.0  
Updated Dayspring Canyon Paper Map for FWMF to 1.7  
Updated Paper Sovngarde Map for FWMF to 1.7  
Updated Paper Blackreach Map for FWMF to 1.7  
Updated [E] Remove Maximum Carnage Message to 1.1 - Accounting for MC/MD update  
Updated ElmoRim - Facegen to 2.0  
Updated Synthesis to 0.25.2   
Updated Attack - MCO DXP to 1.6.0.3   
Updated DynDOLOD to alpha-110  
Updated ElmoRim CRP to 1.1 - Breton Knight Arrows use Adamant perks  
Updated [E] College Quest Tweaks - Forwarded records from AYOP - College of Winterhold  
Updated Adamant - A Perk Overhaul to 5.7.1  
Updated Mysticism - A Magic Overhaul to 2.2.1  
Updated Scion - A Vampire Overhaul to 2.1.2  
Updated Manbeast - A Werewolf Overhaul to 2.0  
Updated Attack MCO-DXP to 1.6.0.5  

Compacted form-ids and converted [E]*-plugins to ESP-FE
Configured SSE SSE Display Tweaks - High performance configuration - Borderless Fullscreen, no upscale  
Downloaded XeSS and FSR2 binaries and added them to UpscalerBasePlugin  
Enabled Ignore Missing Data flag on Immersive Sounds Compendium - Sound Record Distributor...ded   
Moved Jump Behavior Overhaul to Animations-separator  
Moved Player Spell (and Weapon) Lighting to VFX-separator  
Moved Player Spell Lighting - Mysticism Patch to VFX-separator  
Moved Rally's Candlelight and Magelight Fix to VFX-separator    
Moved Static Mesh Improvement Mod Improvement Mod beneath WM's Flora Fixes for CR purposes  
Regenerated DynDOLOD Output w/ High settings
Regenerated ElmoRim - Facegen 
Regenerated Nemesis Output  
Regenerated Synthesis Output  
Reinstalled Arctic - Frost Effects Redux - No ENB   
Reinstalled Inferno - Fire Effects Redux - No ENB  
Reinstalled Lux - No ENB  
Reinstalled Quick Light SE Alternate Meshes - No ENB  
Reinstalled Rally's Candlelight and Magelight Fix - 60 % reduced glow all options  
Reinstalled Storm Lightning for SSE and VR (Minty Lightning 2019) - Halo On all options  
Removed enbcache from [R] Root Files  
Removed EVGAT Tweaks from ElmoRim CRP  
Renamed Berserkyr ENB-separator to Lighting & ReShade  
Renamed [R] Controlmap to [E] ElmoRim Controlmap + rebuilt from scratch
Reran BethINI w/ High settings + manual tweaks




----0.1.6----  
Creation Kit Output - removed .esp-files  
ElmoRim CRP - Forwarded changes from Creation Kit .esp-files  

----0.1.5----  
Added Geirmund's Hall Pull Chain  

Removed Footprints - ENB  
Removed ENB Lava Particle Light Patch

Better Third Person Selection - Disabled Object Cycling by default    
Better Third Person Selectio - Increased Font Size
Bright waterfall fix for ENB - Water for ENB - Removed fxambsnowblowingplaneheavy.nif (Fix for GitHub Issue #9) 
ElmoRim CRP - Forwarded Simplest Horse records
ElmoRim CRP - Added fix for The Break of Dawn "death fall"     
Slightly Better - Old People Consistency - Moved to Late Loaders-separator        
Synthesis Output - Regenerated       
Timing is Everything - Changed Dawnguard start to 17    
unofficial performance optimized textures AKA (UPOT) - Moved to Framework-separator
  
----0.1.4----  
Tweaked enbseries.ini to improve performance
* ResolutionScale = 0.50
* SourceTexturesScale = 0.50
* SamplingRange = 0.50

----0.1.3----  
Switched nvngx_dlss.dll version to 2.4.0 which can be sourced from GitHub, ensuring the link doesn't break. 

----0.1.2----  
Change default settings of Sidequests of Skyrim  

----0.1.1----  
Reduced Sampling Range to 0.25 in ENB AO
Added Nvidia dll to Upscaler Base Plugin

----0.1.0----  
Updated Precision to 2.0.2
Updated Berserkyr ENB to 1.2.6
Updated ENB Binaries to 0.484
Updated Skyrim Upscaler to 1.1.0
Updated Upscaler Base Plugin to 1.0.6.1

Removed Shader Tools Updated

Regenerated Nemesis output



----0.0.7----  
Removed Movement Behavior Overhaul due to t-posing when using target-lock on  
Removed fControllerBufferDepth=0.01 from skyrim.ini

----0.0.6----  
Created separate test-profile  
Set resolution to 1920x1080

----0.0.5----  
Testpublish on WJ!  
Updated Skyrim Upscaler to 1.0.8  
Updated Upscaler Base Plugin to 1.0.4  
Set Widescreen/gamepad mods to always enabled in WJ UI  
Restructured github files  
Swapped cover image to .webp-format  

----0.0.4----   
Added Improvement Names Customized  

----0.0.31---  
Regenerated Nemesis output to include magelock  

----0.0.3----  
Reconfigured WJ tags through UI  
Archived all small [E]-files. Include in WJ-file instead  
Disabled woodcutter's axe recipe from SSOS in ElmoRim CRP  
Added Sidequests Of Skyrim Settings Loader  
Renamed output-mods with [O] prefix for filtering purposes  

----0.0.2----  
Reinstalled AI overhaul - Switched to full version  
Switched to Berserkyr ENB  
Added Skyrim Upscaler  
Removed smaller texture mods such as 3D rocks to improve performance  
Regenerated LOD outputs with medium quality  
Removed Draw2  
Added XPMSSE-styles & fixes  
Removed cathedral landscapes  
Added Folkvangr  
Generated grass cache for Folkvangr  
Removed Elden Equip  
Added Serio's Cycle Hotkeys  
Added 3rd Person Camera Stagger Remover  
Added Menu and Load Smoke Removed for ENB  
Added Ultrawide & Gamepad support separator + mods  
Created ElmoRim discord  
Created modlists.json and made pull request to https://github.com/wabbajack-tools/mod-lists/blob/master/repositories.json  

----0.0.1----  
Created ElmoRim dir  
Created ./Game Root dir  
Copied files from Steam Folder to Game Root dir  
Installed Creation Organizer plugin (Manual DL) w/ wabbajack JSON (MO2 DL) - https://www.nexusmods.com/skyrimspecialedition/mods/66329?tab=description  
Ran Creation Organizer  
Deleted CC content from ./Game Root/Data  
Downgraded CK - https://www.nexusmods.com/skyrimspecialedition/mods/67096?tab=files  
Downgraded game files (BOBW) - https://www.nexusmods.com/skyrimspecialedition/mods/57618?tab=files  
Reordered DLC in MO2 (match mod order to load order)  
Installed SKSE 2.0.20 binaries into Game Root  
Installed SKSE Scripts through MO2  
Copied MO2, Creation Organizer and SKSE archives to ./downloads  
Created Meta-files for MO2 and SKSE according to samples from https://github.com/wabbajack-tools/mod-lists/tree/master/custom_mo2_metadata  
Copied Creation Organizer Meta-file from LoTF  
Switched theme to dark  
Enabled Archive Parsing in MO2  
Learned that "query info" can be used for manually downloaded nexus-files. 
Installed xLodGEN + Output mod + meta  
Installed DynDOLOD + Output mod + meta  
Installed Nemesis + Output mod + meta  
Installed PCA SE + Output mod  
Installed xEdit + Output mod + meta  
Installed Synthesis + Output mod + meta  
Installed Engine Fixes + meta  
Created Framework-Separator + installed mods  
Created SKSE & .Net-Separator + installed mods  
Created Output-Separator + installed mods  
Created Bethesda Content-Separator  
Created --------------------- -Separator (Dev. Tools)  
Updated version-flags on mods  
Unticked flags-column in MO2  
Unpacked CK-scripts  
Installed Tweaked Creation Kit ini (Main file) into Game Root - https://www.nexusmods.com/skyrimspecialedition/mods/19817?tab=description  
Installed SSE Creation Kit Fixes (Main and Optional files) into Game Root + meta - https://www.nexusmods.com/skyrimspecialedition/mods/20061?tab=description  
Installed SSE Creation Kit Fonixdata Lip Sync Fix through MO2  
Learned Basic Git  
Created ElmoDFGD GitHub account  
Created ElmoRim repo  
Learned to edit .md-files  
Tweaked [Arisen](https://github.com/aljoxo/Arisen) WJ README to ElmoRim  
Created ElmoRim Profile  
Removed Default Profile  
Installed Bethini + meta to ./Tools  
Ran Bethini on High  
Installed Rootbuilder plugin  
Installed [R] ENB Binaries  
Installed [R] Controlmap  
Installed Plugin Sync plugin  
Added shortcuts to MO2 toolbar  
Created Visual Baseline-Separator  
Created Mesh Improvements-Separator  
Created Sound-Separartor  
Created Music-Separator    
Created VFX-Separator  
Created Environment-Separator  
Created Fixes-Separator + installed mods  
Created Tweaks-Separator + installed mods  
Created Interface-Separator + installed mods  
Added SynOblivionInteractionIcons Synthesis Patch  
Created Controls-Separator + installed mods  
Set Nemesis, DynDOLOD and xLODGen executables to run in Win 8 Comp.mode  
Ported Appearance-Separator in its entirety from ElmoRim 5    
Added Tavern AI Fix commands to Autorun    
Created Gameplay-separator + installed mods  
Added fBookOpenTime=200 to [Interface] in skyrim.ini  
Created QoL-Separator + installed mods  
Created Animations-Separator + installed mods  
Created Loot, Gear & Encounters-Separator + installed mods  
Created SimonRim-Separator + installed mods  
Created Combat-Separator + installed mods  
Added fInAirFallingCharGravityMult=1.8 to [HAVOK] in skyrim.ini  
Added fControllerBufferDepth=0.01 to [CONTROLS] in skyrim.ini  
Added Late Loaders-Separator  
Ported ElmoRim CRP  
Added WABBAJACK_NOMATCH_INCLUDE tagfile to ./Game Root/enbcache  
Added WABBAJACK_IGNORE tagfile to ./Tools/_tmp  
Added Map-Separator + installed mods  
Configured grass cache settings (modpage + script to list relevant worldspaces)  
Tweaked inis and nvidia control panel settings according to Patrician ENB instructions  
Created Patrician ENB-Separator + installed mods  
Edited meta files to show tools as installed  
set bVATSDisable = 1 under [VATS] in skyrim.ini  
Set ElmoRim to play in fullscreen.  
Followed guide at https://github.com/The-Animonculory/Modding-Resources/blob/main/Regenerating%20Faces%20in%20the%20Creation%20Kit.md for Facegen  
Added https://github.com/caiobraz/Synth-NPCs-Face-Data Synthesis repo  
Set TintMaskResolution=1024 in Skyrim64_test.ini  
Installed SSE Creation Kit Fixes Update  
Installed Cathedral Assets Optimizer  
Installed CAO-profile from https://github.com/The-Animonculory/Modding-Resources/blob/main/BSA%20Creation.7z?raw=true  
Adjusted CCARA>2066 (snowflake) to check for Solas  
Uploaded Facegen and Precision patch to Nexus  
Optimized wabbajack file size using https://github.com/wabbajack-tools/wiki/wiki/06.-Keeping-the-Game-Folder-clean and wabbajack cmd wabbajack-cli.exe modlist-report -i {path to .wabbajack file}  




