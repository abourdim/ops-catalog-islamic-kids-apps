# Khandaq Supply Line

> Survive the month-long siege

A canvas-based resource management game for Muslim kids set during the Battle of the Trench (Khandaq, 5 AH). Single HTML file, zero dependencies, fully offline.

## Gameplay

- **Setting:** Medina is besieged by a coalition of 10,000 soldiers. A trench on the northern approach and mountains to the east/south protect the city. 3,000 defenders hold the line.
- **Goal:** Survive 27 days until Allah sends a divine wind to scatter the enemy (Quran 33:9).
- **Lose condition:** Any resource (Food, Water, Firewood, Morale, Trench integrity) drops to zero.

### Resources
| Resource | Description |
|----------|-------------|
| Food | Dates and grain for the defenders |
| Water | Collected from wells |
| Firewood | For warmth and cooking |
| Morale | Spirit of the defenders |
| Trench | Structural integrity of the defensive trench |

### Actions (pick 2 per day)
- **Ration Food** — distribute food carefully
- **Fetch Water** — send teams to collect water
- **Collect Firewood** — gather wood for fires
- **Patrol Trench** — guard against enemy probes
- **Boost Morale** — make dua and encourage defenders
- **Send Scouts** — gather intel on enemy movements
- **Repair Trench** — strengthen weak trench sections

### Random Events
- Cold nights (firewood drops)
- Enemy attempts to cross the trench
- Sandstorms scatter supplies
- Hunger among defenders
- Arrow volleys
- Hidden wells discovered
- Moments of reflection and dua

### Scripted Historical Events
- **Day 5:** Salman al-Farisi's trench reinforcement technique
- **Day 12:** Nu'aym ibn Mas'ud offers to sow discord among enemy allies (historical turning point)
- **Day 18:** Results of Nu'aym's plan (if accepted)
- **Day 20:** Banu Qurayza threat from within Medina
- **Day 27+:** Divine wind scatters the enemy

### Difficulty Levels
- **Easy:** Slower resource drain, more starting supplies
- **Normal:** Balanced
- **Hard:** Faster drain, tougher events

## Lessons
- Patience (sabr) under hardship
- Trust in Allah (tawakkul)
- Unity of the Muslim community
- Clever diplomacy and strategy

## Features
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- Trilingual support: EN / FR / AR (with RTL)
- Canvas map showing Medina, trench, mountains, enemy camp
- Splash screen with bismillah
- Sidebar help panel (FAQ, How-To, Wiki)
- Sound effects via Web Audio API (no files)
- High score persistence (localStorage)
- Theme/language/sound preferences persisted
- Keyboard shortcuts (1-7 for actions, A/B for event choices, Enter to start, Esc to close help)
- Fully offline, single HTML file, zero external dependencies

## Storage Keys
- `wdiy-hs-khandaq-supply` — high score (furthest day survived)
- `wdiy-lang` — language preference
- `wdiy-theme` — theme preference
- `wdiy-mute` — sound mute state

## Footer
Workshop-Diy — Khandaq Supply Line v1.0
