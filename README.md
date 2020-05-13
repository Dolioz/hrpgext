# HRPG Extension

Userscript to improve the UI of HeroesRPG.
Does not automate gameplay.

## Installation guide

Prerequisite: Tampermonkey browser plugin is installed

Firefox
- Use download link: https://github.com/Dolioz/hrpgext/raw/master/HRPGExtension.user.js

Chrome
- Create a new user script in tampermonkey
- Copy the script from https://github.com/Dolioz/hrpgext/blob/master/HRPGExtension.user.js and eplace the new user script content with it

## UI improvements

- Coloring gems in log
- Coloring gems in gem menu and their boost value to its name (e.g. Fractured Emerald (Gold 0.5%))
- Coloring uncommen chests and lockpicks correctly in log
- Coloring rare chests and lockpicks correctly in log and in globals
- Coloring epic and legendary chests correctly in globals

## Toggleable UI improvements

### Notifications

- Globals
- Personal messages
- Rift spawn and opening message. Also adds information to the browser tab [RS] for rift soon and [RIFT] for an open rift.
- Trade chat messages
- Clan messages
- Clan globals
- Quest completion
- Crafting finish & material shortage
- Item sold on market

### Chat

- Shorten rift kill globals to:
  - Standard: ZN Tanar (Level 150,000) landed the killing blow on the Hades [7] (Level 150,000) obtaining 1 Soul Shard(s) and 1,156 Riftscore! An additional x1.8 Riftscore multiplier was added to the Rift!
  - Short: Global: ZN Tanar (150,000) killed Hades [7] (150,000): 2 Shard(s), 1,156 Riftscore, x1.8 multiplier!
- Hide most non clan member globals
- Hide most clan member globals
- Exclude most globals from unread count
- Separate clan channel (chat commands can't be used in the clan channel)
- Hide clan messages from main channel
- View user profile with right click
- Turn URLs into clickable links
- Turn URLs into links in forum
- Increase chat size limit to 1000

### Log

- Hide common drops (chests, lockpicks, accessories) and fractured gems
- Hide uncommon drops (chests, lockpicks, accessories) and chipped gems
- Hide level ups

### Misc

- Set gathering as startup screen
- Ask confirmation on personal double haste
- Show clan profile link in clan menu
- Show cheaper skill tiers (compares cost efficiency between T1, T2 and T3)
- Hide game header (adds the links of the header as separate menu)
- Permanend scrollbar to prevent UI moving when switching between chat and statistics (requires refresh after change)
- Show power and armor in UI (updates when remove/equip gear and when chat command "/stats" is executed)
- Show attribute bonus in UI (updates when chat command "/stats" is executed)
- Show quest points in UI with link to the quest point stopre (updates only on quest completion, not when buying stuff from the store)
- Hide battle quests (useful for gathers)
- Hide gather quests (useful for battlers)
- Show quest re-reoll/reduce buttons (requires on click less then Carls quick link)
- Show DH timer in UI
- Show static [Enter Rift] button in UI
- Show configurable store link next to credits in UI
