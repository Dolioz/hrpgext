# HRPG Extension

Userscript to improve the UI of HeroesRPG.
Does not automate gameplay.

## Installation Guide

Prerequisite: Tampermonkey browser plugin is installed

Firefox

- Use download link: https://github.com/Dolioz/hrpgext/raw/master/HRPGExtension.user.js

Chrome

- Create a new user script in tampermonkey
- Copy the script from https://github.com/Dolioz/hrpgext/blob/master/HRPGExtension.user.js and replace the content of the new created user script with it

## Changelog

### 2.0.1

- [NEW] option to show only T4 battle skills
- [NEW] option to show compact battle stats
- [NEW] optopn to hide statistics menu
- [CHANGED] moved header links to HRPGExt menu

### 2.0.0

- [NEW] complete feature list in the documentation
- [NEW] coloring epic and legendary upgrade stones from rift reward chests correctly in globals
- [NEW] option to toggle sound notifications
- [NEW] log filter for rare drops (chests, lockpicks, accessories)
- [NEW] log filter for skill point drops
- [NEW] log filter for armor/weapon fragment drops
- [NEW] log filter for quest item drops
- [CHANGED] settings menu renamed to "HRPGExt"
- [CHANGED] show clan profile in clan menu is now a default feature
- [CHANGED] clickable links and right click for user profile are default features now
- [REMOVED] crafting material usage estimation
- [REMOVED] fixed pop up header

## Feature List - UI Improvements

- Add additional information to the browser tab:
  - [RS] = rift soon
  - [RIFT] = rift is open
- Clickable links
- View user profile with right click
- Show clan profile link in clan menu
- Coloring gems in log
- Coloring gems in gem menu and their boost value to its name (e.g. Fractured Emerald (Gold 0.5%))
- Coloring uncommen chests and lockpicks correctly in log
- Coloring rare chests and lockpicks correctly in log and in globals
- Coloring epic and legendary chests correctly in globals
- Coloring epic and legendary upgrade stones from rift reward chests correctly in globals

## Feature List - Toggleable UI Improvements

### Notifications

- Enable sound notifications
- Globals desktop notification
- Personal messages desktop notification
- Rift spawn and opening message desktop notification
- Trade chat messages desktop notification
- Clan messages desktop notification
- Clan globals desktop notification
- Quest completion desktop notification
- Crafting finish & material shortage desktop notification
- Item sold on market desktop notification

### Chat

- Shorten rift kill globals to:
  - Standard: ZN Tanar (Level 150,000) landed the killing blow on the Hades [7] (Level 150,000) obtaining 1 Soul Shard(s) and 1,156 Riftscore! An additional x1.8 Riftscore multiplier was added to the Rift!
  - Short: Global: ZN Tanar (150,000) killed Hades [7] (150,000): 2 Shard(s), 1,156 Riftscore, x1.8 multiplier!
- Hide most non clan member globals
- Hide most clan member globals
- Exclude most globals from unread count
- Separate clan channel (chat commands can't be used in the clan channel)
- Hide clan messages from main channel
- Increase chat size limit to 1000

### Log Filter

- Hide common drops (chests, lockpicks, accessories) and fractured gems
- Hide uncommon drops (chests, lockpicks, accessories) and chipped gems
- Hide rare drops (chests, lockpicks, accessories)
- Hide skill point drops
- Hide armor/weapon fragment drops
- Hide quest item drops
- Hide level ups

### Compact UI

- Hide game header (adds the links of the header as separate menu)
- Show compact battle stats:
    - Kills/Deaths (Win Rate)
    - Gold (Gold per hour)
- Hide statistics menu
- Show only T4 battle skills
- Show power and armor in UI (updates when remove/equip gear and when chat command "/stats" is executed)
- Show attribute bonus in UI (updates when chat command "/stats" is executed)
- Show quest points in UI with link to the quest point stopre (updates only on quest completion, not when buying stuff from the store)
- Hide battle quests (useful for gathers)
- Hide gather quests (useful for battlers)
- Show quest re-reoll/reduce buttons (requires on click less then Carls quick link)

### Misc

- Set gathering as startup screen
- Ask confirmation on personal double haste
- Show cheaper skill tiers (compares cost efficiency between T1, T2 and T3)
- Permanend scrollbar to prevent UI moving when switching between chat and statistics (requires refresh after change)
- Show DH timer in UI
- Show static [Enter Rift] button in UI
- Show configurable store link next to credits in UI

