# Saladin's Spies — Intelligence Network Game

**HS_KEY:** `wdiy-hs-saladin-spies`

## Overview

A canvas-based strategy intelligence game where kids deploy spy agents across the three Crusader states (Kingdom of Jerusalem, County of Tripoli, Principality of Antioch) to gather intel for Saladin's campaign leading to the Battle of Hattin (1187 CE).

## Gameplay

### Three Phases

1. **Deployment Phase** — Select spies from the tray and click cities on the map to place them. Spread them wisely across all three Crusader states. Too many spies in one region triggers detection risk.
2. **Intelligence Gathering** — Watch your spies collect reports on troop movements, supply levels, political tensions, and fortress weaknesses. Coverage across all three regions boosts intel quality; clustering triggers detection penalties.
3. **Battle Planning Quiz** — Answer questions based on gathered intel: "Where is the main army?", "Which fortress is weakest?", "Are the Crusader states united or divided?", etc. Good intel = better answers = higher battle score.

### Difficulty Levels

| Level  | Spies | Detection Threshold | Gather Rounds | Quiz Questions |
|--------|-------|---------------------|---------------|----------------|
| Easy   | 6     | 3 per region        | 3             | 4              |
| Medium | 5     | 2 per region        | 5             | 5              |
| Hard   | 4     | 2 per region        | 7             | 6              |

### Scoring

- **Battle Score** = Intel Gathered (40%) + Quiz Accuracy (60%)
- 80%+ = Decisive Victory
- 50-79% = Victory with losses
- Below 50% = Insufficient preparation

## Lesson

Knowledge is power. Preparation wins wars. Saladin's real-world success at Hattin was built on superior intelligence, patience, and strategic planning.

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-rendered map of the Crusader states with interactive cities
- Drag-to-deploy spy placement system
- Real-time intelligence gathering with animated progress
- Detection risk mechanic for strategic depth
- Quiz phase with randomized ground truth each game
- 8 themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- 3 languages: EN, FR, AR (with RTL support)
- Web Audio API sound effects (no external files)
- High score persistence via localStorage
- Theme/language/sound preferences persisted
- Keyboard shortcuts (1-4 for answers, Enter to start)
- Touch support for mobile devices
- Responsive canvas scaling

## Tech

- Pure HTML/CSS/JS — no frameworks, no build step
- Canvas 2D API for map rendering
- Web Audio API for sound
- localStorage for preferences and high scores
- Follows the Workshop-Diy template structure exactly
