# Spoils Division (Ghanaim) — Workshop-Diy

Interactive math/distribution tool teaching Islamic rules of war spoils division.

## Overview

After a battle, spoils arrive: camels, sheep, gold, weapons, supplies. The child must calculate:

- **1/5 (Khums)** goes to Bayt al-Mal (state treasury, orphans, poor, travelers)
- **4/5** goes to the fighters
- **Cavalry** get triple share (2 for horse + 1 for rider); infantry get 1 share

Reference: **Quran 8:41**

## Game Flow (3 Phases)

### Phase 1 — Calculate Khums
Visual display of spoils with emoji items. Child calculates 1/5 (Khums) and 4/5 (fighters pool) from the total. Draggable spoil items for visual engagement.

### Phase 2 — Distribute Among Fighters
Given infantry and cavalry counts, child calculates:
- Total shares (cavalry x 3 + infantry)
- Value per share (fighters pool / total shares)
- Infantryman's share (1x share value)
- Cavalryman's share (3x share value)

### Phase 3 — Quiz
4 multiple-choice questions per scenario testing comprehension:
- What fraction is Khums?
- How much does a cavalryman get?
- Total shares calculation
- Quranic reference (8:41)

## 5 Scenarios

| # | Name | Spoils | Infantry | Cavalry |
|---|------|--------|----------|---------|
| 1 | Battle of Small Oasis | 215 items | 30 | 10 |
| 2 | Caravan Encounter | 300 items | 20 | 5 |
| 3 | Fortress Victory | 750 items | 80 | 20 |
| 4 | Desert Patrol | 100 items | 12 | 3 |
| 5 | Great Conquest | 1440 items | 150 | 50 |

## Features

- **Single HTML file**, zero dependencies, fully offline
- **8 themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages**: English, French, Arabic (RTL auto-enabled)
- **Sound**: Web Audio API (toggle on/off)
- **High score**: persisted in localStorage (`wdiy-hs-spoils`)
- **Preferences**: theme, language, mute state all persisted
- **Splash screen** with bismillah
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Timer** tracking session duration
- **Activity log** for all actions
- **Keyboard shortcuts**: 1-4 for quiz answers, Enter to start, Escape to close help

## Technical

- HS_KEY: `wdiy-hs-spoils`
- Template: follows exact Workshop-Diy catalog structure
- Fonts: IBM Plex Mono, Outfit, Noto Sans Arabic (Google Fonts)
- No build step, no bundler, no frameworks
