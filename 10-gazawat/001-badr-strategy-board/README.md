# Battle of Badr — Strategy Board Game

> Plan the strategy that changed history

A canvas-based battlefield strategy game for Muslim kids. Position 313 Muslim soldiers on the plains of Badr against 1000 Quraysh — learn why the Prophet (peace be upon him) chose to control the wells, how Hubab ibn al-Mundhir's advice shaped the strategy, and how trust in Allah combined with proper planning led to victory.

## Gameplay

1. **Drag** the 5 green Muslim unit groups from the camp to strategic positions on the map
2. **Control the wells** (blue circles) — denying water to the Quraysh is critical
3. **Take the high ground** — position at least one unit on the hills (brown)
4. **Spread your formation** — units should cover the strategic zone between camps
5. **Execute Battle** — the simulation scores your strategy (wells 40%, high ground 30%, formation 30%)
6. **Show Historical** — toggle gold circles showing the actual positions from the battle

## Victory Conditions

| Condition | Weight | Requirement |
|-----------|--------|-------------|
| Wells Control | 40% | Place units within range of all 3 wells |
| High Ground | 30% | At least 1 unit on a hill |
| Formation | 30% | 3+ units in the middle zone, spread across Y-axis |

Score 80%+ to win and unlock the historical info panels about Hubab's advice, the Prophet's dua, and angel reinforcement.

## Features

- **Canvas battlefield** — top-down map with wells, palm trees, hills, two army camps
- **Drag-and-drop** — mouse and touch support for positioning units
- **Battle simulation** — evaluates well control, terrain advantage, formation
- **Historical overlay** — shows actual positions from the Battle of Badr
- **Info panels** — Hubab ibn al-Mundhir's advice, dua at Badr, angel reinforcement, Islamic lesson
- **8 CSS themes** — Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages** — EN / FR / AR with RTL support
- **Sound effects** — Web Audio API (no files), toggle on/off
- **Keyboard shortcuts** — Enter (execute), R (reset), H (historical), N (new), Esc (close help)
- **Persisted preferences** — theme, language, sound, high score via localStorage
- **Sidebar help** — FAQ, How-To, Wiki tabs
- **Single HTML file** — zero dependencies, fully offline

## Keys

| Key | Action |
|-----|--------|
| `Enter` | Start mission / Execute battle |
| `R` | Reset positions |
| `H` | Toggle historical positions |
| `N` | New battle |
| `Esc` | Close help sidebar |

## Storage

| Key | Purpose |
|-----|---------|
| `wdiy-hs-badr-strategy` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Tech

- Single `index.html`, zero external dependencies (fonts optional)
- HTML5 Canvas for battlefield rendering
- Web Audio API for sound effects
- CSS custom properties for theming
- localStorage for persistence
- Touch + mouse event handling

---

Workshop-Diy — Battle of Badr v1.0
