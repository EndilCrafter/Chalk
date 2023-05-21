### 1.4.1 - 1.18.2 - 2023-05-21 
- Fixed emissive rendering with Rubidium.

### 1.4.0 - 2023-02-10

- Added Chalk Box quick change selected chalks: 
  - Works by Shift+Clicking while not looking at a block.
  - Shifts chalks inside the box to the left.
- Improved compatibility with mods that modify damaging items.
  - Fixes Forbidden&Arcanus Eternal modifier not preventing damage to the chalk.
- Mod sounds now use unique SoundEvents: fixes subtitles and allows changing sounds in a resource pack.

### 1.3.2 - 2022-08-22

- Reduced chalk spawn chance in chests.
- Fixed stone spawning instead of chalk in loot tables.

### 1.3.1 - 2022-08-11

- Fixed sometimes not being able to draw a mark. (Minecraft has multiple types of air. Who would have thought.)

### 1.3.0 - 2022-07-31 - 1 in a MILLION

- Added Chalk Box. It lets you carry more chalks with you and draw glowing marks conveniently.
- Added Chalk Box to chest loot.


- What items are considered to be glowing is now defined by tag "chalk:glowing". Config for glowing items is removed. 
- Fixed glowing mark max allowed light level in a config to be 15 instead of 14.


- Removed glowing chalks.

### 1.2.1 - 2022-04-20
- Changed GlowItems config entry to allow no items to be defined. 
- Updated localization files.

### 1.2.0 - 2022-01-24

- Added glowing chalks. Draws glowing marks. Temporary until I find a better solution.
- Added config option for the glowing mark light level.

- Moved chalks to the Tools creative tab.
- Tweaked chalk mark colors.
- Fixed small mark redrawing bug.

### 1.1.1 - 2021-12-27

- Added ability to draw glowing marks by holding glowing item in offhand (suggestion by welpstudent)
- Added Simplified Chinese translation - provided by Lyaiya

---

### 1.1.0 - 2021-12-24

- Changed recipes of Chalks to Calcite and Dye, instead of Clay
- Slightly reduced chance of Chalks appearing in loot chests


- Added Catalan translation - provided by VerdaPegasus

### 1.0.1 - 2021-12-20

- Improved mark drawing:
  - If clicked on a usable block (such as barrel or dispenser) block will activate instead of drawing a mark
  - Shift can be held to draw on usable blocks, but only cross-mark can be drawn this way
  - New mark will not be drawn if it would be same as the old one (to save durability)

- Restored middle-click on a mark switching to appropriate colored chalk in survival

- Added Russian and Ukrainian translations

### 1.18 - 1.0.0 - 2021-12-01

- Updated to 1.18

- Added Japanese translation provided by RascalNiki
- Added Italian translation provided by Sim5

---

### 1.2.1 - 2021-10-19

- Added chalks to Desert Pyramid and Mason House chests

---

### 1.2.0 - 2021-10-17

- Added ❌-mark: drawn while sneaking
- Chalks now can be found in underground in dungeon and mineshaft chests. Villagers seems to be understanding usefulness of chalk too, some of their chests will contain chalk too.
- Added config file: Chalk durability, glow items, generation in chests can be changed
- Glowing Inc Sac from Upgrade Aquatic can be used to make mark glowing


- Enhanced Pick Block (Middle Click) - it will now select proper chalk from your inventory 
- Added dye tags to all chalks. You can now draw on Supplementaries Blackboard with them. Enable colored_blackboard in Supplementaries config for better results. 
- Added all chalks to "forge:chalk" tag
- Better offhand interactions: if you have something in offhand while drawing the mark - offhand item will not be used


- Toned down Glowing mark particles frequency
- Marks are now colored programmatically instead of colored textures

---

### 1.1.2 - 2021-10-12

- Glowing Inc Sac from "Caves and Cliffs Backport" can be used to make mark glowing
- Glowing marks will sometimes emit shiny particles


- Fixed Glowstone not consuming when used on a mark

---

### 1.1.1 - 2021-10-11

- Moved chalks to Decorations creative tab

  
- Fixed crash when starting a dedicated server
- Fixed crash with Xaero's Minimap

---

### 1.1.0 - 2021-10-10 - Shining Colors 🌈
**WARNING: Due to internal changes - existing drawn marks and chalks from previous version would be removed from world. 

I'm sorry, hopefully it will never happen again. (But who knows?)** 

---

Added:
- **Colored Chalks** for all 16 colors
- **Glowing marks**: use **Glowstone Dust** on a mark to make it really bright. It will slightly light up the surroundings too.

---

### 1.0.0 - 2021-10-04
- First Release