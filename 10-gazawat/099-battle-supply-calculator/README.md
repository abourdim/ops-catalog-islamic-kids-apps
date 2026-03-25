# Battle Supply Calculator

Math-based military logistics game where players calculate food, water, arrows, and equipment needed for armies of various sizes traveling various distances.

## Concept

Supplying an army was critical in every campaign. Players solve 8 supply problems with randomized army sizes and travel durations, calculating quantities of different supply types using multiplication, division, and rounding.

## The 8 Supply Types

| # | Supply | Calculation |
|---|--------|-------------|
| 1 | Food (kg) | soldiers x rate x days |
| 2 | Water (liters) | soldiers x rate x days |
| 3 | Arrows | soldiers x rate x days |
| 4 | Shields | 1 per soldier |
| 5 | Camels | total food weight / 150 kg capacity |
| 6 | Barley sacks | soldiers / 10 per day x days |
| 7 | Tents | soldiers / 8 per tent |
| 8 | Horses | 30% cavalry, 1 horse per 5 |

## Features

- Single HTML file, zero dependencies, fully offline
- Randomized army sizes (200-1000) and durations (2-7 days)
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Different math operations per supply type

## Lesson

Logistics and planning are essential parts of any endeavor. The Prophet carefully planned provisions for every campaign. This game teaches practical math skills while showing that preparation and calculation are forms of wisdom valued in Islam.

## Technical

- **HS_KEY**: `wdiy-hs-battle-supply-calculator`
- **Footer**: Workshop-Diy — Battle Supply Calculator v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
