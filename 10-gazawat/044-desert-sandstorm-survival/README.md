# Sandstorm — Desert Sandstorm Survival

**Workshop-Diy** | Category: Gazawat (044)

## Overview

A canvas-based desert survival simulation for Muslim kids. An army on the march is hit by a sandstorm. The player must secure camels, protect soldiers' eyes, find shelter behind dunes, and regroup scattered units before time runs out.

## Gameplay

The game runs through 4 phases within a timed storm (60-120 seconds):

| Phase | Task | Action |
|-------|------|--------|
| 1 — Camels | Secure loose camels before the wind blows them away | Click each camel to tie it down |
| 2 — Cloth | Protect soldiers' eyes from blinding sand | Click each soldier to distribute cloth |
| 3 — Shelter | Move scattered units behind dunes for protection | Drag units into yellow shelter zones |
| 4 — Regroup | Storm clears, reform the army formation | Click scattered units to regroup them |

## Features

- Single-file HTML, zero dependencies, fully offline
- Canvas-based rendering with sand particle effects and visibility drop
- Wind sound effects via Web Audio API (no audio files)
- 3 difficulty levels: Easy (60s), Medium (90s), Hard (120s)
- 8 themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (with RTL support)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- High score persistence via localStorage
- Touch and mouse input support (mobile-friendly)
- Splash screen with Bismillah

## Historical Context

Desert sandstorms played significant roles in Islamic military history:

- **Battle of the Trench (Khandaq, 627 CE):** Allah sent a fierce wind against the confederate armies besieging Madinah, scattering their camps and extinguishing their fires, leading to their retreat.
- **Battle of Qadisiyyah (636 CE):** Sandstorms during this decisive battle against the Sassanid Empire aided the Muslim forces in their victory.

These events demonstrate how natural phenomena were part of Allah's plan to aid the believers.

## Technical Details

- **HS_KEY:** `wdiy-hs-sandstorm`
- **Canvas:** Responsive, scales to container width
- **Particle system:** 200 sand particles with varying speed, size, and opacity
- **Storm intensity:** Gradually increases visibility overlay and particle speed
- **Template:** Matches the standard Workshop-Diy app structure (splash, app, sidebar, themes, langs, sound, timer, log, high score)

## File Structure

```
044-desert-sandstorm-survival/
  index.html    — Complete game (single file, no dependencies)
  README.md     — This file
```

## How to Run

Open `index.html` in any modern browser. No server required.
