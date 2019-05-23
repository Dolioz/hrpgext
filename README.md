# HRPG Extension

Userscript to improve the UI of HeroesRPG, does not automate gameplay.
Initially created by ApDea and now forked to continue developement.

## Changelog

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
