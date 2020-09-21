# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

## [87] - 2020-09-21
### Added
- hd interfaces

### Fixed
- z-ordering problems on interfaces

## [86] - 2020-09-20
### Fixed
- fix launcher (oopsie)

## [85] - 2020-09-20
### Added
- World hopping

### Fixed
- _white water_ when High Water Detail is enabled.
- players now have most of their limbs in the correct places!
- various floors have been fixed (Overlay/Underlay)
- the landscapers have come again, various unwanted grass objects have been removed
- fixed the door leading to West Ardy(hdos/issues#75)

### Changed
- overgrown cats have been replaced with normal cats for the time being.

## [84] - 2020-09-16
### Changed
- update cache

## [83] - 2020-09-16
### Added
- HDR (High Detail Rendering)
- Bloom (Makes things glow)
* _HDR and Bloom can be toggled using the `:hdr` command (it will be persisted)_
### Fixed
- Minimap scene icons have been restored
- Corp pet scaling issue
### Changed
- improve GL model rendering performance
- improve mipmap generation
- removed rain temporarily from corp lair

## [82] - 2020-09-13
### Fixed
- Lumbridge has landscaped its floors (no more random grass spawns)
- Saradomin Sword has been upgraded
- Saradomin GodSword has been upgraded
- Missing tiles inside Corp have been fixed
- Fixed Corp minimap icons
### Changed
- **Dragon Claws are now HD**


## [81] - 2020-09-12
### Changed
- **Corp is now HD**
### Fixed
- Lumbridge has landscaped its roof (no more random grass spawns)

## [80] - 2020-09-11
### Changed
- **God Wars (and associated items) are now fully\* restored**
- Crossbow movements are now HD
- Punching is now HD
- (*) Bloodveld, Pyrefiend, Icefiend were downgraded to fix glitches.
  They will be restored later on.

## [79] - 2020-09-10
### Changed
- **GE is now HD**
- Restore original water color
- update cache

## [78] - 2020-09-8
### Fixed
- ectophial teleport crash

## [77] - 2020-09-7
### Fixed
- home teleport animation
### Changed
- upgrade teleport animation
- Floors are now **100%** restored!

*Current Progress*:

| type | total | percent |
|------|--------|---------|
| OBJECTS | 24,589 | 96.02% |
| NPCS | 5,782 | 95.80% |
| ANIMATIONS | 6,503 | 93.75% |
| ITEMS | 11,751 | 100% |
| KITS | 152 | 100% |
| GRAPHICS | 1,120 | 94.22% |
| UNDERLAY | 97 | 100% |
| OVERLAY | 173 | 100% |


## [76] - 2020-09-5
### Fixed
- [equipment options](hdos/issues#66)
### Changed
- **MANY** graphical improvements.
This milestone marks the restoration at **95%** complete.
This does *not* include 'backports' (GE,GWD,Corp), though
they are restored to some random extents, they were not the focus
of this update. (They will all be added very soon!)

| type | total | percent |
|------|--------|---------|
| OBJECTS | 24,589 | 96.02% |
| NPCS  | 5,782 | 95.80% |
| ANIMATIONS | 6,503 | 93.75% |
| ITEMS  | 11,751 | 100% |
| KITS  | 152 | 100% |
| GRAPHICS  | 1,120 | 94.22% |

_Floors will be completed on in the next update._

If you guys want even more HD, dont forget about the `:unsafe` command.



## [75] - 2020-09-2
### Fixed
- update cache

## [74] - 2020-08-27
### Fixed
- [game links](hdos/issues#65)
- [auto chat](hdos/issues#61)
- [system update time](hdos/issues#63)

## [73] - 2020-08-26
### Fixed
- update protocol to 191

## [72] - 2020-08-24
### Added
- Discord Presence
- [`:zoom` command](hdos/issues#27). 
    This will increase the max zoom-out of the client.
    You can configure how much to increase, and reset the limit:
   - `:zoom` will increase the limit by 48 (default)
   - `:zoom X` will increase the limit by X (caped to 64)
   - `:zoom 0` will reset the limit back to normal
- error display (ex: cashes)
- `:aa` command. Set the MSAA sample buffers.
    - `:aa 0` will disable anti-aliasing
    - `:aa 1` MSAAx2
    - `:aa 2` MSAAx4
    - `:aa 3` MSAAx8
    - `:aa 4` MSAAx16
    - `:aa 5` MSAAx32
### Fixed
- feet clipping on most objects
### Changed
- HD GE NPCs

## [71] - 2020-08-22
### Added
- `:afk` command to toggle idle-logout
- `:unsafe` command to toggle unsafe animations (enables more HD, might need to re-log)
### Fixed
- fix player animations that were downgraded in v69
### Changed
- graphics backend improvements, and stability.
  This provides a wide range of upgrades to objects and npcs:
    - notable objects: fires, lights, rocks, flags
    - notable npcs: (unsafe) TzHaar, some slayer monsters, fishing pools

## [70] - 2020-08-18
### Changed
- update JOGL to 2.3.2

## [69] - 2020-08-18
### Fixed
- [invisible players](hdos/issues#12)
- [player options](hdos/issues#12)
- [misc. animations](hdos/issues#1)

## [68] - 2020-08-13
### Added
- god wars items
- spirit shields

## [67] - 2020-08-12
### Changes
- update cache

## [66] - 2020-08-12
### Fixed
- [Idle Logout Timer](hdos/issues#4)
- [Account Type Icons](hdos/issues#2)
- [item on player](hdos/issues#8)
- soundfx packet
- [follower option priority](hdos/issues#5)

## [65] - 2020-08-11
### Changes
- fix auth problems

## [64] - 2020-08-11
### Changes
- refine updating mechanisms

## [63] - 2020-08-11
### Changes
- new version control backend

## [62] - 2020-08-09
### Added
- `:issue` command to help report a issue

### Fixed
- [Tab Key](hdos/issues#6)