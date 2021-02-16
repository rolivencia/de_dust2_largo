# Changelog
All notable changes to this project will be documented in this file.

The format tries to be based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

## 2021-02-15
### Added
- [CS 1.6] Pull Request #8 is merged:
   - **Compile Options JACK.png**: Screenshot that shows how the settings were adjusted to compile **de_dust2_largo.rmf**.

### Changed
- [CS 1.6] Pull Request #8 is merged:
   - **de_dust2_largo.rmf**: The RMF has been entirely replaced by one based on the original de_dust2 source file.<br />
   The changes were made to the de_dust2 RMF to remain as faithful to the original de_dust2_largo BSP as possible are:<br />
       - Closed up parts of the map in the same parts they were closed in the original BSP.
       - Added the brush near T spawn.
       - Brushes near CT spawn were moved.
       - Textures that make reference to the bombsite were replaced by the clean versions.
   - **de_dust2_largo.wad**: WAD file replaced, it contains only the used textures of this map that are packed in the original de_dust2 BSP.

## 2021-02-15
### Fixed
- [CS 1.6] Pull Request #4 is merged:
   - **de_dust2_largo.rmf**:
       - Added clip brushes near the sky to prevent players from jumping to the wall borders.
       - Wrong placed NULL textures now show the intended texture.
       - Crates near CT spawn are moved to remain faithful to the original BSP.
       - Added a brush near T spawn to remain faithful to the original BSP.<br /><br />
- [CS 1.6] Pull Request #7 is merged:
   - **de_dust2_largo.wad**: WAD file added, it contains the missing textures from issue #2.
   - **de_dust2_largo.rmf**: Modified the position of the GameHelper ad brushes to remain faithful to the original de_dust2.

## 2020-12-03
### Added
- [CS:GO] Added remake version for CS:GO.

### Changed
- [CS 1.6 & CS:GO] Splitted content in two folders for the CS 1.6 and CSGO versions.

## 2020-09-03
### Added
- [CS 1.6] Added new overview by Ezequiel-TM (https://store.steampowered.com/wishlist/id/tremolomeasure)

## 2020-08-30
### Added
- [CS 1.6] Added screenshots by Ezequiel-TM (https://store.steampowered.com/wishlist/id/tremolomeasure)
