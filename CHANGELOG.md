# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]


## [130] - 2020-12-8
### Changed
#### **CASTLE WARS HAS BEEN RESTORED!**

        This is marks our first area restore, as we begin to finish off the restoration!  
        We were designing and refining our tooling, along with engine work, as we did castle wars,  
        so this update took some time to do! Future updates should not take nearly as long.  
        Thank you for your patience!

We collected some spoiler images.  
We will replace this with a offical gallery soon!  
- [OS](https://imgur.com/Th4SN2k)
- [v129 (before)](https://imgur.com/KaNZMGZ)
- [v130 (after)](https://imgur.com/cv9BQzV)
- [2008 (goal)](https://imgur.com/F9pVyQS)

### Added
- Free Cam (Orb Of Oculus)
### Changed
- `Unsafe Mode` should now permit more things to HD.

## [129] - 2020-12-2
### Changed
- Updated cache
### Added
- Artist: Dump model tool can be toggled with `:dumpmodels` command 

## [128] - 2020-11-25
### Changed
- Updated cache

## [127] - 2020-11-23
### Fixed
- Players have visited the chiropractor again!  
  They now have their heads and ankles in the correct spots!
### Added
- Artist: The players gender can be toggled with the `:gender` command (how progressive!)
- Artist: HD models can now be hot-swapped
- Artist: HD models can now use OS textures

## [126] - 2020-11-22
### Added
- Art mode
### Changed
- Remove `Exit` option on macOS

## [125] - 2020-11-20
### Fixed
- Crossbow animations are now HD
- The MenuBar should render in the correct spot on MacOS? (hdos/issues#307)
- Keyboard shortcuts on macOS will now use the Command key. (fixes hdos/issues#308)
- Fix Tab key in Fullscreen (fixes hdos/issues#302)
- The camel's roller blades have been removed (fixes hdos/issues#317)
- Fixed straggler hand issue (fixes hdos/issues#286)

## [124] - 2020-11-18
### Changed
- Updated cache
- The `:aa` command will now be saved between restarts

## [123] - 2020-11-16
### Changed
- Set the minimum size of the client to fixed-size (765 x 503)
- The `Walk here` action will now use the tile where the menu was opened. This is to match standard client behavior. (fixes hdos/issues#289)
- General interactions will no longer verify the target is reachable. This is to match standard client behavior.
### Fixed
- The `:aa` command will now clamp to your GPUs maximum supported sampling (fixes hdos/issues#290)
- Fix linux freezing when entering HD mode on boot. (fixes hdos/issues#137)
- Fix linux 2fa prompt not displaying. (fixes hdos/issues#140)
- HP bar is now 100% accurate (fixes hdos/issues#287 hdos/issues#144)

## [122] - 2020-11-16
### Fixed
- Eadgar's Ruse: Kitchen drawers have been restored (fixes hdos/issues#280)
- You will no longer get stuck when leaving troll stronghold (fixes hdos/issues#278)
- Fixed the intended visuals of gauntlet floors. Disco room improved. (fixes hdos/issues#270)
- Skybox color has been upgraded, when going deep into the jungle (fixes hdos/issues#259)
- Fixed Father Urhney's roof (fixes hdos/issues#254)
- The pharaohs have called apon the gods (me and brain) to fix their doors (fixes hdos/issues#256)
- Fixed the icon of rock-climbing boots (fixes hdos/issues#247)
- Abyss entrances are no longer gates... (fixes hdos/issues#248)
- Fixed a crash caused by models translations within interfaces (fixes hdos/issues#284)
- Fixed animation sound effect audio (fixes hdos/issues#274)
- Many NPC's have regrown their limbs (fixes hdos/issues#257 hdos/issues#151 hdos/issues#286 hdos/issues#214 hdos/issues#212)
- Even more body parts have been acquired (fixes hdos/issues#150 hdos/issues#152)

## [121] - 2020-11-14
### Fixed
- Fixed a straggler cat
- Fixed the stairs leading to the viewing platform at Castle Wars
- World map surface now preforming much better (fixes hdos/issues#3)
- It must be May, roses have reappeared at Edge Monastery (fixes hdos/issues#264) 
- Fixed fire near Eagle' Peak Mountain (fixes hdos/issues#265) 
- Canafis floors are no longer moving (fixes hdos/issues#263)
- Fixed the missing shortcut on the north side of Yanille (fixes hdos/issues#262)


- ***AA BLOOM*** (fixes hdos/issues#107) 
    > Multisampling now work in post processing (BLOOM)

- ***FIXED PLAYER TELEPORT ON REGION LOAD***  (fixes hdos/issues#37) 
    > This issue was another allusive one!  
      Thanks to **GottaSlay** for helping us reproduce the issue consistently!

- ***AUDIO HAS BEEN FIXED!*** (fixes hdos/issues#106 hdos/issues#172) 
    > The audio engine has been reworked, and no longer persists crackling!

## [120] - 2020-11-11
### Changed
- update cache
### Fixed
- Cairn Isle cave now has an exit (fixes hdos/issues#242)
- Tomb of Rashiliyia rocks are now visible and scalable (fixes hdos/issues#241)

## [119] - 2020-11-10
### Changed
- Remove keybinds from the Help menu (fixes hdos/issues#227)
### Fixed
- Fix layered animations (fixes hdos/issues#158)
- The viewport is now fully visible in the smoke dungeon (fixes hdos/issues#223)
- Messages will now stay cleared, when hopping or relogging (fixes hdos/issues#133)
- Jungle potion cave can now be exited (fixes hdos/issues#229)
- Fally has been once again set right ((fixes hdos/issues#229) )
##### Last Man Standing
- items are now HD (fixes hdos/issues#175)
- A crash has been resolved
- fog now rendering correctly in SD mode
- fog is now working in HD mode (fixes hdos/issues#174)


## [118] - 2020-11-9
### Fixed
- Fixed spell-on-object interactions (fixes hdos/issues#191)
- you may now leave the Spirit Grotto after entering (fix hdos/issues#157)
- Fixed zulrah gnome glitching out (fix hdos/issues#161)
- Charge spell now has the correct graphic (fix hdos/issues#164)
- You may now see players underneath yourself when not self rendering (fix hdos/issues#207)
- fixed an issue with the wall kits inside the dwarven mines (fix hdos/issues#206)
- Arrows now display correctly on the ground (fix hdos/issues#211)
- Fixed an issue with rotated pillars at g.e. (fix hdos/issues#215)
- Olaf Hradson's fire is now animating as it should (fix hdos/issues#196)
- Cats in POH pet house are now upgraded (fix hdos/issues#205)
- Fixed various overlays (fix hdos/issues#169)

## [117] - 2020-11-7
### Added
- add `Draw Debug` option for verbose debug information
### Changed
- bloom will now work in dark areas just as well as light
### Fixed
##### Taverly Dungeon
    - fixed the gate leading to the Cauldron of Thunder
    - fixed the tiles inside of the black dragon area
    - fixed the agility shortcut pipe
- fixed Prifddinas portals
- wilderness building is now looking accurate
- fixed all godwars doors, they are now enterable
- necklaces may now be seen through OS bodies 
- fixed Wintertodt and corrected Vorkath
- fix full screen world map stall (fix hdos/issues#130)


## [116] - 2020-11-5
### Changed
- update cache

## [115] - 2020-11-5
### Changed
- Exiting the client will now prompt to confirm (fixes hdos/issues#135)
### Fixed
- Fullscreen now works with displays > 1080p

## [114] - 2020-11-5
### Changed
- Improve scene rendering performance (+15% FPS boost)
### Fixed
- Login screen crash has been fixed (fixes hdos/issues#131)

## [113] - 2020-11-4
### Added
- Added `Lock fullscreen` setting (fixes hdos/issues#114)
### Changed
- The client can now exit fullscreen by pressing CTRL+F 
### Removed
- Removed `Light Theme` setting keybind
- Removed `Show MenuBar` setting keybind
### Fixed
- The Stealing creation guys wanted their nets back... (fixes hdos/issues#126)
- Fix private message name spacing (fixes hdos/issues#9)
- Fix league clan chat (fixes hdos/issues#124)
- MenuBar clicking is now more responsive, and should not ignore clicks (fixes hdos/issues#125)
- KeyBinds now work when in fullscreen

## [112] - 2020-11-3
### Fixed
- **Fixed Make-X**  (fixes hdos/issues#127)

This bug was the most allusive so far!  
It's only thanks our community of testers that it was fix.  
This brings us great joy to see and experience.  
We would like to thank our testers who helped directly:  

| **TESTER** |
|----------|
|Birthday Cat|
|Surg1n|
|Ling|
|Gloc|


## [111] - 2020-11-2
### Added
- Hint arrows (fixes hdos/issues#122)
### Fixed
- Remove duplicate keybind: `Control T`

## [110] - 2020-11-2
### Added
- Add Hide Username setting
- Add Save Username setting
- The following settings will now save between restarts
  - Hide Username
  - Force HDR
  - Tween
### Fixed
- Purged pink skirt issues. All pink skirts should now be resolved. (fixes hdos/issues#99)
- Fixed trap door in HAM hideout, quest is now completable. (fixes hdos/issues#103)
- Fixed world list, now displaying the correct flag (fixes hdos/issues#100)
- Fixed invisible door issue leading into East Ardy (fixes hdos/issues#75)
- Fixed broken interface buttons (fixes hdos/issues#110 hdos/issues#64 hdos/issues#11)
- Fixed Environment in Ferox Enclave (fixes hdos/issues#115)
- Fixed Alpha issue with OS Models (fixes hdos/issues#84)
- Fixed Lumbridge basement tunnels (fixes hdos/issues#117)
- Clue Scrolls have been updated to use the new sprites over the old (fixes hdos/issues#102)
- Fixed appearance of COX door. (Click box WIP)
- Fixed Vorkath's nest flickering issue. (fixes hdos/issues#96)


## [109] - 2020-10-31
### Fixed
- Corrected the water inside of DKS and other various places
- Disable HDR in Fixed-HD window mode (temporary solution) (fixes hdos/issues#94)
- HP bar
### Changed
- Temporarily removed the waterfall in the Enchanted Valley  
- Rename `Force Tween` to `Tween` in the menu UI

## [108] - 2020-10-30
### Fixed
- Fix Zulrah atmosphere

## [107] - 2020-10-30
### Fixed
- Correct Theater Of Blood and Darkmeyer environments
- Fixed stack-able items (Fletching items [arrows/bolts] appearing as pink skirts)(fixes hdos/issues#95)

## [106] - 2020-10-29
### Added
- Add GL debug data to FPS debug
### Changed
- Collapse About menu
- Performance improvements for dense areas
### Fixed
- Remove duplicate keybindings
- Fix random crashing when teleporting from POH to GE (_finally_!)
- Fix Tutorial Island crashing (fixes hdos/issues#89)
- Fixed fairy ring interface showing pants as (r) (fixes hdos/issues#90)
- Fixed various overlays (fixes hdos/issues#91)


## [105] - 2020-10-28
### Added
- added acknowledgement section (credits) 
### Changed
- removed various unneeded logs


## [104] - 2020-10-28
### Fixed
- fix script crashing due to instruction limits.

## [103] - 2020-10-28
### Changed
- update cache

## [102] - 2020-10-28
### Added
- Force HDR option
- Unsafe operations option
- UI Tooltips
### Changed
- Force tweening will no longer apply to HD animations
### Fixed
- Tab key
- Crash screen
- Shanty pass tent 
- Fremennik Slayer Dungeon
- Misc see-through floor (mainly around Zeah)

## [101] - 2020-10-24
### Added
- Dark/Light Theme setting
- Ability to change windows modes from the toolbar
- UI Options:  
    - Bloom (HDR)
    - No Logout
    - Zoom Limit
    - Draw FPS
    - Disable HUD
    - Render Self
    - Custom Fog
### Changed
- Use Dark Theme by default in the UI
### Fixed
- JVM crash on close
- Closing is now faster and more responsive
- Discord presence should clear sooner on close
- Networking bug when opening specific web pages
- LAF not loading when ran in direct mode from the launcher (native-launcher)

## [100] - 2020-10-22
### Added
- New UI (work in progress)
### Changed
- update protocol to 192
- update launcher to v1.0.4
- update cache
- the client will now open in the center of the screen instead of the top-left
### Fixed
- memory leak whenever windows users try to stream with discord. (fixes hdos/issues#87)

## [99] - 2020-10-14
### Added
- **New Launcher!**  
Please see the [issues release](https://gitlab.com/hdos/issues/-/releases/) for more information.

## [98] - 2020-10-14
### Changed
- update cache
### Added
-further preparations for new launcher 

## [97] - 2020-10-08
### Added
- preparations for new launcher

## [96] - 2020-10-07
### Changed
- update cache

## [95] - 2020-10-05
##@ Fixed
- crashing on world hop
- crashing in LMS

## [94] - 2020-10-03
### Changed
- refine compilation output
### Fixed
- fixed floating npcs in the login screen (fixes hdos/issues#13)
- custom login responses

## [93] - 2020-09-30
### Changed
- update cache
### Fixed
- dark lighting in varrock 

## [92] - 2020-09-29
### Added
- **Mac support**
### Changed
- update jogl to 2.4.0-rc-20200429
- swap out standard water color to the lighter one.
- disable castle wars high-water-detail for now.
- improve default environment/atmosphere (ex: bright caves, wintertod)

## [91] - 2020-09-28
### Fixed
- clicked tile when in HD mode
- crashing when switching between fullscreen
- `:afk` command now works correctly

## [90] - 2020-09-26
### Added
- SD mode zoom
### Fixed
- G.e. npcs have been further upgraded

## [89] - 2020-09-24
### Added
- **Linux support**
### Changed
- update cache
### Fixed
- SD mode (_WIP, zoom next update_)

## [88] - 2020-09-22
### Added
- **hd chatheads**

### Fixed
- blue water flickering in Morytania 

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