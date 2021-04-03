# de_dust2_largo

![de_dust2_largo caption](https://user-images.githubusercontent.com/32349705/113464063-6926e680-9400-11eb-977a-12d774fb89ca.jpg)

Counter-Strike 1.6 custom map. Spin-off of the original de_dust2 map included in CS 1.6, with the added restriction of the players only being able to move through the side passage that connects the T base and CT base.

It is nicknamed in this fashion since in Argentina we dubbed the "side" passage as "largo". 

Altough the suffix of the map is "de_", actually it is not possible to plant the bomb and the map is of deathmatch type. It only bears the suffix because of, let's say, "marketing" reasons.

This map was developed in the southern-hemisphere summer of 2005 while I was 15 years old. In the repository you can find the compiled .bsp version and also the original sources that I used to create the map.

To get the de_dust2 source, I just decompiled the original de_dust2 map included in CS 1.6 and rebuilt it from scratch, including only the side passage.
The original text file included in the distributable version of the map is included below.

Each version has their own folder.
- **/cs** is for Counter-Strike 1.6.
- **/csgo** is for Counter-Strike: Global Offensive.

The source files for both versions are in the subfolder **/src** of the respective version.

The link for the Workshop version of the CS:GO remake is available at the [CSGO Workshop](https://steamcommunity.com/sharedfiles/filedetails/?id=2328564968).

Contributions to refactor and improve both the CS 1.6 & CS:GO maps were made by Maxwell Ruiz, aka [WorstAquaPlayer](https://steamcommunity.com/id/AquaPlayer).

Changelog available in CHANGELOG.md.

## What is each file and what does each folder contain?

### CS:

**maps/de_dust2_largo.bsp** - Compiled map. Ready to run in Counter-Strike 1.6

**maps/de_dust2_largo.nav** - It's the file that bots used to know how to navigate through a map. It is required for the 1.6 bots to avoid them behaving awkwardly.

**maps/de_dust2_largo.res** - Lists the resources required by the game to be able to download all the map dependencies when downloading the map from a server when you don't have it in your computer.

**maps/de_dust2_largo.txt** - Info file that displays after starting/joining a game.

**src/de_dust2_largo.wad** - Wad file that contains the used textures that were embedded in the original de_dust2 bsp and required extracting.

**src/de_dust2_largo.rmf** - Source of the map for Counter-Strike 1.6. Can be opened with Valve Hammer Editor 3.5. It requires importing the Half-Life 1.1.1.0 textures (halflife.wad), de_dust2 textures (de_dust2_largo.wad) and de_dust textures (cs_dust.wad). Since changes were introduced to the original 2005 version of the .rmf file and the compilation presets are lost, it is not possible to generate the same .bsp file that is available on the web. Be careful when distributing compilations based on this .rmf.

**src/Compile Options JACK.png** - Screenshot that shows the settings that the map was compiled.

### CSGO:

**/dist** folder - Contains the map as it is available on the Workshop, with a packaged **.bsp** file with all the required materials and screenshots.

**/materials** folder - Contains all the custom textures used to create the map.

**/radar** folder - Contains the **.psd** file to modify, the **.dds** file and **.txt** file that is bundled to display the in-game radar and the loading splash of the map.

**/src** folder - Contains the unpacked .bsp file, the compilation log and the .vmf file that can be opened using the Hammer Editor.

## Readme files

### Translation of original de_dust2_largo [Final Version] for CS 1.6

**By Ramiro Olivencia alias Mapper22, alias BruceDickinson (mapper22@gmail.com)**      

**Map name:**   	de_dust2_largo

**Size:**			Around 200kb

**Mod:**			Counter-Strike 1.6 & Counter-Strike: Condition Zero
	
**Editor:**			Valve Hammer Editor v3.5

**Compilation time:** 	approximately 10 minutes

**Tools:** 			ZHLT v3.2.1

**Other maps by me:**	gt_legov2, mp22_warehouse, de_sandtemple, de_minicbble
 
_The original readme file is included as a source in this repository, by the name de_dust2_largo.txt_

### CSGO version readme file:

Adaptation of the original "de_dust2_largo" developed by Ramiro Olivencia, aka [Murray](https://steamcommunity.com/id/mapper22/), 
The original version was developed by me under the moniker "mapper22" for Counter-Strike 1.6 as a modification of the original "de_dust" by Dave Johnston, aka DaveJ.

Contributions to refactor and improve the CSGO port were made by Maxwell Ruiz, aka [WorstAquaPlayer](https://steamcommunity.com/id/AquaPlayer).

**Version 1.1 - 02/04/2020**

Complete map rework. Adapted geometry and lightning to resemble the original de_dust2_largo from CS 1.6.

**Version 1.0 - 26/12/2020 (15th anniversary)**

Supported playing modes:
- Deathmatch
- Classic
- Flying Scoutsman
- Arms Race
- Custom

Spawn point numbers:
- 10 T + 10 CT for Classic/Flying Scoutsman/Arms Race/Custom
- 20 for Deathmatch