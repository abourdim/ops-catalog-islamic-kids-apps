# Battle Sandbox

**Design your own battlefield** — a canvas-based strategy sandbox for Muslim kids.

## Overview

Place units, terrain, and fortifications on a grid canvas. Load historical battle setups from early Islamic history, experiment with positioning and terrain advantage, then run a basic simulation to see how forces interact.

## Features

- **Toolbar with 15 placeable elements**: Infantry, Cavalry, Archers (green/red), Walls, Trenches, Catapults, Mountains, Rivers, Trees, Camps
- **Grid-based placement** for neat alignment (25px cells)
- **Drag to reposition** any placed unit
- **6 preset scenarios**: Badr Setup, Uhud Setup, Khandaq Setup, Open Field, Mountain Pass, River Crossing
- **Simulate button**: basic battle animation — infantry advances, cavalry flanks, archers fire at range, walls/mountains/trenches block movement
- **Undo / Clear / Save / Restore** — layout persists to localStorage
- **No scoring** — pure creative/educational sandbox

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Start Mission (splash) |
| `Space` | Toggle simulation |
| `Escape` | Deselect tool / close help |
| `Ctrl+Z` | Undo |
| `Ctrl+S` | Save layout |
| `Delete` | Clear battlefield |

## Historical Scenarios

- **Badr (2 AH)**: Open desert engagement, smaller Muslim force vs larger Quraysh army
- **Uhud (3 AH)**: Mountain at rear providing cover, archers positioned on hill to guard flank
- **Khandaq (5 AH)**: Trench (khandaq) defensive line protecting Madinah from coalition forces

## Template Compliance

Follows the Workshop-Diy single-file HTML template:
- 8 CSS themes (Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand)
- Splash screen with Bismillah
- Sidebar help panel with FAQ / How-To / Wiki tabs
- Language switcher (EN / FR / AR with RTL support)
- Sound via Web Audio API (no external files)
- Persisted preferences (theme, language, sound, layout)
- Back-link to catalog
- Single HTML file, zero dependencies, fully offline

## Keys

- `HS_KEY`: `wdiy-hs-siege-sandbox`
- Layout storage: `wdiy-siege-layout`

## Footer

Workshop-Diy — Battle Sandbox v1.0
