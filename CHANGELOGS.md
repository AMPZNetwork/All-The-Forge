[![](https://www.bisecthosting.com/images/CF/All_the_Forge_10/BH_ATF10_promo.webp)](https://bisecthosting.com/AMPZ?r=cf_atf10)

# All The Forge 10 - ATF10 | Patch Notes
### Be sure to review these changes carefully before updating your world(s).

---

## Version: 1.3.1: (November 11th , 2023) 

### Updated:
- Applied Energistics 2 (15.0.14 → 15.0.15)
- Applied Energistics 2 Wireless Terminals (15.1.2 → 15.1.3)
- Citadel (2.4.8 → 2.4.9)
- Collective (6.82 → 7.3)
- Extreme Reactors (2.0.75 → 2.0.76)
- Embeddium (0.2.7 → 0.2.8)
- Macaw's Furniture (3.2.0 → 3.2.1)
- Minecraft Forge (47.2.4 → 47.2.5)
- Moonlight Lib (2.8.57 → 2.8.60)
- Tree Harvester (8.2 → 8.3)
- ZeroCore 2 (2.1.39 → 2.1.40)

### Changes and Fixes
- Fixed interfaces always exposing their own inventory to storage buses, making subnets impossible.
- Fixed a dupe bug with farmers delight.
- Rectified the improper sitting position of the Chair.
- Adjusted AE2 spatialPowerMultiplier and spatialPowerExponent.
- General improvements.

### Added:
- Create: Steam 'n' Rails
- Extreme sound muffler

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.3.0: (November 6th, 2023) 

### Updated:
- Applied Energistics 2 (15.0.13 → 15.0.14)
- Applied Energistics 2 Wireless Terminals (15.1.1 → 15.1.2)
- CC: Tweaked (1.108.3 → 1.108.4)cc
- ChoiceTheorem's Overhauled Village (3.3.5a → 3.3.6)
- Citadel (2.4.5 → 2.4.8)
- Collective (6.66 → 6.82)
- Comforts (6.3.3 → 6.3.4)
- Curios API (5.3.5 → 5.4.2)
- CTOV - Farmer Delight Compat datapack (2.0 → 2.1a)
- Create (0.5.1.e → 0.5.1.f)
- Deep Aether (1.0.10 → 1.0.11)
- Everything is Copper (2.2.1 → 2.3.2)
- Explorify (1.3.0 → 1.3.0-mc1.20)
- FerriteCore (6.0.0 → 6.0.1)
- GeckoLib (4.2.3 → 4.2.4)
- Hopo Better Ruined Portals (1.3.6 → 1.3.7)
- JourneyMap (5.9.15 → 5.9.16)
- Let Me Despawn (1.1.1 → 1.2.0)
- OpenBlocks Elevator (1.8.15 → 1.9)
- Minecraft Forge (47.2.1 → 47.2.4)
- Moonlight Lib (2.8.35 → 2.8.57)
- Polymorph (0.49.0 → 0.49.1)
- Refined Storage (1.12.3 → 1.12.4)
- Structure Gel (2.14.0 → 2.15.0)
- The Aether (1.3 → 1.4)
- Titanium (3.8.22 → 3.8.23)

### Changes and Fixes
- Fixed monitor peripheral becoming "detached" after breaking and replacing a monitor.
- Fixed signs being empty when placed.
- Fixed loot tables of the farmer delight's farm.
- Fixed slot filtering and slot size checking.
- Fixed an issue with Forge global callbacks not working correctly.
- Fixed network decoding errors.
- Fixed some broken tags.
- Fixed some more compat issues with shaders.
- Fixed a few known duplication bugs.
- Fixed issues with items not stacking after drop on mob kill.
- Fixed Analog Levers not rendering their redstone indicator.
- Fixed Turntable handler causing a crash during world shutdown.
- Fixed an issue with servers hanging when using camouflaged elevators.
- Fixed JEI transfer crash for larger processing recipes.
- Changed what kind of loot you are going to find in the "piglin ruin structure", chests fit more with a vanilla style, and some piglin brutes, drop better loot in that structure.

### Added:
- Construction Wand
- Embeddium
- Embeddium++
- Macaw's Furniture
- ObsidianUI
- RyoamicLights
- Create: Diesel Generators

### Removed:
- Rubidium
- Magnesium/Rubidium Extras
- Magnesium/Rubidium Dynamic Lights

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.2.2: (October 22nd, 2023)

### Updated:
- Applied Energistics 2 Wireless Terminals (15.1.0 → 15.1.1)
- Bookshelf (20.0.5 → 20.1.6)
- EnderIO (6.0.20 → 6.0.21)
- Extreme Reactors (2.0.74 → 2.0.75)
- Easy Villagers (1.0.13 → 1.0.14)
- Guard Villagers (1.6.2 → 1.6.3)
- Jade (11.6.1 → 11.6.3)
- Mekanism (10.4.0.14 → 10.4.2.16)
- Mekanism Generators (10.4.0.14 → 10.4.2.16)
- Mekanism Tools (10.4.0.14 → 10.4.2.16)
- Mining Gadgets (1.15.3 → 1.15.5)
- The Twilight Forest (4.3.1850 → 4.3.1860)
- Sophisticated backpacks (3.18.59.909 → 3.18.65.935)
- Sophisticated Core (0.5.89.425 → 0.5.100.457)
 
### Changes and Fixes
- Fixed in-game book recipe for Extreme Reactors.
- Fixed guards attacking mobs on the same team.
- Fixed item decorator rendering for amount of chemical stored in the mekasuit.
- Fixed certain damage sources not having a source entity.
- Fixed boss loot tables not being properly seeded, meaning the loot was always the same when killing them.
- Fixed hollow cherry logs not having a recipe.
- Fixed the uncrafting table not respecting recipes being marked as special.
- Fixed error when having villager without work sound.
- Fixed battery upgrade to not overflow max int of energy input/output when way too many stack upgrades are put in backpack.
- Miners Lights are now replaceable meaning you can place over them with normal block placement.
- Fixed Industrial Foregoing Iron, Gold and Diamond gears recipe not working inside AE2 ME. refer to this [image](https://imgur.com/mwWvlHk) to get an understanding of how to craft the new recipes.
- Added a the abiliy to craft chainmail armour (craft this the same way as you do the other armor but with chain).

### Added:
- Chisel's & Bits

### Removed:
- ModernFix

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.2.1: (October 13th, 2023)

### Updated:
- Citadel (2.4.4 → 2.4.5)
- Cupboard (2.0 → 2.1)
- Easy Villagers (1.0.12 → 1.0.13)
- ModernFix (5.7.5 → 5.8.1)
- Rubidium (0.7.1 → 0.7.2) (Technic and ATLauncher ONLY DELETE FOR CF Post)
- Security Craft (v1.9.7 → v1.9.8)
- TrimsEffect (1.0.1 → 1.0.3)
- Ketket's Graves Datapack (0.1 → 0.8)

### Changes and Fixes
- We've resolved a bug that was causing crashes for some users on ATLauncher and Technic. This issue was related to rendering specific texture chunks during world generation. For more details, check out issue [#629](https://github.com/Asek3/Rubidium/issues/629). Please note that this is an unofficial patch until an official release becomes available.
- Fixed an issue where Reinforced Doors placed adjacent to each other wouldn't open properly after the chunk they're in was reloaded.
- Fixed We've fixed the trash slot button, ensuring it no longer clashes with the vanilla recipe book when opened.
- Added the ability to craft iron, leather, gold and diamond horse armor. refer to this [image](https://i.imgur.com/NoZsFzi.png) for the recipe. 
- Corrected the problem that prevented placing, breaking, or interacting with blocks next to a Sentry.
- Sentries no longer attack teams that are allowed through an allowlist module.
- Addressed a duplication glitch involving easy villagers.
- Eliminated lag caused by the Forge vehicle resync patch and resolved a recipe conflict between The Aether Iron and Gold rings and Industrial Foregoing gears.
- The Lootr chest texture now uses the Minecraft default texture to be more compatible with resource packs.
- General performance improvements have been made to both loading and gameplay for all users.

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.2: (October 10th, 2023)

### Updated:
- Applied Energistics 2 (15.0.11 → 15.0.13)
- Applied Energistics 2 Wireless Terminals (15.0.12 → 15.1.0)
- AeroBlender (1.0 → 1.0.1)
- Bookshelf (20.0.4 → 20.0.5)
- ChoiceTheorem's Overhauled Village (3.3.5 → 3.3.5a)
- Curios API (5.3.4 → 5.3.5)
- CC: Tweaked (1.108.1 → 1.108.3)
- Dungeons and Taverns (v3 → 3.0.3)
- Extreme Reactors (2.0.73 → 2.0.74)
- Guard Villagers (1.6.1 → 1.6.2)
- Kotlin for Forge (4.4.0 → 4.5.0)
- Open Loader (19.0.2 → 19.0.3)
- Searchables (1.0.1 → 1.0.2)
- SuperMartijn642's Core Lib (1.1.12a → 1.1.15)
- Titanium (3.8.21 → 3.8.22)

### Changes and Fixes
- Bug Fix: Addressed an issue where adding servers to the multiplayer screen would result in their deletion upon the next pack launch.
- Bug Fix: We've adressed an issue with the witch villa's brewing loot chest table creating error logs.
- Bug Fix: Fixed an Illager Hideouts hallway sideroom not being able to generate.
- Bug Fix: Fixed certus quartz cluster waterlogging.
- Bug Fix: Fixed a bug where the terminal would not close when the network runs out of power.
- Bug Fix: Fixed error when a BaseBlockEntity returns null client data.
- Bug Fix: Fixed the loading bar not using the entire bottom screen on smaller displays.

### Added:
- Lootr 
- Blood Magic
- Easy Emmerald Tools & More

### Removed:
- Iron Jetpacks
- Cucumber
- Easy Emerald

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.1.0 (October 1st, 2023)

### Updated:
- AppleSkin (2.5.0 → 2.5.1)
- Applied Energistics 2 Wireless Terminals (15.0.11 → 15.0.12)
- Amplified Nether (v1.2.2 → v1.2.3)
- Blam (7.1.3 → 7.1.4)
- Blue Skies (1.3.28 → 1.3.29)
- Curios API (5.3.1 → 5.3.2)
- Collective (6.65 → 6.66)
- Curios API (5.3.2 → 5.3.4)
- Create (0.5.1d → 0.5.1e)
- Catalogue (1.7.1 → 1.8.0)
- Continents (v1.1.2 → v1.1.3)
- Dungeons and Taverns (2.1.4 → v3)
- EnderChests (1.0 → 1.1)
- EntityCulling (1.6.2-mc1.20 → 1.6.2-mc1.20.1)
- Extreme Reactors (2.0.72 → 2.0.73)
- FancyMenu (2.14.9-1 → 2.14.9-3)
- JourneyMap (5.9.12 → 5.9.15)
- Jade (11.5.1 → 11.6.1)
- Moonlight Lib (2.8.24 → 2.8.35)
- Minecraft (47.1.47 → 47.2.1)
- Old Combat Mod (1.20.jar → 1.20x)
- Oculus (1.6.4 → 1.6.9)
- Rubidium (0.7.0a → 0.7.1)
- YUNG's Better Dungeons (4.0.1 → 4.0.3)
- YUNG's Better End Island (2.0.1 → 2.0.4)
- YUNG's Better Jungle Temples (2.0.1 → 2.0.4)
- YUNG's Better Nether Fortresses (2.0.2 → 2.0.5)
- YUNG's Better Strongholds (4.0.1 → 4.0.3)
- YUNG'S API (4.0.1 → 4.0.2)
- Structure Gel API (2.13.1 → 2.14.0)
- ShetiPhianCore (1.0 → 1.1)
- Simple Discord RPC (3.2.2 → 3.2.4)
- Towns and Towers (1.11 → 1.11.1)

### Changes and Fixes
- Bug Fix: Resolved a crash that occurred when applying trapdoors to copycat panels.
- Bug Fix: Fixed an issue where Deployers were unable to interact with blocks using block-like items.
- Bug Fix: Addressed an issue related to slot loading on client-only entities.
- Bug Fix: Fixed problems related to the migration of old waypoints.
- Bug Fix: Resolved a crash associated with sound events in the presence of certain mods where the sound was null.
- Bug Fix: Fixed a potential crash caused by unexpectedly large health or absorption values.
- Bug Fix: Resolved a crash related to the Wireless Universal Terminal.
- UI Improvement: Adjusted the display of large hunger and saturation text in tooltips, preventing it from overlapping the icon.
- Feature Enhancement: Disabled the warning message for collective mod downloads.
- Performance Improvement: Improved performance by addressing multiple instances of modded structures causing lag.
- Performance Improvement: Made further improvements to memory usage.
- Gameplay Adjustment**: Rebalanced the loot found in the Stronghold library.
- Gameplay Enhancement: Illager camps now contain maps for Pillager Outposts.
- UI Enhancement: Made user interface tweaks to the Main Menu.
- Performance Enhancement: Enhanced the performance of Funnels, Chutes, and other Create components when used with large vaults.

### Added:
- The Aether
- Deep Aether
- EnderIO
- Silent Gear
- Mining Gadgets
- Mekanism 
- Mekanism Generators
- Mekanism Tools
- ModernFix
- FarriteCore

### Removed:
- Tips
- Productive Bees

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.0.2 (September 17, 2023)

### Changes and Fixes
- Fixed "No Chat Reporting server loging error".

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.0.1 (September 17, 2023)

### Updated:
- Applied Energistics 2 Wireless Terminals (15.0.6-beta → 15.0.11)
- Blue Skies (1.3.27 → 1.3.28)
- Blam (7.0.7 → 7.1.3)
- Cooking for Blockheads (16.0.0 → 16.0.1)
- Cristel Lib (1.1.1 → 1.1.3)
- Farming for Blockheads (14.0.1 → 14.0.2)
- McJtyLib (8.0.2 → 8.0.3) 
- Moonlight Lib (2.8.18 → 2.8.24)
- Macaw's Roofs (2.2.4 → 2.2.4b)
- RFTools Base (5.0.1 → 5.0.2)
- RFTools Builder (6.0.0 → 6.0.1)
- The Twilight Forest (4.3.1846 → 4.3.1850)
- Waystones (14.0.1 → 14.0.2)
- TrashSlot (15.0.0 → 15.1.0)

### Changes and Fixes
- Added a feature to the Main Menu: A slideshow that updates the background every 25 seconds, with promises of more additions in future updates.
- Added a backup server IP option on the multiplayer screen to ensure seamless gameplay continuity in the event of a main server IP gose down.
- Improved the server renting experience when using our partner's in-game service: Modpack detection is now automated during checkout.
- Resolved an issue with the titlescreen menu background being cut off when using smaller scaling settings.
- Reintroduced the vanilla recipe book feature.
- Fixed a crash with AE Infinity Booster.
- Fixed a worldgen issue that could cause a server to hang with many players online.
- Fixed a crash when repeatedly placing named kitchen blocks due to overflowing name.
- Fixed sandy and mossy waystones not retaining their name when broken with silk touch.
- Fixed a dupe bug related to some special crops.
- Fixed a few mods' integration with the Patchouli mod.
- Fixed a datapack error message during server startup.
- Fixed the trash slot being accessible in spectator mode.
- Fixed Roofing Hammer & Gutter not being found in the creative inventory or JEI interface.
- Fixed Death Tome Models using data from the previous render while on a Lectern, this would cause them to bounce up and down when a non lectern Death Tome is in view.

### Added:
- YUNG's Better End Island
- Rubidium
- Magnesium Extras
- Magnnesium/Rubidium Dynamic Lights
- Oculus

### Removed:
- Legendary Tooltips
- Equipment Compare
- Iceberg

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---

## Version: 1.0.0 (September 12, 2023)

- Initial Release.

For bug reports and issues, please visit our [Issue Tracker](https://github.com/AMPZNetwork/All-The-Forge-10).

---
