# Ambush Planner

**Category:** Ghazawat (10)
**ID:** 041
**HS_KEY:** `wdiy-hs-ambush`

## Overview

A canvas-based terrain strategy game for Muslim kids. Players plan ambushes by placing hidden units behind hills and in trees, then trigger the ambush when the enemy column enters the kill zone. Timing and placement are key.

## Gameplay

1. **Place Units** — Select unit chips (Archers, Swordsmen) and click on valid terrain (hills or trees) on the canvas map to position them.
2. **Watch the March** — An enemy column marches along the road through the terrain.
3. **Trigger the Ambush** — Click the TRIGGER AMBUSH button (or press Space) when enemies are inside the kill zone (red dashed rectangle).
4. **Scoring** — Enemies inside the kill zone and in range of your units are "engaged." Those outside escape. Too early or too late reduces your score.

## Scenarios (5 total)

| # | Name | Terrain | Enemy Count |
|---|------|---------|-------------|
| 1 | Valley Pass | Hills on both sides of a narrow valley | 8 |
| 2 | Forest Road | Dense tree cover flanking a winding road | 10 |
| 3 | Hill Crossing | Rolling hills with a road between ridges | 9 |
| 4 | Desert Ravine | Rocky ravine with hills and sparse trees | 12 |
| 5 | Mountain Path | Steep mountain trail, single-file march | 14 |

## Historical Reference

Each scenario includes a historical insight about how the Prophet (peace be upon him) and the Sahabah used terrain advantage in battles such as Badr, Uhud, and the Trench (Khandaq).

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based rendering with terrain (hills, trees, roads, kill zones)
- 8 themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- 3 languages: EN, FR, AR (with RTL support)
- Web Audio API sound effects (click, boom, win melody)
- High score persistence via localStorage
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Touch support for mobile devices
- Keyboard shortcuts: Space to trigger, Enter to start

## Tech

- Pure HTML/CSS/JS, no frameworks
- Canvas 2D API for map rendering
- Responsive canvas scaling
- localStorage for high score (`wdiy-hs-ambush`), theme, language, sound prefs

## File Structure

```
041-ambush-planner/
  index.html   — Single-file game (HTML + CSS + JS)
  README.md    — This file
```
