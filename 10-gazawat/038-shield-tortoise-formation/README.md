# Shield Wall — Tortoise Formation Game

**Workshop-Diy** | Islamic Kids Apps Catalog | Gazawat Series (#038)

## Overview

A canvas-based formation builder game for Muslim kids. Players drag shield icons onto a grid to create a protective tortoise (testudo) formation, then watch as arrows rain down. Gaps in the formation mean casualties — perfect coverage means a safe advance.

## Gameplay

1. **Setup Phase** — Drag shields from the tray onto the grid cells to cover soldiers
2. **Arrow Phase** — Press "Advance!" and arrows rain down on the formation
3. **Result** — Shielded cells block arrows; unshielded cells cause casualties

## Levels

| Difficulty | Grid | Shields | Soldiers | Arrows |
|-----------|------|---------|----------|--------|
| Easy | 3x2 | 6 | 6 | 12 |
| Medium | 4x3 | 12 | 12 | 20 |
| Hard | 5x4 | 20 | 20 | 35 |

## Lesson

- **Teamwork** — Every shield matters; one gap exposes the group
- **Discipline** — Proper formation requires careful placement
- **Protecting each other** — Covering your neighbor is a duty

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based rendering with drag-and-drop shield placement
- Touch support for mobile/tablet
- 8 color themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Keyboard shortcuts: Enter to start, Space to advance

## Technical

- **HS_KEY**: `wdiy-hs-shield-wall`
- **Stack**: Vanilla HTML5 Canvas + CSS + JS
- **Storage**: localStorage only
- **Network**: None (fully offline)

## File

```
038-shield-tortoise-formation/
  index.html   — Complete game (single file)
  README.md    — This file
```
