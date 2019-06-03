# HRPG Extension

Userscript to improve the UI of HeroesRPG, does not automate gameplay.
Initially created by ApDea and now forked to continue developement.

## Changelog

### v1.8.6

[Features]
- Chat: Treasure Chest and Lockpick drops are now colored (Rare, Epic, Legendary)
- Log: Optional filter for low drops (Common, Fractured)
- Log: Treasure Chest and Lockpick drops are now colored (Uncommon, Rare, Epic, Legendary)
- Log: Gem drops are now colored

### v1.8.5

[Bugfixing]
- Fixed quick quest initilization when battle or gather quests are hidden

### v1.8.4

[Features]
- New options to hide battle/gather quests

[Bugfixing]
- Toggle header after header creation
- Fixed hiding clan member globals

[Polishing]
- CSS alignments for clan chat

### v1.8.3

[Features]
- Changed setting from "Hide most other player globals" to "Hide most non clan member globals"
- New option to hide most clan member globals

[Polishing]
- Increased chat size option from 300 to 1000
- Set default setting for enter rift button to deactivated
- Removed unstable feature "click player in clan chat to open clan profile"

### v1.8.2

[Features]
- Added option for a static [Enter Rift] button
- Shorten your own rift kill messages aswell
- Hide other globals: added hero kills and quest completion

[Bugfixing]
- Fixed credit store link to "Boosts"

### v1.8.1

[Features]
- Added a menu with game header links (only active when the game header is hidden)

### v1.8.0

[Features]
- Added auto update (only tested in firefox, may not work in chrome)
- Option to hide game header
- Option for a permanent scrollbar to keep the game UI static when switching channels (requires page refresh)

[Polishing]
- Added hint to the option "Fixed popup header" that it requires a page refresh
- Removed option center popup, because it was not used
- Show semantic version in footer

### v1.7.2

[Features]
- Shorten rift kill messages show shard and riftscore rewards (E.g.: Global: ZN Tanar (150,000) killed Hades [7] (150,000): 2 Shard(s), 1,156 Riftscore, x1.8 multiplier!)

[Polishing]
- Reworked setting descriptions and order
- Increased attribute bonus font size

### v1.7.1

[Features]
- Added rift soon warning [RS] in the document title, when a rift is about to open in 5 minutes

[Bugfixing]
- Fixed DH status minute + 1 bug
- Fixed display of the script version

[Polishing]
- Further reformatting

### v1.7.0

[Features] 
- Added notification for "A Rift will open in 5 minutes!"
- Document title is extended with [RIFT] when a rift is open or is about to open in 5 minutes

[Bugfixing]
- Fixed shorten rift kill globals

[Polishing]
- Reformatted code with formatter and removed dead code
- Removed show rift score, because its broken and obsolete due to game changes
- Removed gem fix, because Carl fixed it recently
- Removed new version notification, because automatic update is no longer supported
- Removed donation footer
