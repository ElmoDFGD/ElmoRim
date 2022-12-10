# ElmoRim Wabbajack Dev-Diary
## 2d0

* High Level Enemies Redux & Heritage Enemies 2
* Favourite Howls Menu  
* Controller support
* Ultrawide support
* IED instructions
* map marker wrong height
* bow when attacking dawnguard instruction
* Reshade for DoF
* Added fInAirFallingCharGravityMult=1.8 to [HAVOK] in skyrim.ini
* Added fControllerBufferDepth=0.01 to [CONTROLS] in skyrim.ini
* How to distirbute upscaler
* delete speemultfix .esp
* test with HDR
* add AVL for gilded ebony

## Changelog

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
set bVATSDisable = 1
Set ElmoRim to play in fullscreen.
Activated NIS in Gefore Experience (75% Scaling)
Activated Sharpening in Geforce Control Panel (50%)
Followed guide at https://github.com/The-Animonculory/Modding-Resources/blob/main/Regenerating%20Faces%20in%20the%20Creation%20Kit.md for Facegen
Added https://github.com/caiobraz/Synth-NPCs-Face-Data Synthesis repo
Set TintMaskResolution=1024 in Skyrim64_test.ini
Installed SSE Creation Kit Fixes Update
Installed Cathedral Assets Optimizer
Installed CAO-profile from https://github.com/The-Animonculory/Modding-Resources/blob/main/BSA%20Creation.7z?raw=true
Adjusted CCARA>2066 (snowflake) to check for Solas
Uploaded Facegen and Precision patch to Nexus
Optimized wabbajack file size using https://github.com/wabbajack-tools/wiki/wiki/06.-Keeping-the-Game-Folder-clean and wabbajack cmd wabbajack-cli.exe modlist-report -i {path to .wabbajack file}



----0.0.2----
Reinstalled AI overhaul - Switched to full version
Switched to Berserkyr ENB
Added Skyrim Upscaler
Removed smaller texture mods such as 3D rocks to improve performance.