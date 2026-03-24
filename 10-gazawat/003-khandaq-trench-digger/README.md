# Battle of Khandaq — Trench Digger

> Dig the trench that saved Medina

## Overview

An interactive canvas-based game where kids learn about the Battle of the Trench (Khandaq, 5 AH / 627 CE). Players draw a trench across the unprotected north side of Medina, assign digging teams, and race against a 6-day deadline before the 10,000-strong Quraysh coalition arrives.

## Gameplay

1. **Intro**: Salman Al-Farisi appears and suggests the trench idea (a Persian military strategy never used in Arabia)
2. **Draw Phase**: Click and drag across the north side of the top-down map to mark all 10 trench sections
3. **Assign Workers**: Select worker icons and click trench sections to assign them. Rocky sections need more workers
4. **Dig Phase**: Press "Next Day" to advance. Workers dig based on their assignment and section difficulty
5. **Siege**: When the trench is complete, watch the Quraysh army arrive and fail to cross
6. **Lesson**: Learn about shura (consultation), innovation, and teamwork

## Features

- **Top-down map** of Medina with city center, eastern/southern mountains, and open north side
- **Canvas drawing** — click and drag to draw the trench path
- **Worker management** — drag/assign worker icons to trench sections
- **Rocky obstacles** — some sections are rocky, need more workers, and dig slower
- **6-day timer** — complete the trench before the enemy arrives
- **3 difficulty levels** — Easy (more workers, faster), Medium, Hard (fewer workers, more rocks)
- **Siege animation** — 10,000 Quraysh forces arrive and are blocked by the trench
- **Victory lesson** — shura, innovation, working together, trust in Allah

## Template Compliance

- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Splash screen with bismillah, title, subtitle, start button
- Language switcher: EN / FR / AR (RTL support)
- Sidebar help panel with FAQ, How-To, Wiki tabs
- Keyboard shortcuts (Enter, Space, 1-9, N for next day, Escape)
- High score persistence (`wdiy-hs-khandaq-trench`)
- Sound/theme/language preferences persisted in localStorage
- Web Audio API sounds (no external files)
- Back-link to catalog
- Single HTML file, zero dependencies, fully offline

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Enter` | Start game / Advance day |
| `Space` | Skip intro |
| `1`-`9` | Select/toggle worker |
| `N` | Next day |
| `Escape` | Close help sidebar |

## Technical

- **Single file**: `index.html` (zero external dependencies except Google Fonts)
- **Canvas**: 680x440 top-down map rendering
- **Touch support**: Full touch/drag support for mobile devices
- **Storage key**: `wdiy-hs-khandaq-trench`
- **Footer**: Workshop-Diy — Battle of Khandaq v1.0
