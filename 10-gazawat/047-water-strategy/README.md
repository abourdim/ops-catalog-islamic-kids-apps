# Water Wars — Desert Water Strategy

**HS_KEY:** `wdiy-hs-water-strategy`

## Overview

Canvas-based resource control strategy game for Muslim kids. Control a Muslim army competing for desert water sources (wells, oases, rivers). Inspired by the wells strategy at the Battle of Badr, where the Muslim army secured water sources before the battle began.

## Gameplay

- **Objective:** Secure water sources, guard them, deny water to the enemy
- **Turn-based:** Each turn, select units, move/secure/guard, then end turn
- **Water economy:** Armies consume water each turn. Without water, units lose HP
- **Win conditions:** Eliminate all enemy units, or control more water sources by turn 20
- **Enemy AI:** Seeks uncontrolled water sources, attacks Muslim units when all sources are contested

## Actions

| Action | Description |
|--------|-------------|
| Move | Move a unit up to 3 tiles (Manhattan distance) |
| Secure Well | Move to a water source and claim it for your army |
| Guard | Station a unit at a secured well to defend it |
| End Turn | Finishes your turn, triggers water consumption, then enemy AI moves |

## Maps

1. **Badr Wells** — Scattered wells with a central oasis, dune terrain on flanks
2. **Oasis Valley** — Central oasis with corner wells and river sources
3. **River Canyon** — Vertical river dividing the map, with side wells

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based rendering (640x440)
- 8 themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Sound via Web Audio API (no audio files)
- Sidebar help panel with FAQ, How-To, Wiki tabs
- High score persistence via localStorage
- Keyboard shortcuts: 1/2/3 for actions, E for end turn
- Splash screen with bismillah

## Historical Reference

At Badr, al-Hubab ibn al-Mundhir advised the Prophet (peace be upon him) to position the army near the wells and deny water access to the Quraysh. This strategic water control was a key factor in the Muslim victory.

## Tech

- **Rendering:** HTML5 Canvas 2D
- **State:** Pure JS, no frameworks
- **Storage:** localStorage for high scores, theme, language, sound prefs
- **Audio:** Web Audio API oscillators
