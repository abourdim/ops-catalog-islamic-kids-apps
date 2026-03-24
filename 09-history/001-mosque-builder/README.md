# Mosque Builder

**Build a mosque piece by piece** — an interactive canvas-based game for Muslim kids.

## Overview

Kids learn mosque architecture by placing each structural element in the correct position on a canvas. Each correctly placed element draws on the mosque and reveals its Islamic significance.

## Elements (12 total)

| # | Element | Description |
|---|---------|-------------|
| 1 | Foundation | Base rectangle at bottom |
| 2 | Walls | Side rectangles forming the prayer hall |
| 3 | Dome | Semicircle on top center |
| 4 | Minaret | Tall tower with pointed top |
| 5 | Mihrab | Arch niche indicating Qibla direction |
| 6 | Minbar | Stepped pulpit for sermons |
| 7 | Courtyard | Open area in front |
| 8 | Fountain / Wudu Area | Circle in the courtyard |
| 9 | Entrance Door | Arched door at front |
| 10 | Windows | Small arches on walls |
| 11 | Crescent | Gold symbol atop the dome |
| 12 | Carpet Area | Prayer rows inside |

## Difficulty Levels

- **Easy** — 6 main elements (Foundation, Walls, Dome, Minaret, Mihrab, Minbar)
- **Medium** — 9 elements (+ Courtyard, Fountain, Entrance Door)
- **Hard** — All 12 elements

## Gameplay

1. Read the element name shown above the canvas
2. Click/tap the canvas where that element belongs
3. Correct placement draws the element and shows its Islamic significance
4. Wrong click flashes red — try again
5. Complete all elements to finish the mosque

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based drawing with simple geometric shapes
- 8 CSS themes (Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand)
- Trilingual UI (EN / FR / AR with RTL support)
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Dashed target zone hints for guidance
- Islamic significance info for each element
- Progress bar and accuracy tracking
- Keyboard shortcuts (Enter to start)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Touch support for mobile devices

## Storage Keys

- `wdiy-hs-mosque-builder` — High score (accuracy %)
- `wdiy-lang` — Language preference
- `wdiy-theme` — Theme preference
- `wdiy-mute` — Sound mute state

## Tech

- Pure HTML + CSS + JS, single file
- Canvas 2D API for mosque rendering
- Web Audio API for sounds
- localStorage for persistence
- No frameworks, no build tools, no external assets

---

**Workshop-Diy — Mosque Builder v1.0**
