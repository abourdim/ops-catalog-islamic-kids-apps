# Arrow Rain

Canvas-based archery physics game for Muslim kids.

## Overview

Kids adjust bow **angle** (5-85 degrees) and **power** (1-10) to arc arrows at shield targets placed at various distances. The arrow follows a realistic parabolic trajectory. Wind affects harder difficulties.

## Features

- **Canvas archery physics** — projectile motion with gravity and wind
- **Trajectory preview** — dotted arc shows predicted path before firing
- **3 difficulties** — Easy (no wind, large shields), Medium (light wind), Hard (strong wind, small shields)
- **Score tracking** — hits, shots, accuracy percentage
- **High score** — best accuracy % persisted in localStorage (`wdiy-hs-arrow-rain`)
- **8 CSS themes** — Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual** — EN / FR / AR with RTL support
- **Sound effects** — Web Audio API (fire whoosh, hit, miss, win melody)
- **Sidebar help** — FAQ, How-To, Wiki with note about Muslim archers at Badr/Uhud
- **Keyboard shortcuts** — Space to fire, Arrow keys for angle/power, Enter to start, Escape to close help
- **Splash screen** — Opens with Bismillah
- **Single HTML file** — zero dependencies, fully offline

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| Space | Fire arrow |
| Up/Down | Adjust angle |
| Left/Right | Adjust power |
| Enter | Start game |
| Escape | Close help |

## Islamic Context

The Wiki section includes a note about Muslim archers at the Battles of Badr (2 AH) and Uhud (3 AH), where the Prophet Muhammad (peace be upon him) positioned archers strategically, highlighting archery as a valued skill in early Islam.

## Tech

- Single `index.html`, no build step
- HTML5 Canvas for rendering
- CSS custom properties for theming
- localStorage for preferences and high score
- Web Audio API for sound
