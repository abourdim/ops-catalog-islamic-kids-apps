# Tactical Retreat — Workshop-Diy

Canvas-based tactical withdrawal game for Muslim kids. Part of the Gazawat series.

## Concept

Not every retreat is a defeat. A well-ordered withdrawal saves the army to fight another day. Players command an orderly retreat by placing rally flags on the canvas, guiding soldiers to safety, and protecting the rear guard.

- **Orderly retreat** = regroup and counter-attack (victory)
- **Disorderly retreat** = rout, soldiers scatter (game over)

## Scenarios

| # | Scenario | Historical Reference | Mechanic |
|---|----------|---------------------|----------|
| 1 | Fighting Retreat | Battle of Mu'tah (629 CE) — Khalid ibn al-Walid | Steady pullback under pressure. Rear guard soldiers slow enemies. |
| 2 | Feigned Retreat | Battle of Ain Jalut (1260 CE) — Mamluks vs Mongols | Lure enemies forward with flags, then counter-attack when they overextend. |
| 3 | Strategic Withdrawal | General tactic | Fall back to high ground zone for defensive advantage (stuns nearby enemies). |

## How to Play

1. Click **Start Mission** on the splash screen
2. Select a scenario from the dropdown
3. Press **New Game**
4. **Click/tap the canvas** to place rally flags (up to 5)
5. Blue circles = your soldiers; they move toward the nearest flag
6. Yellow circles = rear guard (Mu'tah scenario); they slow enemies
7. Red triangles = enemy forces advancing from the right
8. Guide soldiers to the **Safe Zone** (left edge) to save them
9. If too many soldiers get scattered (hit by enemies), the army routs
10. Save 50%+ of your soldiers to win

## Score

- **Soldiers saved** is the primary score
- High score stored in `localStorage` under key `wdiy-hs-retreat`

## Features

- Single HTML file, zero dependencies, fully offline
- 8 color themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (with RTL support)
- Web Audio API sound effects (no audio files)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Responsive canvas scales to fit screen
- Touch support for mobile/tablet
- localStorage persistence for theme, language, sound, and high score

## Tech

- Pure HTML5 Canvas + vanilla JavaScript
- No frameworks, no build tools, no external assets (except Google Fonts)
- `requestAnimationFrame` game loop
- All game state managed in-script

## File

```
040-retreat-and-regroup/
  index.html   — single-file app
  README.md    — this file
```

## HS_KEY

```
wdiy-hs-retreat
```
