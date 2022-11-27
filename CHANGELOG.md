# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

## [Unreleased]
### Changed
- The heroes guild and the heroes guild's dungeon have been restored (fixes hdos/issues#605)
  - MapFilter has also been improved for the dungeon
- Witch's House dungeon has been restored
- Burthorpe has been restored
  - Also restored the Zamorakian temple and fixed the Falador wall (fixes hdos/issues#807)
  - Burthorpe's games room has also been restored, but will see a rework if it becomes relevant content
- Rogues' Den has been restored
  - MapFilter has also been improved
- Uzer, the Uzer ruins and the Shadow realm have been restored (fixes hdos/issues#374)
- The poll booth flag has been textured
- The following improvements have been made to Taverley (fixes hdos/issues#550):
  - Stools are no longer clipping inside tables (fixes hdos/issues#633)
  - Stools, staircases, bookcases and sword racks have been upgraded
  - A missing roof has been added
- Quick Settings now automatically clears any active search when the side panel is collapsed
### Fixed
- Fix a bug where plugins and other UI elements break on client reset (fixes hdos/issues#1300)
- Quick settings no longer requires pressing double-shift twice to close
- Fix a bug where the minimum size of the client was wrong after opening/closing the sidebar (fixes hdos/issues#1349)
- Fix a bug where plugins would disappear within the quick settings if the user changes window modes after starting the client
- Improve transparency rendering for landscape scenery
- The following improvements have been made to the Edgeville Dungeon:
  - The sign on the door is now visible on both sides (fixes hdos/issues#424)
  - The columns now more accurately reflect collision
  - Several excessive stalactites have been removed
  - All mining rocks are now stay upgraded when mined
- The "strange hole" from the "A Porcine of Interest" quest is now also fixed prior to completing the quest
- A fence in Lumbridge has been replaced by the correct type
- The fireplace in the Lumbridge general store no longer shines through the wall
- The mining rocks in the western part of the Lumbridge swamp should now also stay upgraded when mined


## [306] 2022-25-11
### Fixed
- Agility plugin: Fix broken shortcut regression from v305

## [305] 2022-25-11
### Changed
- Restored Al-Kharid and Shantay Pass (fixes hdos/issues#1395)
  - Captain Dalbur has also been restored
- 86 different skeletons have been restored (including the Skeletal Mystics from CoX!) (fixes hdos/issues#1403)
- Gargoyles are now upgraded when they shatter
- Numerous improvements have been made to Lumbridge:
  - The downgraded tiles in the Lumbridge kitchen and -basement have been upgraded
  - Several walls that are adjacent to doors have been replaced by the compatible variants
  - The two stairs on the upmost floor of the Lumbridge castle have been fixed
  - Restored the interior inside the Lumbridge castle bank
  - The cannonballs displayed as a ladder by the Lumbridge castle bank have been put back
    - The ladder has been moved to the other side
  - Restored the back entrance of the Lumbridge courtyard (and re-added the tower)
  - Dozens of models have been restored or upgraded
  - The king's statue has been remodeled to be compatible for the restore (fixes hdos/issues#1404)
  - The general store has been overhauled
  - Windows of all the houses have been restored
  - Pathing has been improved to accommodate for oldschool layout
  - The oldschool bushes that are seen for non-ironman accounts (instead of the portal) have been remastered
  - The rusted anvil has been remastered
  - In several places the types and colours of fences and fence gates has been improved (fixes hdos/issues#494)
  - Several parts of the church have been restored
  - The "strange hole" from the "A Porcine of Interest" quest has been remastered and no longer has dirt inside it (fixes hdos/issues#512)
  - The mining rocks in the Lumbridge Swamp have been upgraded permanently
  - Improved the accuracy of roof removal in several places
  - The bar has been restored, and the bar sign has been remastered (fixes hdos/issues#456)
  - Restored NPCs:
    - Woodcutting tutor (Woodsman tutor)
    - Smithing tutor (Smithing apprentice)
    - Bartender
    - Account security tutor (Henry, Professor of Stronghold of Player Safety)
    - Bank tutor
### Fixed
- The following improvements have been made to the Grand Exchange agility tunnel shortcut:
  - The upper walls are no longer slightly sunken and the tile heights have been improved
  - The surrounding pebbles of one of the holes have been re-added
  - Some upper walls will no longer disappear whilst roofs are hidden
  - An issue where the minimap would display two agility shortcut icons has been fixed
- Fixed an issue where tile heights would conflict and raise a building's corner in the air after growing back the hedges by Ardougne's mansion
- The player is no longer drunk whilst trying to perform the spinning wheel animation
  - *We are looking into solutions to fix the spinning wheel itself*
- Fix item outlines in misc. interfaces (fixes hdos/issues#1180)
- Improve terrain blending
- Fix a bug where NPCs would disappear when the client recovers from a disconnect

## [304] 2022-22-11
### Changed
- Change default world to 301
- The Kourend (white) graceful outfit has been cleaned by Sarahs trusty loom
### Fixed
- Fix known crashes

## [303] 2022-21-11
### Fixed
- Fix OpenGL NullPointerException crash
- Fix underworld crack in Tutorial Island

## [302] 2022-21-11
### Changed
- Restored Tutorial Island, and remastered The Node (fixes hdos/issues#219 hdos/issues#332 hdos/issues#580)
  - _The Ironman dialog (issue 1392) will be fixed soon_
- Restored the Undead Trees around Draynor Manor (fixes hdos/issues#1402)
- Ground Items: reformat the game message notification
### Fixed
- MES: Fix "Teleport to POH" priority over "Teleport" (fixes hdos/issues#1399)
- Additional Npcs downgrade fixes intended for v297 have been included

## [301] 2022-20-11
### Changed
- Restored Draynor Manor (fixes hdos/issues#213)
- Restored the Yanille Agility Dungeon (fixes hdos/issues#364)
- Restored North-East of the Kharidian Desert (fixes hdos/issues#375)
- Made the following improvements to Yanille:
  - Restored the Yanille area whilst you are in the upstairs section of the Watchtower
  - Upgraded the fountain by the Watchtower
  - Improved the staircase leading into the Yanille Agility Dungeon (fixes hdos/issues#658)
  - Two small corners in the entrance wall of Yanille have been fixed as part of an underlying issue
- Captain Barnaby has been restored (fixes hdos/issues#387)
- Catacombs of Kourend's atmosphere has been brightened slightly
### Fixed
- Fix agile inventory sprites
- Fixed the following in the Spirit of Elid and Kalphite (task-only) Slayer dungeons:
  - Random oldschool walls have been cleaned up (fixes hdos/issues#368)
  - Improved MapFilter so both dungeons are no longer visible for each other
    - Tears of Guthix is also no longer visible from either of these dungeons whilst MapFilter is enabled
  - A missing wall piece in the task-only dungeon has been added until its remaster
  - Added a cave atmosphere to the task-only dungeon
- Fixed the lava in Brimhaven Dungeon (fixes hdos/issues#1393)
- Fully grown and diseased Oak trees have had their bushes trimmed (fixes hdos/issues#301)
- Bill Teach has been restored, and is no longer missing his torso (fixes hdos/issues#366)
- Ross' arms are no longer burnt (fixes hdos/issues#397)
- Fixed an issue where Draynor Manor's atmosphere would get stale after enabling the Halloween event

## [300] 2022-16-11
### Changed
- *AGILE WHEN? AGILE NOW!*  
    (_192 models later, all agile sets have been remastered_)
### Fixed
- Fix sit-on objects (fixes hdos/issues#303)
- The following improvements have been made to Port Sarim:
  - Some furniture has been upgraded
  - Some (interactable) furniture has been downgraded, to prevent transformation upon interaction (fixes hdos/issues#1311)
- Menu Entry Swappers: Fix priorities (fixes hdos/issues#1239 hdos/issues#1265 hdos/issues#1104) 


## [299] 2022-16-11
### Fixed
- Fix downgraded assets and other regressions from today's game update

## [298] 2022-16-11
### Changed
- All the areas affected by Oldschool's Halloween event have returned to normal
- Juna has been restored
- Agility Plugin: add Meiyerditch and Revenant cave shortcuts
- Remastered some motherlode mine models to make it less jarring (fixes hdos/issues#385)
- Improved Zalcano's atmosphere (fixes hdos/issues#200)
  - Additionally, some lighting was added
### Fixed
- Players can now properly leave the Pest Control boat without ending up floating over the boat (fixes hdos/issues#1369)
- Fixed L-shape movements (fixes hdos/issues#1123)
- The Inferno cape inventory icon no longer becomes invisible when using Low texture detail
- Improve various chathead animations
- Fix known crashes
- A remaining underwater issue along the shore of Hazelmere's island has now also been fixed (fixes hdos/issues#1365)
- The mining rocks in Barbarian Village will no longer return to the default colour variant whenever they are mined (fixes hdos/issues#1237)
- Mayor Hobb has taken off his ice skates and no longer slides across the floor when walking around (fixes hdos/issues#1362)
- Dense Essence Fragments have had their inventory icon corrected (fixes hdos/issues#1334)
- The Falador Teleport tablet icon no longer appears larger than the rest (fixes hdos/issues#1273)
- The cannons during the Tempoross fight now shoot fish instead of light spheres (fixes hdos/issues#1268)
- Fixed several missmaps where the Barbarian Assault icons would replace other models (such as in the Hallowed Sepulchre) (fixes hdos/issues#421 hdos/issues#1230)
- Improve animation smoothing (fixes hdos/issues#1196 hdos/issues#1380) 
- Patched up the river west of the Gnome Ball Field (fixes hdos/issues#52)
- The Jormungand's Prison Dungeon (Island of Stone) has been cleaned up (fixes hdos/issues#183)
- Made the following improvements to the "Getting Ahead" quest (fixes hdos/issues#379):
  - Atmosphere of the cave has been improved
  - The interaction with the cave exit has been corrected
  - Flour should now appear correctly
  - Skeletons are no longer mismapped
- The Fisherman Realm has been restored, and:
  - Restored the Freaky Forester random event (they secretly hide there..)
  - Heavily improved background terrain and MapFilter
  - Fixed all the torches burning through the roof and improved lighting (fixes hdos/issues#361)
- Fixed an underwater issue at the Wizard's Tower

## [297] 2022-14-11
### Added
- Added background fps: ***when unfocused fps will be capped to the desired value***
- Camera Plugin: Add the ability to unlock the minimum pitch
### Changed
- Restored the Lumbridge Swamp Caves
- Restored Tears of Guthix
- Restored Edgeville Dungeon's earth warrior area (fixes hdos/issues#1374)
- Restored Pest Control (fixes hdos/issues#345 hdos/issues#696 hdos/issues#1371)
- Make the default outline thickness more sleeker
### Fixed
- Fix random cases where the client would hang for a few seconds before recovering
- Misc. npcs have been restored back to their original forms prior to this weeks game update
- Removed an unnecessary wall at the entrance in Brimhaven Dungeon (fixes hdos/issues#1364)
- Port Sarim chests, drawers and doors should finally work as expected (fixes hdos/issues#1311)
- The z-fighting in the Port Sarim jail has been resolved (fixes hdos/issues#1311)
- Paterdomus Temple walls have reappeared
- Slightly moved a wall in the Paterdomus Temple to where you should not be able to walk
- The Lumbridge Swamps-Lumbridge Cellar shortcut is once again accessible whilst MapFilter is enabled (fixes hdos/issues#1379)
- Tears of Guthix is once again accessible from the Lumbridge Caves whilst MapFilter is enabled
- An underwater gap along the shore of Hazelmere's island has been fixed (fixes hdos/issues#1365)
- The tool leprechaun restore intended for v296 should now work properly (fixes hdos/issues#1363)

## [296] 2022-9-11
### Changed
- Restored and remastered Brimhaven Dungeon and its new areas (fixes hdos/issues#893 hdos/issues#435 hdos/issues#428 hdos/issues#138)
- The eeriness of Halloween has subsided, and the crew has packed up their things. Until next year!
- The bushes at Lord Handelmorts home in Ardougne have been now properly watered by Horacio
- Restored baby green dragons
- Restore Tool Leprechaun
- Added a missing rock in the Port Sarim waters
### Fixed
- Improve update performance (the client should no longer get stuck at "Fetching Config")
- The sidebar button should no longer get lost randomly in the middle of the screen (fixes hdos/issues#1069)
- Improve Opponent Information plugin (fixes hdos/issues#1358)
- Fixed window symmetry of the Edgeville Monastery (fixes hdos/issues#1328)
- You can no longer walk through the wall of the Edgeville Monastery (fixes hdos/issues#1328)
- The web in the Temple of Ikov can once again be interacted with
- (Desert) goats will now perform their animations correctly
- A type of wooden gate in Nardah will no longer be rotated the wrong way around (also fixes future cases of this model)
- The door in Gerrant's fishing shop in Port Sarim will no longer duplicate (fixes hdos/issues#1311)
- Fix misspelled agility courses within the Agility plugin
### Removed
- Remove Quick Settings from the toolbar (since it's enabled by default now)

## [295] 2022-2-11
### Changed
- Restore Troll Stronghold (fixes hdos/issues#434 hdos/issues#888 hdos/issues#890)
### Added
- Add plugin: Object Markers
### Fixed
- Screenshot: fix a bug where events are captured before they are rendered
- Ground Items: fix lootbeams from despawning when changing regions
- Fix overheads from clipping through the minimap
- Fixed a Z-Fighting issue regarding the player's shadow on the Seer's Village rooftop agility course
- The furnace in Burgh de Rott should once again be interactable during the In Aid of the Myreque quest (We are aware that the fire inside the furnace may not animate. We will have to revisit this later due to a deeper engine problem)
- Removed an excessive light in the Temple of Ikov
- The Ice Queen Lair is once again fully accessible whilst MapFilter is enabled
- A certain type of steel door no longer vanishes whilst it's being opened 

## [294] 2022-31-10
### Changed
- Restored the following areas in the Kandarin region:
  - Seers village
  - Temple of Ikov
  - Fishing Guild and part of Baxtorian
  - Coal trucks and the dwarven outpost
  - Ranging Guild
  - McGrubor's Wood
  - SinclairMansion
  - Elemental Workshop
- Screenshot plugin: add "Open Folder" button to open screenshot directory
- Screenshot plugin: enable "Valuable Drops" by default
- Restore Fire cape (i) (fixes hdos/issues#1290)
### Fixed
- Screenshot plugin: fix the year-month formatting to not be a month behind
- Fix crashing when zooming at a low target FPS (fixes hdos/issues#1352)
- Added some missing rocks and fixed an underwater issue in the Baxtorian falls
- Fixed a mapfilter issue where the metal dragon task-only area in the Brimhaven Dungeon would be inaccessible
- You can once again exit the Nature's Grotto whilst doing the quest (fixes hdos/issues#1351)
- Pyrefiends now perform the correct defend animation (fixes hdos/issues#1324)
- Several doors in Port Sarim no longer revert to their old models after opening and closing them (fixes hdos/issues#1311)
- Entrana fences are no longer sunken into the ground (fixes hdos/issues#1309)

## [293] 2022-29-10
### Added
- Add Plugin: Screenshot
### Fixed
- Fix known crashes
- Fix many incorrect chatheads
- Transmog Plugin: locking the look no longer breaks the client after re-logging (fixes hdos/issues#1341)

## [292] 2022-26-10
### Changed
- #### **HD Pack 4.5**
  This special version is an addition to our fourth **HD PACK**. HD Packs aim to upgrade a group of OS models with custom assets, so they align with the HD art style.

  This additional HD pack version has a set of smaller improvements, and targets the **Oldschool Halloween event**. Although the event is limited, we may re-introduce some of the assets in a future event.

  The following changes are introduced:
  - Additional fixes were made after the initial fixes in v291
  - Remastered all objects
  - Added additional (slightly lighter) Halloween atmospheres to several zones
    - Also added lights to all of the new Jack-o'-Lanterns
  - The HDOS crew has provided the children in Varrock with improved H'ween outfits
  - Textured the Witch outfit

  *We may subsequently remaster more things or revisit armour in the future, but our tools are limited, so that'll be something for the remastering stage*
### Fixed
- Improve Pin Bar layout behavior
- Opponent Information: Fix player lookup, refine UI settings
- Fix Amulet of the Eye recoloring (fixes hdos/issues#1345)
- Fix the world list not listing specific worlds

## [291] 2022-26-10
### Changed
- Camera zooming is now smoothened out
### Added
- Add plugin: Opponent Information
### Fixed
- Quick Settings no longer closes on world hop
- Fixed a crevice in the Varrock river
- Fixed the OS Halloween 2022 event
- Improved MapFilter for the slayer-only kalphite dungeon and the Desert Treasure pyramid

## [290] 2022-21-10
### Changed
- Improve Halloween audio behavior so users can manually select songs
### Fixed
- Ground items should no longer appear under objects when multiple items are stacked
- Fix downgraded assets from the last game update
- A small gap in the floor in the Legend's guild dungeon has been fixed

## [289] 2022-20-10
### Changed
- Quick Settings is now enabled and pinned to the sidebar by default
### Fixed
- Random event restores intended for v287 have been fixed
- A sunken floor tile that was ripping the carpet apart in the Ferox Enclave has been fixed
- Fix the "The art of hocus-pocus" intended for v287
- Fix known crashes

## [288] 2022-19-10
### Fixed
- Deploy missing assets for v287 (Ferox Enclave)

## [287] 2022-19-10
### Changed
- #### **HD Pack 4**
  This version marks our fourth **HD PACK**. HD Packs aim to upgrade a group of OS models with custom assets, so they align with the HD art style.

  This HD Pack targets the **Death's Domain** and **Ferox Enclave** areas as part of the spooky halloween update, and introduces the following changes:

  - Remastered all objects
  - Improved pathing and ground textures
  - Upgraded NPCs (work-in-progress engine work)
  - Immersive lighting and atmospheres have been added
  - The falador crypt entrance roof will no longer be hidden as roof
  - Death's domain entrances are no longer filled with dirt (fixes hdos/issues#1240)
  - Added more torches to the Ferox Enclave dungeon
  - Added underworld (underwater) to pools and rivers
  - Several wrongly rotated chests have been fixed, and replaced with the remastered variant
  - Other notably affected models:
      ```
      - Staff of balance
      - Death's domain entrances (Lumbridge, Falador, Seer's Village, Ferox, Kourend and Prifdinnas)
      - Craw's bow
      - Thammaron's sceptre
      - Viggora's chainmace
      - Dragon pickaxe (or)
      - Dragon pickaxe (upgraded)
      ```
- #### **It's halloween!**
  - Remastered the paintings from the 2006 H'ween event, can you find them all?
  - Restored the 2006, 2007 and 2008 H'ween music tracks
  - Restored the Small- and Angel of Death gravestones (permanently)
  - Restored Gravedigger (and Beekeeper, Pillory and Pinball random events) as part of the halloween themed upgrades (permanently) (fixes hdos/issues#516 hdos/issues#845)
    - Also restored the mysterious old man (permanently)
  - Restored the 2008 ***Trick or Treat!*** Halloween event, by overhauling several zones:
    - Lumbridge
    - Draynor
    - Port Sarim
    - Rimmington
    - Grand Exchange
    - Edgeville
  - Restored Grim reaper hood (permanently)
  - Restored Zombie head (permanently)
  - Restored the Warlock- and Witch costume outfits with the Pyromancer outfit
    - The bruma torch has turned into a broomstick!
  - Some NPCs have decided to change into their halloween costumes
  - Purple sweets have turned into H'ween candy

  <br>

  *Note: Some of these changes will be reverted once Halloween comes to an end*

- Restored Port Sarim and Rimmington (fixes hdos/issues#1311 hdos/issues#1035)
  - Cleaned up the draynor agiliy shortcut tunnel (fixes hdos/issues#226)
  - Remastered the cabbage-port graphic (fixes hdos/issues#991)
- Remastered the Achievement cape, Achievement cape (t) and Quest Point Cape (t)
- The clan portal at the Grand Exchange has been improved
- The clue stash in the Edgeville Monastery is no longer invisible
### Fixed
- Fix item offsets for female players


## [286] 2022-18-10
### Fixed
- Transparent dialogs now correctly disable when transparent chat is disabled
- Fix npcs downgraded from last update (fixes hdos/issues#1338)
- Fix player skin colors (fixes hdos/issues#1024 hdos/issues#71)
- Summoning plugin now works for pets in POH (fixes hdos/issues#1337)

## [285] 2022-18-10
### Added
- Add summoning plugin
### Changed
- Restore fonts
- Restore transparent dialogs
- Restore the fixed mode game frame (finish the restore)
- Improve aliasing on the xp-orb sprites
- UI: Searching now automatically cancels when selecting a plugin from the search results
### Fixed
- Fix world map bugs (fixes hdos/issues#1261 hdos/issues#1192)
- Fix holes in the minimap and compass when in resizable mode (fixes hdos/issues#1137)
- Fixed an issue where minimap icons in Varrock were no longer shown after the restore
- Mowed the grass on the road from Varrock west-bank to the Grand Exchange
- Fixed a path issue by the Lumbridge windmill
- The strange doors in the Lighthouse dungeon will no longer decide to have fun with the transmog plugin
- Panning down the camera in the Lighthouse dungeon no longer makes the upper walls disappear
- Various torches should no longer burn as rigorously and burn through roofs
- Fixed a collision issue regarding the queue ropes in the Ardougne south-bank

## [284] 2022-13-10
### Fixed
- Fixed the landslide on the ice mountain
- Ardougne: Fixed the thieving door in Ardougne Castle
- Ardougne : Added some missing lights and fix bleeding lights (lights should no longer shine through walls)
- Icefiends now perform the correct animations

## [283] 2022-11-10
### Fixed
- Fix world map crashing

## [282] 2022-11-10
### Fixed
- Update protocol to 209
### Changed
- The settings window of a plugin can now be quickly closed using the `Tab` key (vs clicking the arrow)
- The plugin settings UI now remembers your last scroll position when navigating the UI

## [281] 2022-09-10
### Changed
- **Restored Ardougne**
  - A map with the exact restored locations can be found [here](https://cdn.discordapp.com/attachments/1000839218681102366/1026451614418092062/ardymap.png)
  - Other Ardougne improvements:
    - Areas where the Adougne Restore would otherwise create sharp bumps in tileheights have been smoothened out and modernized whilst maintaining the intended style
      - The old-school agility course heights have also been smoothened and improved (the plank on the course no longer makes you wobble up and down)
    - Fixed an issue where attempting to note items at the Leprechaun by the Ardougne Farm would result into interacting with the rock instead. (fixes hdos/issues#1247)
    - The Golden Gnome in the Legend's Guild has been remastered
    - A dozen objects in Ardougne have been altered to fit the restore
    - Several lighting effects that were overlooked in the original HD Ardougne have been added
    - Some areas now hide roofs more accurately
    - Remastered the Witchaven Dungeon (hellhound area) and jail cell underneath Ardougne Castle used in the Song of the Elves quest
- The agility sign on rooftop courses has been remastered
- Improve the Entity Hider plugin
### Fixed
- Add brightness fixes intended for v280
- Fixed the black area upstairs by the wyverns in the Asgarnia Ice Dungeon
- The skybox plugin no longer overrides Nex during her darkness phase
- Fix a bug in the texture projection (a good example is GE floors)
- Several improvements have been made to the Edgeville Restore:
  - Restored the furnace building
  - Improved the river and shorelines
  - Fixed a missing wall by Oziach
  - Created a path around the tree in the middle of the pathway
  - The Hell-rat behemoth rooms in Evil Dave's basement have been remastered (fixes hdos/issues#758)
  - The Wilderness Statistics board is once again visible (fixes hdos/issues#612)
  - The coffins in the Edgeville cemetery south of the bank have been restored and the interaction has been fixed (fixes hdos/issues#1312) 
  - Some missing lights were added
  - Removed a pillar that was clipping inside the Soul Wars portal
- Fixed an issue where the upper parts of the walls surrounding the GE would always be hidden

## [280] 2022-22-9
### Fixed
- Fixed chatheads (as per usual!)
- Fixed an issue where a dock was missing by the Ectofungus
- The True Blood Altar to the Myreque hideout cave entrance is once again accessible
- Fixed an issue where map filtering would block you from going further into the True Blood Altar tunnels
- Increased the brightness on some runecrafting altars, Giant's foundry, Catacombs and Motherlode mine (fixes hdos/issues#1107)
- Reverted an unintended Wildstalker hat model from overriding models
- Brightened the lights in the Warrior's Guild Basement
- Patched up the path leading to the Warrior's Guild Basement ladder
- The Skull slope on the agility course is once again visible, and is now highlighted by the agility plugin (fixes hdos/issues#1266)
### Changes
- Remaster the Lost Bag
- Restored Treasure trail items 
  <details>
  <summary>Click for a list of items</summary>

  - 3rd age range top (HD: Third-age range top)
  - 3rd age range legs (HD: Third-age range legs)
  - 3rd age range coif (HD: Third-age range coif)
  - 3rd age vambraces (HD: Third-age vambraces)
  - 3rd age robe top (HD: Third-age robe top)
  - 3rd age robe (HD: Third-age robe)
  - 3rd age mage hat (HD: Third-age mage hat)
  - 3rd age amulet (HD: Third-age amulet)
  - 3rd age platelegs (HD: Third-age platelegs)
  - 3rd age platebody (HD: Third-age platebody)
  - 3rd age full helmet (HD: Third-age full helmet)
  - 3rd age kiteshield (HD: Third-age kiteshield)
  - Ancient robe top
  - Ancient robe legs
  - Ancient cloak
  - Ancient crozier
  - Ancient stole
  - Ancient mitre
  - Armadyl robe top
  - Armadyl robe legs
  - Armadyl stole
  - Armadyl mitre
  - Armadyl cloak
  - Armadyl crozier
  - Bandos robe top
  - Bandos robe legs
  - Bandos stole
  - Bandos mitre
  - Bandos cloak
  - Bandos crozier
  - Bronze dragon mask
  - Iron dragon mask
  - Steel dragon mask
  - Mithril dragon mask
  - Nardah teleport
  - Tai bwo wannai teleport
  - Dragon platelegs (g) (HD: Dragon platelegs (or))
  - Dragon plateskirt (g) (HD: Dragon plateskirt (or))
  - Dragon full helm (g) (HD: Dragon full helm (or))
  - Amulet of fury (or)
  - Ancient platebody
  - Ancient platelegs
  - Ancient plateskirt
  - Ancient full helm
  - Ancient kiteshield
  - Armadyl platebody
  - Armadyl platelegs
  - Armadyl plateskirt
  - Armadyl full helm
  - Armadyl kiteshield
  - Bandos platebody
  - Bandos platelegs
  - Bandos plateskirt
  - Bandos full helm
  - Bandos kiteshield
  - Ancient bracers (HD: Ancient vambraces)
  - Ancient d'hide body (HD: Ancient body)
  - Ancient chaps
  - Ancient coif
  - Bandos bracers (HD: Bandos vambraces)
  - Bandos d'hide body (HD: Bandos body)
  - Bandos chaps
  - Bandos coif
  - Armadyl bracers (HD: Armadyl vambraces)
  - Armadyl d'hide body (HD: Armadyl body)
  - Armadyl chaps
  - Armadyl coif
  - Green dragon mask
  - Blue dragon mask
  - Red dragon mask
  - Black dragon mask
  - Fury ornament kit
  - Fury ornament kit
  - Dragon sq shield ornament kit (HD: Dragon sq shield ornament kit (or))
  - Dragon sq shield ornament kit (HD: Dragon sq shield ornament kit (or))
  - Dragon full helm ornament kit (HD: Dragon full helm ornament kit (or))
  - Dragon full helm ornament kit (HD: Dragon full helm ornament kit (or))
  - Druidic wreath (HD: Third-age druidic wreath)
  - Book of war
  - Book of law
  - Book of darkness (HD: Ancient book)
  - Bandos page 1
  - Bandos page 2
  - Bandos page 3
  - Bandos page 4
  - Armadyl page 1
  - Armadyl page 2
  - Armadyl page 3
  - Armadyl page 4
  - Ancient page 1
  - Ancient page 2
  - Ancient page 3
  - Ancient page 4
  - Armadyl rune armour set (lg) (HD: Armadyl armour set (lg))
  - Armadyl rune armour set (sk) (HD: Armadyl armour set (sk))
  - Bandos rune armour set (lg) (HD: Bandos armour set (lg))
  - Bandos rune armour set (sk) (HD: Bandos armour set (sk))
  - Ancient rune armour set (lg) (HD: Ancient armour set (lg))
  - Ancient rune armour set (sk) (HD: Ancient armour set (sk))
  - Armadyl rune armour set (lg) (HD: Armadyl armour set (lg))
  - Armadyl rune armour set (sk) (HD: Armadyl armour set (sk))
  - Bandos rune armour set (lg) (HD: Bandos armour set (lg))
  - Bandos rune armour set (sk) (HD: Bandos armour set (sk))
  - Ancient rune armour set (lg) (HD: Ancient armour set (lg))
  - Ancient rune armour set (sk) (HD: Ancient armour set (sk))
  - Book of war
  - Book of law
  - Book of darkness (HD: Ancient book)
  - Bandos page 1
  - Bandos page 2
  - Bandos page 3
  - Bandos page 4
  - Armadyl page 1
  - Armadyl page 2
  - Armadyl page 3
  - Armadyl page 4
  - Ancient page 1
  - Ancient page 2
  - Ancient page 3
  - Ancient page 4
  - Bandos platebody
  - Bandos platelegs
  - Bandos plateskirt
  - Bandos full helm
  - Bandos kiteshield
  - Armadyl platebody
  - Armadyl platelegs
  - Armadyl plateskirt
  - Armadyl full helm
  - Armadyl kiteshield
  - Ancient platebody
  - Ancient platelegs
  - Ancient plateskirt
  - Ancient full helm
  - Ancient kiteshield
  - Ancient robe top
  - Ancient robe legs
  - Ancient cloak
  - Ancient crozier
  - Ancient stole
  - Ancient mitre
  - Armadyl robe top
  - Armadyl robe legs
  - Armadyl stole
  - Armadyl mitre
  - Armadyl cloak
  - Armadyl crozier
  - Bandos robe top
  - Bandos robe legs
  - Bandos stole
  - Bandos mitre
  - Bandos cloak
  - Bandos crozier
  - Bronze dragon mask
  - Iron dragon mask
  - Steel dragon mask
  - Mithril dragon mask
  - Nardah teleport
  - Tai bwo wannai teleport
  - Dragon platelegs (g) (HD: Dragon platelegs (or))
  - Dragon plateskirt (g) (HD: Dragon plateskirt (or))
  - Dragon full helm (g) (HD: Dragon full helm (or))
  - Amulet of fury (or)
  - Ancient bracers (HD: Ancient vambraces)
  - Ancient d'hide body (HD: Ancient body)
  - Ancient chaps
  - Ancient coif
  - Bandos bracers (HD: Bandos vambraces)
  - Bandos d'hide body (HD: Bandos body)
  - Bandos chaps
  - Bandos coif
  - Armadyl bracers (HD: Armadyl vambraces)
  - Armadyl d'hide body (HD: Armadyl body)
  - Armadyl chaps
  - Armadyl coif
  - Green dragon mask
  - Blue dragon mask
  - Red dragon mask
  - Black dragon mask
  - Fury ornament kit
  - Fury ornament kit
  - Dragon sq shield ornament kit (HD: Dragon sq shield ornament kit (or))
  - Dragon sq shield ornament kit (HD: Dragon sq shield ornament kit (or))
  - Dragon full helm ornament kit (HD: Dragon full helm ornament kit (or))
  - Dragon full helm ornament kit (HD: Dragon full helm ornament kit (or))
  - 3rd age range top (HD: Third-age range top)
  - 3rd age range legs (HD: Third-age range legs)
  - 3rd age range coif (HD: Third-age range coif)
  - 3rd age vambraces (HD: Third-age vambraces)
  - 3rd age robe top (HD: Third-age robe top)
  - 3rd age robe (HD: Third-age robe)
  - 3rd age mage hat (HD: Third-age mage hat)
  - 3rd age amulet (HD: Third-age amulet)
  - 3rd age platelegs (HD: Third-age platelegs)
  - 3rd age platebody (HD: Third-age platebody)
  - 3rd age full helmet (HD: Third-age full helmet)
  - 3rd age kiteshield (HD: Third-age kiteshield)
  - Druidic wreath (HD: Third-age druidic wreath)
  - 3rd age robe top (HD: Third-age robe top)
  - 3rd age robe (HD: Third-age robe)
  - Dragon platebody ornament kit (HD: Dragon platebody ornament kit (or))
  - Dragon platebody ornament kit (HD: Dragon platebody ornament kit (or))
  - Dragon platebody ornament kit (HD: Dragon platebody ornament kit (or))
  - Dragon platebody ornament kit (HD: Dragon platebody ornament kit (or))
  - Dragon platebody (g) (HD: Dragon platebody (or))
  - Dragon platebody (g) (HD: Dragon platebody (or))
  - 3rd age druidic robe top (HD: Third-age druidic robe top)
  - 3rd age druidic robe top (HD: Third-age druidic robe top)
  - 3rd age druidic robe bottoms (HD: Third-age druidic robe)
  - 3rd age druidic robe bottoms (HD: Third-age druidic robe)
  - 3rd age druidic staff (HD: Third-age druidic staff)
  - 3rd age druidic staff (HD: Third-age druidic staff)
  - 3rd age druidic cloak (HD: Third-age druidic cloak)
  - 3rd age druidic cloak (HD: Third-age druidic cloak)
  - 3rd age mage hat (HD: Third-age mage hat)
  - 3rd age range top (HD: Third-age range top)
  - 3rd age range legs (HD: Third-age range legs)
  - 3rd age range coif (HD: Third-age range coif)
  </details>

## [279] 2022-16-9
### Changes
- #### HD Pack 3
  This version marks our third **HD PACK**. HD Packs aim to upgrade a group of OS models with custom assets, so they align with the HD art style.

  This HD Pack targets the minigame **Guardians of the Rift** and introduces the following changes:

  - Remastered all objects and NPCs
  - Several ground textures have been added to the zone
  - Added immersive lighting, atmosphere and skybox
  - Added the ability for lighting to be dynamically turned on or off, depending on the state of the object (such as an orb spawning)
  - The Raiments of the Eye have been upgraded with the Great Orb Project runecrafting robes (fixes hdos/issues#1167)
    - A custom set has been created to reflect the red version of the old-school outfit
  - The Amulet of the Eye has been completely remastered and should no longer clip as much
  - The click radius and shadows of the entrance barrier have been improved
  - The lava texture is now bloomed (notable area is the fire altar)
  - Restored Runecrafting Altars
  - Restored Wizard's Tower
  - Remastered the Blood Altar
  - Other notably affected models:
      ```
      - Boots of the Eye (use the Infinity Boots HD rig)
      - Abyssal Lantern
      - Abyssal Protector (pet)
      - Greatish Guardian (pet)
      - Rift Guardian (pet)
      ```
  - Note: *Fixes for the Lost bag should be included in the next update*
- Restored Teleblock (and no longer shoots a tornado) (fixes hdos/issues#542)
- Restored Kree'arra's tornado
- Restored the ground/inventory model of the Imbued Slayer Helmet
- Improved the textures on the Ava's Assembler
- Restored the newer versions of the Spirit Shields
- Several improvements have been made to Draynor (fixes hdos/issues#547)
  - Improve tile heights
  - Fix the dungeon entrances
  - Restore the hay roofing
- Removed Catacombs from map filtering for now
- Improve Motherlode Mine and Kourend Catacombs sky
- Quick settings is now docked by default
### Added
- Idle Logout Plugin
### Fixed
- Improve performance for the new animations in raids3
- Some unintended upgrades of bushes were reverted
- Some textures now emmit their light even when bloom is disabled


## [278] 2022-10-9
### Fixed
- Fixed GWD doors (fixes hdos/issues#1005)

## [277] 2022-9-9
### Fixed
- Improve the new animations in raids 3 (no loading times, less cpu, less memory, and improved tweening)
- Re-deploy audio update from 276, revert TOA audio for now
- Fixed rotated drawer in Ardougne
### Changes
- Restored beekeeper

## [276] 2022-8-9
### Changes
- Update protocol to 208
- Restored waterfiends
- Restored many small people
### Fixed
- Nature's Grotto exit fixed
- Gargoyles now display the defend animation correctly (fixes hdos/issues#786)
- Part of the wall east of the Grand Exchange should no longer disappear when roofs are hidden
- Combat dummies have sprouted from the patches of dirt in the POH (fixes hdos/issues#1276)
#### Audio (thanks to `@RS Orchestra#9880`)
- #### Fixes
  - Fixed an issue in one of the Bechstein 280 Piano samples (Patch 640 - Bank 5, Preset 0)
- #### Changed
  - Replaced the Staccato Opera Voice Oh samples with higher quality (Patch 257 - Bank 2, Preset 1)
  - Replaced the Sustained Opera Voice Oh samples with higher quality (Patch 258 - Bank 2, Preset 2)
- #### Added
  - Added Realistic Church Organ to Patch 659 (Bank 5, Preset 19)
  - Added Realistic Tremolo Strings to Patch 684 (Bank 5, Preset 44)
  - Added Realistic Orchestra Hits to Patch 695 (Bank 5, Preset 55)
  - Added Dubstep Wobble Synth to Patch 735 (Bank 5, Preset 95)
- #### Songs
  - Start (HD)
  - A Taste of Hope (Orchestral Remix)
  - Alchemical Attack! (Remix)
  - Rest In Peace (Death)
  - The Angel's Fury (Angel of Death, Remix)
  - Tombs of Amascut Jingles upgrade to HD sounds
  - Tombs of Amascut OST upgraded to HD soundset

## [275] 2022-5-9
### Fixed
- Fix Port Phasmatys restore

## [274] 2022-5-9
### Changes
- Restored Morytania (fixes hdos/issues#404 hdos/issues#490 hdos/issues#736 hdos/issues#867 hdos/issues#896 hdos/issues#1280)
  - the following zones have been affected:
    ```
    - Silverea
    - Paterdomus Temple (overworld)
    - Canifis
    - Slayer Tower (No remaster)
    - Mausoleum
    - Fenkenstrain's Castle
    - Experiments Dungeon
    - Ectofungus, Farm
    - Port Phasmatys
    - Haunted Woods
    - River opening above Slepe
    - Mort Myre Swamp, Nature's Grotto, The Hollows
    - Barrows, Barrows Crypts
    - Burgh de Rott
    - Haunted Mine
    - Tarns Lair
    - Myreque Hideout, Tomb of Ivandis, Fairy ring
    ```
  - Related changes:
    ```
    - Remastered the Morytania poll booth
    - Children in Burgh de Rott have been restored
    - Restored the Ectophial teleport
    - Remastered barrows heads inside the crypt (for the moment)
    ```
- Improved the texture projection on the regular poll booth
- Remastered clue stashes
- Restored 181 gnomes (fixes hdos/issues#961)
### Fixed
- Add support for the new skeletal system (Beta)
- Increase point light limit from 256 lights to 1024 lights to scale with the extended render distance
- Actor and projectile rotations and movements are now more smoother (removed micro-shaking)
- Fixed the flickering rates on some types point lights
- Fix notification popup rendering (fixes hdos/issues#1187)

## [273] 2022-26-8
### Fixed
- Fix animation stalling (fixes hdos/issues#1292)
- Fix raids 3 black underlays

## [272] 2022-25-8
### Fixed
- Angels in the sky mistaking the Torva full helm chathead for a skybox no longer make the client crash (fixes hdos/issues#1289)
- Fixed an issue where the cache mistakenly exceeded a limit. Booting the client should once again be as fast as before
- Raids 3 no longer suffers crashes from the strange new energy emitted from the menaphite pantheon (they instead will display their power via t-poses for now)
- Add support for 32 bit file identifiers within the cache
### Changes
- Improve the atmosphere for raids3 (until it gets remastered)

## [271] 2022-24-8
### Fixed
- Fix custom assets

## [270] 2022-24-8
### Changes
- Cold update the client
### Fixed
- Fix Paterdormus renovation

## [269] 2022-22-8
### Fixed
- Paterdormus' library has been renovated, and is no longer cursed when hide roofs is toggled off (fixes hdos/issues#1277)
- You can no longer sink through Canifis' rooftop agility course, and should once again be functional (fixes hdos/issues#1281)
### Changes
- The ring of the elements now uses HD teleport animations (fixes hdos/issues#1136)
  - Creating custom colours for each location is on the to-do list, but not a priority right now as it requires engine work
- Paterdormus' library atmosphere has been improved
- All variants of the Soul Wars capes have been restored
- Restored Nomad and Zimberfizz
- #### HD Pack 2
  This version marks our second **HD PACK**. HD Packs aim to upgrade a group of OS models with custom assets, so they align with the HD art style.

  This HD Pack targets **Ungael** and the boss **Vorkath** and introduces the following changes:

  - Added lighting and immersive atmospheres to Ungael
  - Remastered the objects on the island
  - Vorkath and its minions have been remastered
  - Several Vorkath projectiles have been remastered or restored
  - Added shorelines around the island
  - Climbing rocks on the island now performs an improved HD animation
  - Torfinn has been upgraded
  - Other notably affected items:
      ```
      - Ava's Assembler and Vorkath's Head
      - Dragon Crossbow
      - Mythical Cape
      - Dragonfire Ward and Skeletal Visage
      - Wrath Rune and Talisman
      - Superior Dragon Bones
      ```


## [268] - 2022-15-8
### Fixed
- Fixed black artifacts (grass and flags) in M1 GPUs
- Fixed long loading times when entering/exiting full screen on MacOS
- Fixed flicking issues on some UIs when UI Batching is enabled in MacOS (fixes hdos/issues#1275)

## [267] - 2022-10-8
### Added
- Add Attack Styles plugin
### Fixed
- Fixed the remastered tinted hit splats
- Refine extended npc
### Changes
- Restored Varrock (fixes hdos/issues#642 hdos/issues#796 hdos/issues#868)
- Restored Port Khazard
- Increased the contrast between normal and tinted hitsplats described above to improve differentiation between the two
- Remastered the max-hitsplat (adapted the 2011 style to match 2009 style)

## [266] - 2022-8-4
### Fixed
- Fixed downgrades from this weeks game update
- Fixed a gap in the beach by the east coast of yanille
- Fixed rotated RSC fence texture (fixes hdos/issues#1228)
- Fixed an issue where the client would stop allocating more VRAM above a certain threshold (high stress on the client no longer causes it to crash unexpectedly)
### Changes
- Restored the Imbued slayer helmet with the Full slayer helmet
- Restored mining rocks globally (some rocks will look off, this is intentional until those areas get restored by hand)
- Restored dragons
- Restored bears
- Truly restored the dragon pickaxe (animations and inventory icon)
- Improve texture projection for common trees
- The gem rocks in Shilo Village no longer turn brown when depleted
- The depleted version of the infernal axe is now mapped to the inferno adze
#### Audio (thanks to `@RS Orchestra#9880`)
- Reverted the Celesta instrument patch back to fix issues with several tracks
- Added Bechstein 280 Piano to Patch 640 (Bank 5, Preset 0)
- Song of the Elves (Reorchestrated Remix)

## [265] - 2022-7-28
### Changes
- Restored Yanille (fixes hdos/issues#276 hdos/issues#363 hdos/issues#592 hdos/issues#1142)
- Restored the Lighthouse and Lighthouse Dungeon (fixes hdos/issues#1042)
- Restored Fight Arena

## [264] - 2022-7-14
### Changes
- Restored Entrana (and its dungeon)

## [263] - 2022-7-14
### Changes
- Update protocol to 207
### Fixed
- Key remapping: disable remapping when inputs are present (fixes hdos/issues#1232)

## [262] - 2022-7-14
### Fixed
- Remove WIP plugins

## [261] - 2022-7-14
### Changes
- Restored the floor, and lighting in the Chaos Tunnel
- Restore Dragonbone necklace
### Fixed
- Fix the "Walk here" option when used from the right click menu
- The chat lock now automatically re-locks once a message is typed (fixes hdos/issues#1222)
- Box traps now look correct in the inventory (fixes hdos/issues#589)
- Improve region filtering and extended npcs (fixes hdos/issues#1224)
- Fix destination tile from appearing far away (fixes hdos/issues#1204)
#### Plugins
- Added: Key Remapping
- Camera: Move key remapping to the new Key Remapping plugin, and allow for customizable keys
- Tile Marker: Add an option to mark the menu destination
- Tile Marker: Destination tile now has a smooth transition
- FPS Debug: Rename to just FPS, and allow the FPS meter to be adjustable
- MES: Fixed swap from duel arena to pvp arena
### Launcher (v8)
- Add DLL Blocking (thanks to RL/Adam for the help)
- Windows launchers: fix window snapping, and black borders
- Remove proxy request on networking errors

## [260] - 2022-7-6
### Fixed
- Fix item downgrades due to the latest game update

## [259] - 2022-7-6
### Added
- Add toggle for UI batch rendering to offset negated performance on some specific GPUs (ex: ivybridge)

## [258] - 2022-7-5
### Fixed
- Fix login screen freezing (tm)
- The tunnels in Meiyerditch have been corrected (fixes hdos/issues#1155)  
- The Vyrewatch have regained their flexibility and no longer T-pose(fixes hdos/issues#1154)  
- The reclaim pet interface is now fully functional (fixes hdos/issues#1119)
#### Plugins
- Added an option to draw the true tile, even if the render position matches the server position (fixes hdos/issues#1168)

## [257] - 2022-7-5
### Fixed
- Fix known crashes
- Fix lobby screen freezing
- Fix lightbox solution rendering
- Fix ground item dots not rendering on the minimap (fixes hdos/issues#1176)
- Improve region filtering and extended npc wandering ranges

## [256] - 2022-7-2
### Changes
- Improve title screen npc movement
### Fixed
- Fixed UI rendering for older GPUs
- Fixed object examine

## [255] - 2022-7-1
### Changes
- Refine settings names, descriptors, and search tags
### Fixed
- Fix known crashes
- Fix broken context cursors
- Fix the welcome message within the lobby (spinning runes)
- Improve click boxes (fixes hdos/issues#923 hdos/issues#1103 hdos/issues#1106)
- Npc interaction now works when character shadows are disabled (fixes hdos/issues#1145)
- The door to COX now has a full size clickbox  (fixes hdos/issues#683)
- Region filtering: fix known areas that were being cutoff
- Quick settings no longer flashes when hopping in fixed mode, or closing the main settings window (if it was docked)
- Fix pixel artifacts that would accumulate in fixed mode
- Fix actor rotation (fixes hdos/issues#1089 hdos/issues#1112 hdos/issues#1135)
#### Plugins
- Ground markers: now work in instances (fixes hdos/issues#1146)
- Idle notifier: fix known bugs (fixes hdos/issues#923)
- Discord: the plugin now works as expected in f2p
- Discord: Zezima is not longer the default display name within the discord presence plugin
- Agility: All obstacles should now have their clickbox rendering properly (fixes hdos/issues#1049)
- Anti-drag: fix the shift key modifier
- Tile indicator: fixed an issue where you could not use both hover tile, and true tile at the same time (fixes hdos/issues#1156)
- Player indicator: no longer marks your own player

## [254] - 2022-6-29
### Added
- Ground markers
- Discord presence
- True tile markers are now available in the "Tile markers" plugin.
- Idle notifier
- Metronome plugin
### Fixed
- Fixed known crashed

## [253] - 2022-6-29
### Fixed
- Fix crashing when changing AA

## [252] - 2022-6-29
### Added
- Extended render distance
- Seamless region loading
- Region filtering (Beta)
- Extended npcs (Beta)
- Add a `Support` link to the Help menu on the top menu bar
### Changes
- Improve performance (2x peak performance in some cases)
- Restore The Warriors' guild 
- Restore The Crafting guild and Make over Mage buildings (fixes hdos/issues#1090)
- Restore Falador church (fixes hdos/issues#373)
- Restore Falador farm
- Restore various npcs, such as Mutated bloodvelds
### Fixed
- (Audio) `The Guardians Prepare`: Fixed the sustain control so notes don't drag on for a long time
- Camera shake speed (fixes hdos/issues#1026)
- Middle mouse expected behavior on components (fixes hdos/issues#1134)
- Fix the camera plugin from disabling
- Fixed the orange Ket-Zek (fixes hdos/issues#660)

## [251] - 2022-6-23
### Fixes
- Fix `OutOfMemoryError` (:smiwe:)

## [250] - 2022-6-22
### Changes
- Anti-Drag now only applies to items
### Fixes
- Fix known crashes
- Create a fallback for "sync error" faults
- Fix internal GL error notification
- Fix HD chatheads

## [249] - 2022-6-22
### Changed
- Removed the "quest helper" joke plugin
### Fixed
- Update broadcasting now clearly states it's from HDOS
- Added the ability to change your height while using freecam / occulus orb
- The default anti-drag settings have been corrected

## [248] - 2022-6-21
### Changed
- Added update broadcasting
### Fixed
- Antidrag plugin

## [247] - 2022-6-21
### Fixed
- Fixed Item switching when changing tabs (Fixes g-maul switches)

## [246] - 2022-6-21
### Fixed
- Fix interaction when using UI scaling

## [245] - 2022-6-21
### Changed
- Improve UI scaling (fixes hdos/issues#876)
- Add a Quick Settings toggle to the top Toolbar
### Fixed
- Fixed clan members not updating when they join/leave
- Fix known crashes
- Fix MES (fixes hdos/issues#1104)
- Quick Settings now opens properly when in fixed mode, with the sidebar closed
- WASD camera no longer triggers when searching within Quick Settings
- Fix the bank search from closing when Quick Settings search is active

## [244] - 2022-6-17
### Fixed
- Fix known crashes

## [243] - 2022-6-17
### Fixes
- The bank no longer closes when closing Quick Settings in the middle of searching
- Improve interaction detection for large entities (fixes hdos/issues#1041)

## [242] - 2022-6-15
### Fixed
- Update protocol to 206

#### Plugins
- Fixed a crash with the occulus orb plugin

## [241] - 2022-6-09
### Fixes
- Add numpad keys to bank pin plugin (fixes hdos/issues#1062)
- Fix main settings window not opening after world hop (fixes hdos/issues#1055)
- Fix "Use" MES swaps (fixes hdos/issues#1060)
- The bank no longer closes when searching after using Quick Settings search
- Fix inaccurate actor rotations (fixes hdos/issues#1059)
- Fix invisible balloons in the prison pete random event
### Changes
- Restore `Elite Void` and `Amulet of fury (or)`
- Fix atmosphere for the `Giants' Foundry`
- Quick Settings search can now be closed using the `Tab` key
#### Audio Improvements (thanks to `@RS Orchestra#9880`)
- Polished up several instruments: Patches 0-9, 44-49, and 60.
- Added realistic Timpani (Patch 687) and French Horns (Patch 700) to Bank 5.
- The following audio have been remastered:
  - Guardians of the Rift - Failure (Jingle)
  - Guardians of the Rift - Success (Jingle)
  - Sleeping Giants - Quest Complete (Jingle)
  - Delrith
  - Wally the Hero
  - Cain's Tutorial
  - Penguin Plots
  - Sorceress's Garden
  - Dogfight
  - Brain Battle
  - Awful Anthem
  - Crest of a Wave
  - Eye of the Storm
  - The Sinclairs
  - The Adventurer (Unlisted)
  - The Foundry
  - Drunken Dwarf
  - Mined Out
  - The Guardians Prepare
  - Temple of the Eye
  - Guardians of the Rift
  - Venomous
  - Dunes of Eternity
  - The Pharaoh
  - The Forgotten Tomb
  - Ruins of Isolation
  - Thrall of the Devourer
  - The Gates of Menaphos
  - The Spymaster

## [240] - 2022-5-14
### Fixed
- Fix invisible NPCs
- Fix rendering artifacts for Macbooks running integrated graphics.
- Partial fix for a very random and strange bug in newer AMD cards (ex: RX 590, RX 5600). 
  Restarting multiple times will eventually work.

## [239] - 2022-5-12
### Fixed
- Update protocol to 205

# [238] - 2022-5-10
### Fixed
- Fixed crashing

## [237] - 2022-5-10
### Changes
- Refactor plugin backend (fixes misc. quirks)
### Added
- Add Anisotropic Filtering (Display settings)
- Bank pin plugin
- Restore LMS Dragon Defender
### Fixed
- Fixed fullscreen on macOS
- Fixed misc. crashes

## [236] - 2022-4-28
### Fixed
- Actually fix the max cape `:^)`

## [235] - 2022-4-28
### Fixed
- Fixed known crashes
- Fix max cape restore

## [234] - 2022-4-28
**PLUGINS BATCH 1**  
Plugins voted for in batch 1 have been added
- All plugins and settings are now accessed through the _In Game Settings_
- The `Quick Settings` window allows you to edit plugins settings while in combat, it is access via _Double tapping shift_
- Plugin overlays (including the `Quick Settings`) can be resize, dragged and dropped to and from the sidebar.
### Changed
- Migrate and upgrade all existing plugins to be inside the game
- `Rough Walls` are now easier to click
- Remaster the title screen background (static image)
- The default FPS for the client is now set to 500 (from 100)
#### Restored
- Restored/Backported:
- Soul wars cape
- Dragon defender
- Ardougne cloak 1-4
- Falador shield 1-4
- Fremennik sea boots 1-4
- Karamja gloves 4
- Explorer's ring 1-4
- Varrock armour 1-4
- Max Cape (Completionist cape)
- Ancient teleport
- Lunar Teleport
- Superheat Item spell
- Low and High alch animation
### Added
- **The graphics settings within the login screen now exist within the game settings under the `Display` tab**
#### Plugins
  - Boosts Information
  - Clue Scroll Helper
  - Ground Items
  - Loot Tracker
  - Menu Entry Swapper
  - Puzzle Solver
  - Green Screen
  - Quick Settings
  - Tile Indicator
  - Entity Hider
  - Anti Drag
  - Player Indicators
  - Door Kicker
  - Agility
  - Quest Helper
  - FPS Debug
  - Transmog
  - Skybox
  - Camera
  - Slowmo
### Fixed
- Right-Click menu `Walk-here`
- The `Esc` key for the closing the Settings UI
- Fix the `Hide Roofs` setting
- Player notifications messages (logged in/out) now clear after 10 seconds
- Improve safe mode (disables settings if it detects the client failed to boot)
- Fix a long standing bug randomly causing users to no longer be able to type
- Fix Cerberus rotation bug
- Fix world map spin rate and minimap hint arrows
- Fix the bank and other UIs when the client is down-clocked (< 50 FPS target)
- Improve min size and UI scaling limits
- Fortify update detection (cold updates)
#### Graphical Fixes
  - Fix Fog depth
  - Fix particles sizes when using x8 and x16 AA
  - Fix particles sizes when using UI scaling
  - Fix a bug on some GPUs that caused the water to turn green
  - Fix the quest tab icon from overflowing
  - Fix player shadows from rendering over players
  - Fix cannon shadow flickering
  - Improve rendering performance for dynamic shadows
  - Fix player rotation shaking (ex: dancing)


## [233] - 2022-4-27
### Fixed
- Fix the water

## [232] - 2022-4-27
### Fixed
- Partial fix for the Beneath Cursed Sands game update.  
  Beneath Cursed Sands might cause crashes -- full fix will be out in a few hours

## [231] - 2022-4-22
### Fixed
- Fix interaction breaking from the recent cold fix
- Fix broken chatheads :^)

## [230] - 2022-4-20
### Fixed
- Fix alching
- Fix login screen background

## [229] - 2022-4-20
### Fixed
- Fix inventory (fixes hdos/issues#1043)

## [228] - 2022-4-10
### Fixed
- Fix crashing at GOTR (fixes hdos/issues#1036)

## [227] - 2022-3-30
### Added
- Remaster the `Abyssal whip (or)` from Leagues3 (Thanks to `@Maximax#1897`)
### Fixed
- Fix particle rendering when UI scaling is active

## [226] - 2022-3-23
### Changed
- Update protocol to 204

## [225] - 2022-3-8
### Fixed
- Fix ChatHeads that were downgraded in the latest update
### Changed
- Remastered the title screen (login) sprites (thanks to `@DemHunter#7191`)
  - Improved image quality, and cleaning up aliasing and artifacts from compression.
- Added Staccato Strings to Bank 5
- Added Custom "TzHaar" Drums to Bank 6
- The following music tracks have been restored/remixed (thanks to `@RS Orchestra#9880`)
    - Adventure
    - Assault and Battery
    - Attack 1
    - Attack 5
    - Attention
    - Bane (Bane of Summer)
    - Baroque
    - Cave of Beasts
    - Clan Wars
    - Distant Land
    - Easter Jig
    - Emperor
    - Expanse
    - Expecting
    - Fanfare
    - Gnome Village
    - H.A.M. Attack
    - Have an Ice Day
    - Impetuous
    - Inadequacy
    - Inferno (Remix)
    - Itsy Bitsy...
    - Jaws of the Basilisk (Jaws of the Dagannoth)
    - Lair of the Basilisk (Lair of Kang Admi)
    - Long Ago
    - Newbie Melody
    - Pirates of Penance
    - Rune Essence
    - Scape Santa
    - Scape Soft
    - Shining Spirit
    - Showdown
    - Sojourn
    - Soundscape
    - Splendour
    - Tears of Guthix
    - The Power of Tears
    - Theme
    - Tomorrow
    - Too Many Cooks...
    - Tremble
    - Undead Dungeon
    - Upcoming
    - Venture 2
    - Wander


## [224] - 2022-2-27
### Fixed
- Fix occasional JVM crash before the crash screen opens (oh my)
- HD songs should no longer be abruptly stopped before they finish (fixes hdos/issues#1006)
- Fix known crashes
### Changed
- The following music tracks have been restored/remastered (thanks to `@RS Orchestra#9880`)
    - Arboretum
    - Bait (Conspiracy: Part 2)
    - Bloodbath
    - Catacombs and Tombs
    - Conspiracy (Conspiracy: Part 1)
    - Darkmeyer
    - Don't Panic Zanik
    - Duel Arena
    - Dusk in Yu'biusk
    - Horizon
    - Leagues 3 Intro Cutscene
    - Rising Damp
    - Soul Wars
    - Temple of Tribes
    - The Enclave (Command Centre)
    - The Waiting Game
    - Upir Likhyi (Remix)
    - Vanescula (Vanescula Fight)
    - Zanik's Theme


## [223] - 2022-2-23
### Fixed
- Launcher: lower max heap size within the jar launcher for 32 bit operating systems 
  to help mitigate a silent GL_OUT_OF_MEMORY error, which would cause black screens.
- Fix assets that were downgraded from the previous updates (ex: Goblins, Bob)
- Fix overhead clipping issues when in fixed mode
- At long last: Overhead bars no longer randomly draw in the top left corner!

## [222] - 2022-2-13
### Fixed
- fix floor underlays textures that became hard to see (ex: tzhaar)
- fix shader compilation crashing in some specific cards
- refine pallet correction fix from the v220
- improve rendering for item piles that are on top of objects

## [221] - 2022-2-9
### Fixed
- fix crashing due to new content

## [220] - 2022-2-9
### Added
- **Nex has been restored!**
- **Added particle support!**
- **Added billboard support!**
- Restored directional sound
- Restored the "Blow Kiss" animation
- Restored Halos
### Fixed
- **Animations are now smoother!** (fix timing bug that was causing micro-stuttering in-between frames)
- Animations no longer stall in the last keyframe before looping
- Fix chat heads
- Fix up misc. assets in GWD
- The mouse cross now appears when using items and spells on objects
- Player and npc shadows now render on the correct floor when on bridges and overpasses
- Shadows for large npcs now properly animate
- Shadows no longer clip into the terrain and objects on the floor
- Improve the render order for ground items so its more aligned with the OS behavior
- Health bars now fade at the proper rate
- Fixed an apparent bug in the model color pallet which removed a range of colors.
  Most notable color being black, which has been turning into gray
- Fix the oil spill tainting some waters in Gielinor
### Changed
- Update protocol to 203
- Misc. textures have been tweaked slightly
- Santa's imps have gone back home
- Flying (ex: knock back) is now smoother
- Reduced the volume for the bird flapping animations
- Improve region loading performance

- #### Full Music Restore!

    Thanks to `@RS Orchestra#9880` the music restore is now fully completed!  
    We were missing some tracks, jingles, and patches before, but thanks to
    his _Orchestration_, it's now completed in all of its glory!  
    Many tracks and audio may sound higher quality and richer.  
    Audio is one of those details that really helps bring everything together and gives a more fuller experience.  
    Some tracks he personally touched up on:  
    - Arboretum
    - Armadyl Alliance
    - Armageddon
    - Autumn Voyage
    - Bandos Battalion
    - Barb Wire
    - Bloodbath
    - Castle Wars
    - Coil (Remixed)
    - Darkmeyer
    - Dream
    - Garden
    - Harmony
    - Iban
    - Ice and Fire (Remixed)
    - Medieval
    - Ready for Battle
    - Scape Main
    - Shine
    - Soul Wars
    - Still Night
    - Strength of Saradomin
    - The Ancient Prison (Zaros Stirs)
    - The Enclave (Command Centre)
    - The Waiting Game
    - Upir Likhyi (Remix)
    - Vanescula (Vanescula Fight)
    - Zamorak Zoo
    - Zaros Zeitgeist



## [219] - 2022-1-5
### Fixed
- fix known crashes
- fix drag delay UI for mac

## [218] - 2021-12-30
### Fixed
- fix gim chat mode
- Drag delay plugin (the higher the delay, the sooner it's considered not dragging)

## [217] - 2021-12-28
### Fixed
- fix mac full screen and resizing
- fix mac toolbar UI
- fix known crashes

## [216] - 2021-12-26
### Changed
- refine the crash screen
- set the launcher to validate resources on boot
### Fixed
- disable full screen on mac, use undecorated window frames to help fix resizing problems.
- the game engine will attempt to fully shutdown on crash

## [215] - 2021-12-26
### Added
- gl internal error reporting
### Fixed
- improve performance on macos
- fix actor shadows and overheads from disappearing when the right click menu is open

## [214] - 2021-12-26
### Fixed
- fix idle logout
- improve compatibility with older graphics cards

## [213] - 2021-12-25
### Changed
- updated crash screen
### Fixed
- fix recent crashing on macs

## [212] - 2021-12-25
### Added
- add `::uiscale` command (ex: `::uiscale 100` == 100% (normal))
### Fixed
- fix resizing issues on mac
- fix music fading between tracks
- reduce memory usage and improve startup performance

## [211] - 2021-12-24
### Changed
- upgrade LWJGL to 3.3.0
- reduce the minimal GL requirement to 3.1 to support older cards
### Fixed
- add support for macOS/arm64
- fix crashes and bugs

## [210] - 2021-12-24
### Fixed
- improve compatibility with older graphics cards
- fix crashes

## [209] - 2021-12-23
### Fixed
- fix 32 bit support 
- improve compatibility with older graphics cards

## [208] - 2021-12-23
### Fixed
- remove verbose debug

## [207] - 2021-12-23
### Changed
- extend click distance
- `::slowmo` updated to go even more slow, moe.
### Fixed
- fix 2fa login timeout
- fix keyboard rotation rates at lower fps targets
- fix animations at lower at lower fps targets
- fix rotation shaking at higher fps targets
- improve compatibility with older graphics cards
- crash fixes

## [206] - 2021-12-22
### Changed
**NEW CLIENT**
- rewrote the old fixed function rendering pipeline to use GL3.2 core
- unlocked the clients tick rate, and frame rate
- added multi-threading
- improve performance by orders of magnitude
- migrate from JOGL to LWJGL

## [205] - 2021-12-16
### Changed
- Fix camera animation
- Fix random lag spikes around populated areas
- Fix downgrades from latest update
- Touchup Falador a bit

## [204] - 2021-12-9
### Changed
- Update protocol to 202

## [203] - 2021-11-3
### Changed
- Update protocol to 201

## [202] - 2021-10-26
### Fixed
- Client reconnection no longer kicks you to the login screen

## [201] - 2021-10-25
### Fixed
- The in-game brightness setting is no longer backwards
- Steam plugins no longer appear
- Searching in the settings windows has been fixed/improved
- Fixed chatheads and other downgrades due to the last cache update
- Fix GIM chat icons

## [200] - 2021-10-6
### Fixed
- GIM clans now work
- HD Chatheads that were downgraded have been fixed

## [199] - 2021-10-6
### Changed
- Update protocol to 200
### Fixed
- HD Chatbox
- Misc. crashes

## [198] - 2021-8-25
### Fixed
- Chat messages now work as expected
- Fix tutorial island crashing

## [197] - 2021-8-25
### Changed
- Update protocol to 199

## [196] - 2021-7-28
### Changed
- Update protocol to 198
### Fixed
- Fixed the troll npc animations within the Pinball random event (fixes hdos/issues#954)
- Address downgraded assets from recent cache updates
- Fix brightness in SD mode

## [195] - 2021-7-1
### Changed
- Restored Shilo Village (fixes hdos/issues#930)
- Restored Law Altar (fixes hdos/issues#908)
- ```::dark``` now has a second parameter (1 to 100) to adjust the brightness ex.(::dark 75) (fixes hdos/issues#875)
- The eat animation has been restored (fixes hdos/issues#639)
- The Graceful top and bottom are now using the Agile models (rest soon to be done) (fixes hdos/issues#936)
- The infernal axe is now represented by the inferno adze (fixes hdos/issues#929)
### Fixed
- Fix the camera zoom when in HD mode (fixes hdos/issues#163 hdos/issues#537 hdos/issues#640 hdos/issues#795 hdos/issues#801 hdos/issues#818)
- Thordur's Blackholes are darker than ever (fixes hdos/issues#880 hdos/issues#155)
- Message's first letter is now capitalized (fixes hdos/issues#835)
- Goblins in Lumbridge basement now are longer on hover boards (fixes hdos/issues#806)
- The wheat field in Catherby has been fixed up (fixes hdos/issues#862)
- Watered seedlings/saplings should now have the correct item sprite (fixes hdos/issues#860)
- Fluffy's Kitten finally decided to stop hiding inside a book (fixes hdos/issues#622 hdos/issues#919)
- Overhead messages now last the standard time before vanishing (fixes hdos/issues#940)
- Fix misc. crashes
- Fixed all issues at tempeross (fixes hdos/issues#931 hdos/issues#927)
- Bandage tables are now back in soul wars (fixes hdos/issues#838 hdos/issues#665)
- Repaired the signs outside seers (fixes hdos/issues#808)
- Removed random light from man house in Edgeville (fixes hdos/issues#878)
- Fix audio and brightness settings (fixes hdos/issues#950)

## [194] - 2021-6-23
### Fixed
- Fix the chatbox (fixes hdos/issues#942)
- Fix the chatbox color settings

## [193] - 2021-6-23
### Fixed
- Fixed some checker flooring (fixes hdos/issues#928)
- Fixed gargoyle animations (untextured death is intended for now) (fixes hdos/issues#786)
- Fix the chatbox

## [192] - 2021-6-16
### Changed
- Update protocol to 197
- Revert the pickaxe models back the OS style
- Upgraded the orange `Ket-Zek` in the fight caves (fixes hdos/issues#660)
- Upgraded health bars to HD (fixes hdos/issues#320 hdos/issues#788)
- Improved texture upscaling slightly
- Improved bloom on the `Twisted Bow`
### Fixed
- Excluded the `Basilisk Knight` attack from tweening and should no longer twirl (fixes hdos/issues#184)
- Excluded the `Mogre` death animation from tweening (fixes hdos/issues#299)
- Various NPCs can no longer go stiff (fixes hdos/issues#587 hdos/issues#700)

## [191] - 2021-6-11
### Changed
- Update the LAF (fixes hdos/issues#419 hdos/issues#620)
- Restore the `Air Guitar` animation (fixes hdos/issues#918)
- The `Verac's flail` idle animation now tweens
- Upgrade the `Viggora' chainmace` to the `Verac's flail` (excluding attack) (fixes hdos/issues#748)
- Upgrade the `Agility skillcape` (fixes hdos/issues#395 hdos/issues#907)
### Fixed
- Fix a bug where the buggy sacks near buggie in the kalphite cave would display as a floating tile (fixes hdos/issues#376)
- The motherlode mine no longer makes the dragon pickaxe cower in fear (fixes hdos/issues#841 hdos/issues#828 hdos/issues#787 hdos/issues#489)
- Performing the spin emote will no longer haunt you with the crafting context cursor (fixes hdos/issues#785)
- Spells/Item now cancel when you click on a tile (fixes hdos/issues#871)
- Fix an oversight where unpowered orbs would have the same model colour as air orbs ([this was fixed in 2009](https://runescape.wiki/w/Update:Patch_Notes_(6_May_2009))) 

## [190] - 2021-6-5
### Changed
- Revert the `Scythe of vitur` attack animation
- Taking fish from a barrel in piscarilius will no longer atomically rearrange that barrel
### Fixed
- Fixed misc crashes
- The client can now enter HD mode when using Java 16
- Improve highDPI scaling

## [189] - 2021-6-2
### Added
- 2FA will now ask if you want to authorize for 30 days or one time
### Fixed
- Chatting within clans now works (fixes hdos/issues#897)
- The favorite world now applies correctly (fixes hdos/issues#826)

## [188] - 2021-6-2
### Changed
- The `F-Keys`, `Esc`, and `Space` keys can be used when the chat lock is enabled in the WASD Plugin
- Upgraded the new clan icons in the UI
    - Thanks to `@Adam#9751` for making them, and `@Zukitwo#3440` for testing them!
### Fixed
- Implement the new clan system (fixes hdos/issues#820 hdos/issues#834)
- Improve dpi-scaling for high resolution displays
- Camera zoom now persists (fixes hdos/issues#863)
- Resolve a bug that would corrupt the jagex_cl.dat files
- Players can now finally escape Petes Prison! (fixes hdos/issues#181)
    - Thanks to `@Im2Hi2Play#7412` for letting us use his account!
- Remove the gap at the bottom of the context menu
- Father Aereck and Donie have switched back to their correct bodies

## [187] - 2021-5-28
### Fixed
- Fixed interaction problems due to the recent update

## [186] - 2021-5-28
### Changed
__***!!!OPEN BETA!!!***__

## [185] - 2021-5-27
### Added
- UI Scaling
### Changed
- Upgrade `Poll Booth` models
- Scuffed alters have been restored
- The first favorited world now defaults selected on launch.
    - pvp worlds will are ignored
    - worlds over 512 won't work due to script limitations
### Fixed
- Plugin: Player Markers plugin's clan logic has been fixed
- Plugin: Player Markers settings will now save
- Plugin: Ground Markers will now account for items that are on top of objects
- Plugin: Tile Hover and Tile Click no longer randomly hide when in GL mode 
- The scroll texture is no longer upscaled in interfaces
- HP bars no longer red bar when they are low
- Roofing in the barrows chambers has been fixed
- Dead clicks no longer occur when the Tile Hover plugin is enable
- Possible fix for freezing in linux
- Fixed the path between Lumbridge and Varrock

## [184] - 2021-5-19
### Changed
- Update protocol to 196
- Improved "Player Marker" plugin, settings may now change independently

## [183] - 2021-5-17
### Removed
- Removed the `Allocating Memory` loading step (should make startup times faster)
- Removed the `Idle Logout` feature
- Removed the `Unsafe Mode` feature
### Fixed
- The ground no longer cracks when you use the Dragon Warhammer spec
- Fixed chatheads and other downgrades due to the last cache update
### Changed
- Organized the menu bar UI
- Hiding interfaces now applies to the login screen (Useful for recording the background)
- Replace the command prefix with `::` instead of `:` (ex: `::issue` instead of `:issue`)
### Added
- The following plugins have been added:

    | Plugin | Description |
    |------|-------|
    | Tile Hover | Draws the tile the mouse is hovering |
    | Tile Click | Draws the tile your player is moving to |
    | Ground Marker | Draws information about items that are on the ground |
    | Player Marker | Draws information about players |


- Plugins now save their settings

## [182] - 2021-4-26
### Fixed
- Misc. NPC rotations have been fixed (fixes hdos/issues#792)
- Fix downgrades caused by the latest cache update

## [181] - 2021-4-23
### Fixed
- Whip idle animation now works in LMS (fixes hdos/issues#608)
- The Ancient Doors in the Legend's Quest have been corrected (fixes hdos/issues#670) 
- World Map: fix label rendering (fixes hdos/issues#479) 
- World Map: fix lag when zoomed out (fixes hdos/issues#728)
- World Map: fix Left click options (fixes hdos/issues#209)
- Seren now renders when in HD Mode (fixes hdos/issues#378)
- The Security Guard has decided to give users the key to unlock the gate (fixes hdos/issues#357)
- Seren environment has been fixed (fixes hdos/issues#582)
- Water near TOB had been upgraded to HD water (fixes hdos/issues#701)
- Trap door has been restored in Old Man Ral's Hideout (fixes hdos/issues#535)
- Troll Stronghold staircase has been fixed (fixes hdos/issues#401)
- Windows mode now saves when changed in menu (fixes hdos/issues#663)
- Lil' Creator pet should now be fixed (fixes hdos/issues#615)

## [180] - 2021-4-16
### Added
- The `:mog` command is now available to users!  
This command allows you to change into any NPC in the game!  
For example: `:mog 3127` will turn you into Jad!  
A nice free and public database for looking up NPCs is [osrsbox](https://www.osrsbox.com/tools/npc-search/)  
**Disclaimer: This command is just for fun and is expected to be glitchy and unstable, please do not report any problems**
### Fixed 
- Fixed NPCs that were downgraded due to the latest cache update (fixes hdos/issues#790)

## [179] - 2021-4-14
### Changed
- Update protocol to 195
- The Ivandis Flail has been restored, and subsequently, the Blisterwood Flail has been upgraded
### Fixed 
- Fixed the XP tracker (fixes hdos/issues#7)

## [178] - 2021-4-3
### Removed
- Due to a minor coding error, Summoning has been rescheduled to 2022
### Fixed 
- The Wizards have cleaned up the Asgarnian Ice Dungeon after an accident underneath their tower (fixes hdos/issues#680)
- Improved Unsafe Mode for NPCs (fixes hdos/issues#783)
- Duradel has been so kind as to apply a magical salve to a variety of monsters, which has calmed their animations (fixes hdos/issues#678 hdos/issues#652 hdos/issues#771 hdos/issues#661 hdos/issues#255 hdos/issues#656)
- Fixed a crash due to corrupt jagex_cl.dat files (it even crashes the official client, go figure)
- Fixed AMD detection when using ATI drivers
### Changed
- The following weapon animations have been upgraded:

    | Affected | Upgraded to |
    |------|-------|
    | Dragon Sword (special) | Vesta's Longsword (special) |
    | Dragon Warhammer (special) | Statius' Warhammer (special) |
    | Abyssal Dagger | Dragon Dagger (except stab) |
    | Elder Maul | Chaotic Maul |
    | Abyssal Bludgeon | Chaotic Maul |
    | Scythe of Vitur | Generic Spear |
    
- The following weapon models have been upgraded: 

    | Affected | Upgraded to |
    |------|-------|
    | Zamorakian Hasta    |   Zamorakian Spear   |
    | Magic Shortbow (i)   |   Magic Shortbow   |
    | Amulet of glory (5/6) | Amulet of glory |
    

- The Dharok's Greataxe running animation has been restored
- The Leaf-bladed sword have been restored
- The context cursor for 'Climb' now only shows the ladder cursor on stairs and ladders,
  in other cases (e.g. climbing rocks) it will show the agility cursor
- Tweening for some old fire animations has been disabled
- Added missing mods to the acknowledgements


## [177] - 2021-4-1
### Added
- New skill: Summoning
- Drop context cursor
### Changed
- Improved the accuracy on context cursors even more (fixes hdos/issues#782)
- The defend and jab animations for spears and halberds have been improved

## [176] - 2021-3-30
### Added
- **Auto Updating**  
    ```
    The client should now be able to auto-magically deal with random cache updates from Jagex.  
    The client will adapt itself accordingly based on detected changes, and attempt to retain  
    content integrity and upgrades. This means there should be no downtime for non-protocol updates. 
    This feature is bound to cause some new bugs, so be on the lookout! 
    ``` 
- Added Lvl-7 Enchant spell icon and cursor
- Restored remaining HD cursors
- Restored teletab teleport
### Changed
- Improved the accuracy on context cursors
- Restored the crush animation for the Zamorakian Spear
- Corrected the Defend and Smash animations for 2-handed weaponry
### Fixed
- Lots of items impersonating the pink skirt have been whipped into submission (fixes hdos/issues#283 hdos/issues#231 hdos/issues#139)
- The snow in Goblin Village has melted
- The darkness from camelot castle has been vanquished
- Context cursors now work in fullscreen (fixes hdos/issues#775)
- The wooden doors in Morton have been taught how to open properly (fixes hdos/issues#682)
- The dark energy core no longer turns incorporeal when jumping to other players (fixes hdos/issues#691)
- The leaf-bladed battleaxe animations are now HD, and no longer make you invisible (fixes hdos/issues#452)
- The black squares in the pyramid plunder entrance have been resolved (fixes hdos/issues#305)
- When using the NPC Contact spell, the dark mage no longer hides in a chest (fixes hdos/issues#517)
- The mischievous fairy that replaced the letter R with green pants in the fairy ring interface has been forced to return it (fixes hdos/issues#288)
- The blood shard has been pulled out of the shadow realm, and has taken on a new visible form (fixes hdos/issues#713)
- The correct icon in the level up window for prayer has been found in the heavens (fixes hdos/issues#673)
- Animations within interfaces now tween (fixes hdos/issues#653)
- The monkey council has banned smoke bombs, you can no longer turn invisible while using a greegree (fixes hdos/issues#675 hdos/issues#676)


## [175] - 2021-3-24
### Changed
- Update cache
- Custom cursors now persist into the entire application
### Fixed
- Various broken HD Textures have been fixed
### Added
- Restored custom context cursors

## [174] - 2021-3-17
### Changed
- Fix crashing from shooting stars (fixes hdos/issues#770)

## [173] - 2021-3-17
### Changed
- Updated cache
- The dragon pickaxe has been restored
### Fixed
- Improve hitsplat rendering (fixes hdos/issues#749)
- Exclude Texture Upscaling from textures where the results are undesired
- Exclude Tweening from animations where the results are undesired
- Fix: Dhc causes graphical stretch with armadyl platelegs (female)

## [172] - 2021-3-3
### Changed
- Update cache

## [171] - 2021-3-1
### Added
- Restore large HP bars
### Fixed
- Glitching animations introduced in v170 (fixes hdos/issues#745)
- The menu selection is now accurate (fixes hdos/issues#746)
- Fishing pools have been put back into the water (fixes hdos/issues#742)
- Goblins have rejoined the HD tribe

## [170] - 2021-2-28
### Changed
- The following UI elements have been restored
  ```
   - Game Frame
   - Choose Option (right click menu)
   - Hit splats 
   - Health bars 
   - Chat box 
   - Normal Spells 
   - Lunar Spells
   - Ancient Spells
   - Skill Icons 
   - Default Cursor (golden)

- OS Humanoid npcs now have HD animations

## [169] - 2021-2-24
### Changed
- Update protocol to 194
### Fixed
- misc. spot animations/projectiles that were wrong are now correct (fixed hdos/issues#720)
- Fixed cursed banana related issues (fixed hdos/issues#730 hdos/issues#732)
- Holding down a key bind for UI toggles no longer deadlocks the client (fixed hdos/issues#712)
- Made the lighting in the Stronghold Slayer Caves more consistent (fixed hdos/issues#724)

## [168] - 2021-2-17
### Changed
- Fix birthday event

## [167] - 2021-2-17
### Changed
- Update cache

## [166] - 2021-2-9
### Added
- Add commands 
    - :recommended - sets the graphics to a happy medium recommended settings.
    - :streaming   - sets the canvas to 720p HD screen res, and ramps up the settings.
    - :lowDetail   - sets the graphics to the lowest possible settings.
### Changed
- #### HD Pack 1
    
    This version marks our first _HD PACK_  
    HD Packs aim to *upgrade* a group of OS models with custom assets, so they align with the HD art style.   
    This HD Pack targets **Zulrah**  

    - Major effected items: 
        ```
        - Zulrah scales 
        - Magic fang
        - Trident of the seas & Trident of the swamp
        - Staff of the dead & Toxic staff of the dead
        - Tanzanite fang
        - Toxic blowpipe
        - Serpentine visage
        - Serpentine helmet
        - Magma helmet
        - Tanzanite helmet
        - Zul-andra teleport scroll
        ```
    
    - Major effected npcs:
        ```
        - Zulrah (all forms)
        - Pet Snakeling
        - Snakeling
        - Priestess Zul-Gwenwynig
        ```
    - Lighting, and environment has been added to the areas to create a more immersive feeling
- Many projectiles that were not restored, should now be HD
### Fixed
- The teleport scrolls in Zulrah Shine has returned (fixed hdos/issues#703)
- Fixed the roof in Sisterhood sanctuary(fixed hdos/issues#708)

## [165] - 2021-2-3
### Changed
- `Scape Theme` is now the default login music
- Update the cache
### Fixed
- Fix capacity check when adding to the friends or the ignore list
- Fix a crash if trying to turn Unsafe Mode on while the client is loading
- The whip has been disciplined to no longer stretch your hand off when it is idle

## [164] - 2021-1-30
### Fixed
- Fix crashing after updating from 163 (whoopsie)

## [163] - 2021-1-30
### Changed
- Increase the memory limit of the client to 512m (from 384m)
- Update the login screen sprites
- Verbose Debug will now render your current zoom
### Fixed
- Fixed the crystal ball glitching out in Varrock (fixes hdos/issues#662)
- Fixed incorrect stairs in East Ardy mansion (fixes hdos/issues#581)
- Upgrade the twisted bow (fixes hdos/issues#664)

## [162] - 2021-1-27
### Fixed
- Fixed remaining map load crashes (oopsie)

## [161] - 2021-1-27
### Fixed
- Fix peekaboo chairs in Edgeville
- Fix window mode switching
- Fix crashing near Wizard Tower

## [160] - 2021-1-27
### Changed
- Update cache
- Restore: Abyss (fixes hdos/issues#498)
- Added a check to prevent users from trying to change windows mode before the client initializes (fixes hdos/issues#238)
### Fixed
- Artifacting in interfaces caused by x16 anti-aliasing has been resolved (fixes hdos/issues#483)
- Braziers in Enakhra's Temple are now animating properly (fixes hdos/issues#402 hdos/issues#81)
- Fixed the stove in Goblin Tunnel (Observatory Quest) (fixes hdos/issues#291)

## [159] - 2021-1-22
### Changed
- Improve idle and movement animations
- Upgrade/Fixed the `Frozen abyssal whip` and `Volcanic abyssal whip`
- Restore: `Slayer Helmet`
- Rename `Hide HUD` to `Hide Interfaces`, remove `Hide` prefix.
### Fixed
- `Hide Players` now hides player overheads also (fixes hdos/issues#617)
- Fix poll booth in Edgeville (fixes hdos/issues#649)
- Fix `Abyssal Tentacle` for female players (fixes hdos/issues#647)
- Fixed the urns inside pyramid plunder (fixes hdos/issues#641)
- Fixed Shadow Giants (Ice Giants are now back to ice) (fixes hdos/issues#533)
- Players (mostly female) have visited the chiropractor again, and had their heads re-attached to their body!

## [158] - 2021-1-20
### Added
- Added "Scape Theme" to login music choices.
- The new area in Taverly (WIP)
### Changed
- Updated cache
- Upgrade/Fixed the `Abyssal Tenticle`
### Fixed
- Fixed whip attack sounds
- Varrock: fixed the floors in banks
- Camels no longer die every hit (fixes hdos/issues#624 hdos/issues#322)
- Fixed various issues with npcs and their animations (fixes hdos/issues#73 hdos/issues#142)

## [157] - 2021-1-14
### Fixed
- Fix bad deploy (POH)

## [156] - 2021-1-14
### Fixed
- Fixed 95% of Z-Fighting cases(flickering) (fixes hdos/issues#326 hdos/issues#104 hdos/issues#56 hdos/issues#40 hdos/issues#148)
- Fixed feet going through floors (fixes hdos/issues#502 )

## [155] - 2021-1-13
### Changed
- Update cache

## [154] - 2021-1-12
### Fixed
- Fixed AMD artifacts!!

## [153] - 2021-1-12
### Changed
- Upgrade idle animations (smoother)
### Fixed
- Fix text spacing (I hope)
- Slayer tower basement environment has been brightened

## [152] - 2021-1-11
### Changed
- Engine cleanup
- Updated the whip
    - Thanks to `jimqc` for finding the compatible ones
- Restore: Barbarian Assault/Outpost
- Restore: Baxtorian Falls
- Woodcutting Guild: improve path overlay
- Burgh de Rot : more accurate lighting
- Seer's Village : updated the bank floor
- Jatizo : updated floors, removed bad lights
- Al Kharid : improved flooring in the temple (full restoration on hold until open beta)
### Fixed
- Fix floating in GE
- Fix invisible model rendering (fixes hdos/issues#311 hdos/issues#509 hdos/issues#76 hdos/issues#118)
- Fixed space rendering is player names (fixes hdos/issues#309 hdos/issues#10 hdos/issues#9)
- Fixed home teleport animation (fixes hdos/issues#417)
- Fixed members world detection (fixes hdos/issues#577 hdos/issues#571 hdos/issues#60)

## [151] - 2021-1-6
### Changed
- Update cache

## [150] - 2021-1-5
### Added
- Add `Anti-Aliasing` option to Graphics
### Changed
- GL only menu options will now be disabled when not in HD mode
### Fixed
- Fix object area sound effects
- Fix a performance bug when the camera is aimed up
- Fix `Many Idle Animations` setting
- Fix castle wars bad wall on sara side.
- Fixed the under-lighting in Mor Ui Rek (inferno) (fixes hdos/issues#342)
- Fixed the pillars around the Astral rune alter  (fixes hdos/issues#341)
- Fixed the gaping holes in the wilderness agility area (fixes hdos/issues#228)
- Fixed magic carpet ride animation (fixes hdos/issues#153)
- Salarin the Twisted's cave now has walls (fixes hdos/issues#355)
- Hellcat now stays one once he gets overgrown (fixes hdos/issues#576)
- Fixed the flames in Burgh de Rott (fixes hdos/issues#338)
- Hans hands are back (fixes hdos/issues#151)
- Because we removed them from Thessalia's shop (fixes hdos/issues#150)
- Added floor overlays to the Tower of Life (fixes hdos/issues#220)
- All Lumbridge combat tutors have been upgraded (fixes hdos/issues#383)
- Lunar Isle : the pond
- Lunar Isle : repaired the roofs
- Taverly: Fixed a missing wall at fishing quest start (fixes hdos/issues#566)
- Taverly: Improved fencing (fixes hdos/issues#564)
- Taverly: Smoothed out paths (fixes hdos/issues#565)
- Taverly: Drawers now remain the same when opening and closing (fixes hdos/issues#544)
- Catherby : Improved drawers peeking through the walls (fixes hdos/issues#556)
- Catherby : Moved improperly placed stone (fixes hdos/issues#567 hdos/issues#50 )
- White Wolf Mountain : Restored south side (fixes hdos/issues#554)
- Canifis Tunnel : Gates now are HD when open (fixes hdos/issues#543)
- Lumbridge : Touched up the flour mill (fixes hdos/issues#511)
- Lumbridge : Cleaned up Hay Storage Wall (fixes hdos/issues#513)
- Lumbridge : Repaired Furnace building (fixes hdos/issues#508)
- Lumbridge : Removed random ice berg (fixes hdos/issues#493)
- Lumbridge : Restore RFD instance (fixes hdos/issues#442)
- EdgeVille : Fixed crack in floor near G.E. (fixes hdos/issues#495)
- EdgeVille : Fixed backwards door (fixes hdos/issues#461)
- Silvarea : Removed extra objects (fixes hdos/issues#541)
- Varrock : Fixed tunnels from G.E to EdgeVille (fixes hdos/issues#450 hdos/issues#226)
- Varrock : G.E. now has the proper roof texture

## [149] - 2021-1-1
### Fixed
- WASD Camera chat lock no longer applies when logging in

## [148] - 2021-1-1
### Added
- WASD Camera
### Changed
- Restore: Draynor Village (wip)
- Restore: Draynor Sewers
- Disable interaction while Free Cam is active
- Idle Logout no longer last forever, and is now limited to 15 minutes (from 5 minutes)
### Fixed
- Taverly: Fixed the skybox in the Witch's house (fixes hdos/issues#549)
- Taverly: Sanfew's table has been upgraded (fixes hdos/issues#553)
- Taverly: Fixed the carpet under the poll booth (fixes hdos/issues#552)
- Taverly: Flipped a bench to be facing the correct way

## [147] - 2020-12-31
### Fixed
- Fixed PVP priority rendering (fixes hdos/issues#337)

## [146] - 2020-12-31
### Changed
- Restore: Canifis Tunnel
- Restore: Silvarea
- Restore: H.A.M. Lair
- Restore: Taverly
- Restore: White Wolf Mountain
- Restore: Catherby
- Improve `Verbose Debug`
- Barbarian Village: fix lighting in village, add lighting to fishing spot fire.
- Lumbridge: improve the passage west of the castle
- Lumbridge: improve lighting in the church
- Improve default fog in undergroud areas to be easier to see
### Fixed
- Anti-Aliasing and the `:aa` command finally saves correctly
- Fix lag spike in some areas when users switched from SD to HD mode
- Fix H.A.M doors (fixes hdos/issues#475 hdos/issues#476)
- Freminnik Slayer Dungeon: put rocks back, fix Kurasks expansion (fixes hdos/issues#485)
- Fix broken/incorrect music tracks (fixes hdos/issues#536)
- Exclude the remaining scroll baackgrounds from texture up scaling
- Fix custom fog in dynamic regions
- Fix the gauntlet fog so its no longer bright

## [145] - 2020-12-28
### Added
- `Born Login` setting (plays "Born to do this" when in the login screen)
### Changed
**Restore Audio**

| type | total | percent |
|------|--------|---------|
| TRACKS | 523 | 100% |
| JINGLES | 273 | 100% |
| SOUNDFX | 3,664 | 95.74% |

- Improve the `:dark` command so that you can still see things
- Remove the `Cancel` option in the exit confirmation dialog
### Fixed
- Music jingles (ex: level up sounds) now work (they were never implemented!, whoopsie)
- Fix Texture3D support detection for Mac
- Improve Texture Upscale in interfaces (fixes hdos/issues#531) 
- Fix the Dharok attack animations
- Lumbridge: delete an extra piece of bridge (fixes hdos/issues#506)
- Lumbridge: fix Al Kharid gate (fixes hdos/issues#525 hdos/issues#501)

## [144] - 2020-12-24
### Fixed
 - Enable Texture3D support (it has disabled since v81, whoopsie!)  
   This greatly improves the water and lava!   

## [143] - 2020-12-24
### Fixed
- Fix specular highlighting (the 'shine' effect) in textures!
- Lumbridge: fix a `Suit of armour` in the entrance
- Lumbridge: fix the east bank booth to match the rest

## [142] - 2020-12-23
### Changed
- Restored graphics assets from [Animation Pack 1](https://runescape.fandom.com/wiki/Update:Blog_-_Animation_Update:_Pack_1)
- Improve Dragon scimitar special attack
### Fixed
- Fixed flickering problems in login screen animation
- Fixed ZGS special attack

## [141] - 2020-12-23
### Changed
- **Restored [Animation Pack 1](https://runescape.fandom.com/wiki/Update:Blog_-_Animation_Update:_Pack_1)**
    - 331 items (mostly polishing)
    - 584 animations (mostly audio improvements, and smoothing/tween)
- Restored Dragon platebody
- Restored Dagon'hai
- Restored Santa outfit
- Restored Zamorakian spear animations
- The Ghrazi rapier attack animation has been improved
- Change Debug KeyBind to `Alt D` (from `Shift D`)
### Fixed
- Lumbridge: Place the correct cannon on top of castle entrance
- Improve performance in crowded areas
- Removed carpet in the Motherlode Mine
- Fix Bank/Equipment lag (fixes hdos/issues#491)
- Varrock Sewers: Fix random torches (fixes hdos/issues#465)
- Ice Mountain restore has been put back (whoopsie) (fixes hdos/issues#464)

## [140] - 2020-12-21
### Added
- Add options: `Hide Players`, `Hide NPCs`, `Hide Graphics`, `Take Look`
### Changed
- Organized the UI to be less cluttered
- The `Take Look` option has been disabled by default,  
  and can be enabled using the new option.
- Texture Upscale no longer applies to interfaces
### Fixed
- Fix dynamic objects in restored areas
- Upscaled textures now animate at the correct speeds
- Lumbridge:
    - Fix ham trapdoor (fixes hdos/issues#467)
    - Deleted an extra wall in swamp (fixes hdos/issues#466)
    - Remove dirt over Deaths Domain (fixes hdos/issues#463)
    - Fix church door (fixes hdos/issues#462)
    - Fixed random overlay on the grass near lumby church
    - Fixed issue with a tile in basement
    - Restored the path leading to the north farm, towards draynor
    - Fixed the color of the wall surrounding wheat on the same path
    - Restore `Death to the Dorgeshuun` area under the watermill (fixes hdos/issues#459)
    - Fix chest and drawers when opened (fixes hdos/issues#458)
    - Fix ham trapdoor (fixes hdos/issues#467)
    - Fix misc. fencing to have less gaps
    - Add lights to the passage west of the castle
    - Fixed castle doors (fixes hdos/issues#457)
    - Enabled environment for basement (fixes hdos/issues#455)
    - Fixed light position at the general store
    - Upgraded the tavern (fixes hdos/issues#456)

## [139] - 2020-12-18
### Changed
- **Lumbridge has been restored!**
### Added
- Texture Upscale option (increases texture resolution)
### Fixed
- Edgeville Dungeon: improve `odd looking door` when it's opened
- Varrock Sewers: improve cave roofing near Bryophyta 
- Corp: fix atmosphere, re-enable rain
- Falador Party Room: re-enable flickering lights
- Castle Wars: torches in the waiting room are now fixed to the wall (fixes hdos/issues#411)
- Fixed Minimap in restored areas

## [138] - 2020-12-14
### Fixed
- Hotfix : fixed the red, and green marked squares floating around the map.

## [137] - 2020-12-14
### Changed
- Varrock Sewers
### Fixed
- Edgeville: fix floor near barbarian village
- You may now add the correct amount of users to your friends list in members worlds (fixes hdos/issues#380)
- Fixed issues in fally party room

## [136] - 2020-12-14
### Fixed
- Fix random sound effects in restored areas
- Edgeville Dungeon: improve `odd looking door`
- Edgeville: fix missplaced lights in platebody shop

## [135] - 2020-12-13
### Changed
**The following has been restored**
- Edgeville (wip)
- Edgeville Dungeon
- Falador Party Room (wip)
- Ice Mountain
- Black Knight's Fortress
- Barbarian Village


## [134] - 2020-12-11
### Fixed
- castle wars: fix the stairs?! (fixes hdos/issues#415)
- castle wars: fix misplaced overlays along the east pathway

## [133] - 2020-12-10
### Changed
- update the cache

## [132] - 2020-12-10
### Changed
- **The Monastery near Edgeville has been restored!** 

## [131] - 2020-12-9
### Changed
- update protocol to 193
### Fixed
- castle wars: fix balcony tile heights (fixes hdos/issues#410)
- castle wars: delete extra box above spawn rooms (fixes hdos/issues#409)
- castle wars: moved the skeleton causing teleporting issues in zammy lobby (fixes hdos/issues#412)

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