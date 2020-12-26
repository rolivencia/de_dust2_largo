# de_dust2_largo

![de_dust2_largo caption](https://raw.githubusercontent.com/rolivencia/de_dust2_largo/master/csgo/dist/thumb2328564968.jpg?raw=true)

Counter-Strike 1.6 custom map. Spin-off of the original de_dust2 map included in CS 1.6, with the added restriction of the players only being able to move through the side passage that connects the T base and CT base.

It is nicknamed in this fashion since in Argentina we dubbed the "side" passage as "largo". 

Altough the suffix of the map is "de_", actually it is not possible to plant the bomb and the map is of deathmatch type. It only bears the suffix because of, let's say, "marketing" reasons.

This map was developed in the southern-hemisphere summer of 2005 while I was 15 years old. In the repository you can find the compiled .bsp version and also the original sources that I used to create the map.

To get the de_dust2 source, I just decompiled the original de_dust2 map included in CS 1.6 and rebuilt it from scratch, including only the side passage. The original text file included in the distributable version of the map is included below.

The CSGO version, with its source files, is included under the /csgo folder. The link for the Workshop version of the CSGO remake is available at https://steamcommunity.com/sharedfiles/filedetails/?id=2328564968

### 2020-12-03 Update
Added remake version for CSGO. Splitted content in two folders for the CS 1.6 and CSGO versions.

### 2020-09-03 Update
Added new overview by Ezequiel-TM (https://store.steampowered.com/wishlist/id/tremolomeasure)

### 2020-08-30 Update
Added screenshots by Ezequiel-TM (https://store.steampowered.com/wishlist/id/tremolomeasure)

## What is each file and what does each folder contain?

### CS 1.6 version:

.nav - It's the file that bots used to know how to navigate through a map. It is required for the 1.6 bots to avoid them behaving awkwardly.

.res - Lists the resources required by the game to be able to download all the map dependencies when downloading the map from a server when you don't have it in your computer.

.bsp - Compiled map. Ready to run in CS 1.6

.rmf - Source of the map. Can be opened with Valve Hammer Editor 3.5. It requires importing the Half-Life 1.1.1.0 textures (halflife.wad) and de_dust2 textures (de_dust2.wad)

.txt - Info file.

### CSGO version:

/dist folder - Contains the map as it is available on the Workshop, with a packaged .bsp file and screenshots.
/radar folder - Contains the .psd file to modify and the .dds file that is bundled to display the in-game radar and the loading splash of the map.
/materials folder - Contains all the custom textures used to create the map.
/src folder - Contains the unpacked .bsp file, the compilation log and the .vmf file that can be opened using the Hammer Editor.

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

Adaptation of the original "de_dust2_largo" developed by me, under the moniker "mapper22", for Counter-Strike 1.6 as a modification of the original "de_dust" by Dave Johnston, aka DaveJ.

Detailed textures taken from de_dust2_upscaled, by 3kliksphilip, based on the originals from Chris "MacMan" Ashton.

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
