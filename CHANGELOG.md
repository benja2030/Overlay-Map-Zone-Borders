# Changelog

## 1.1.2 (not released yet)

- Cave entrances are open: in 26 caves with a Blizzard cave map (Shadowthread Cave, Fel Rock, Fargodeep Mine, the Deadmines...), the cut opens at the entrance and fades into the land outside, instead of closing the way out like a wall (Cave\m<id>.tga, made from OpenMap's mask of each cave). Needs Overlay Map 1.2.6.
- Fixed: Alterac Mountains' outline took in the corner of Silverpine Forest and Hillsbrad Foothills that its map picture paints, cut off in two straight lines at the picture's edge (around Dalaran). It now follows the real border there, from the game's own record of which zone each patch of ground belongs to; Dalaran stays whole inside it.
- Overlay Map's logo next to it in the game's AddOns list.

## 1.1.1 (2026-11-22)

- Fixed: the cave outlines (Caves.lua and the Cave folder) were missing from the 1.1.0 package, which showed "Error loading Caves.lua" at login and left caves cut to a plain box.

## 1.1.0 (2026-11-21)

- Cave outlines: the real shape of 248 caves, mines and underground places, for Overlay Map's Zone Border inside them (Overlay Map 1.2.2 or later, with OpenMap). Each one is made from the pictures the game's minimap draws the cave with. A sharp and a soft version of each.

## 1.0.0 (2026-11-20)

- First version: the zone outlines for Overlay Map's Zone Border option (Overlay Map 1.1.6 or later), as a separate download. One outline per zone and capital city of Kalimdor and the Eastern Kingdoms, a soft version of each, and the versions for each Outside Your Zone opacity.
