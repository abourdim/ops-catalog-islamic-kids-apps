# Camel Caravan Loader

Interactive logistics puzzle where kids load supply camels for military campaigns, balancing weight between food, water, weapons, and medicine.

## Concept

Camels were the backbone of desert military logistics. The Quran mentions camels as signs of Allah's creation (88:17). The Prophet (peace be upon him) carefully planned supplies for every expedition, ensuring fair distribution even with limited resources. Players learn about military logistics by optimizing caravan loads.

## Gameplay

1. A random mission is assigned (Short Raid, Desert March, or Long Campaign)
2. Each mission has different weight limits and supply requirements
3. Use + and - buttons to load 8 types of supplies onto the camel
4. Watch the weight bar — overloading slows the caravan and costs points
5. Essential supplies (water, food, weapons, medicine) must meet minimums
6. Click Depart to calculate journey score based on balance and preparation

## Supplies

| Supply | Weight | Essential | Description |
|--------|--------|-----------|-------------|
| Water Skins | 8kg | Yes | Critical for desert travel |
| Dates & Bread | 5kg | Yes | Food for the troops |
| Swords & Arrows | 10kg | Yes | Weapons for battle |
| Medicine | 3kg | Yes | Treating wounded |
| Tools & Rope | 6kg | No | Utility items |
| Camel Feed | 7kg | No | Feed for the animal |
| Tent Materials | 12kg | No | Shelter |
| Gold Coins | 4kg | No | Trade and supplies |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- Visual weight bar with color-coded warnings
- Random mission generation for replayability
- Scoring system with essential supply penalties
- High score persistence via localStorage

## Lesson

Planning and logistics: Success in any endeavor requires careful preparation. The Prophet (peace be upon him) never embarked on a journey without proper planning. This teaches children the value of resource management and thoughtful preparation.

## Technical

- **HS_KEY**: `wdiy-hs-camel-caravan-loader`
- **Footer**: Workshop-Diy — Camel Caravan Loader v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
