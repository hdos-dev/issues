# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]

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