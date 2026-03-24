# Battle Timeline Builder

> Map the campaigns of the Prophet &#65018; — Interactive timeline from 622 to 632 CE.

## Overview

A canvas-based drag-and-drop timeline builder where Muslim kids learn the chronological order of the Prophet's battles, expeditions, and key events during the Medina period.

## How to Play

1. Open `index.html` in any modern browser (zero dependencies, fully offline).
2. Click **Start Mission** on the splash screen.
3. Choose a difficulty level (Easy / Medium / Hard).
4. Drag battle cards from the tray onto the correct year position on the timeline.
5. **Correct placement** — card plants on the timeline with a green glow and a brief description appears.
6. **Wrong placement** — card bounces back with a red flash.
7. Complete the full timeline to see the historical progression.

## Difficulty Levels

| Level  | Cards | Content                                      |
|--------|-------|----------------------------------------------|
| Easy   | 8     | Major battles: Badr, Uhud, Khandaq, Mecca... |
| Medium | 14    | + Banu Qaynuqa, Mu'tah, Hunayn, Tabuk...     |
| Hard   | 22    | All events including treaties and missions    |

## Events Included (22 total)

- **622** — Hijrah, Constitution of Medina
- **624** — Battle of Badr, Banu Qaynuqa
- **625** — Battle of Uhud, Banu Nadir
- **626** — Banu Mustaliq
- **627** — Battle of Khandaq (Trench), Banu Qurayza
- **628** — Treaty of Hudaybiyyah, Battle of Khaybar, Dhat al-Riqa
- **629** — Battle of Mu'tah, Umrah al-Qadiyyah
- **630** — Conquest of Mecca, Hunayn, Siege of Taif, Tabuk, Destruction of Idols
- **631** — Missions to Yemen
- **632** — Farewell Pilgrimage, Usama's Expedition

## Strategy Evolution (shown on timeline)

1. **Early / Defensive** (622-625) — Badr, Uhud
2. **Siege Defense** (627) — Khandaq (Trench)
3. **Offensive** (628-630) — Khaybar, Mu'tah, Hunayn, Tabuk
4. **Peaceful Conquest** (628-632) — Hudaybiyyah, Conquest of Mecca, Farewell Pilgrimage

## Features

- Canvas-based interactive horizontal timeline (622-632 CE)
- Drag-and-drop with mouse and touch support
- Phase-colored zones (defensive, siege, offensive, peaceful)
- Green glow on correct placement, red flash on wrong
- Auto-scroll completion animation
- 8 CSS themes (Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand)
- Trilingual (EN / FR / AR with RTL support)
- Sound effects via Web Audio API (no files)
- High score persistence via localStorage
- Timer, progress bar, activity log
- Sidebar help panel (FAQ, How-To, Wiki)
- Keyboard shortcuts (Enter to start, H for help, Esc to close)
- Single HTML file, zero dependencies, fully offline

## Technical

- **HS_KEY**: `wdiy-hs-battle-timeline`
- **Stack**: Single HTML file, vanilla JS, Canvas API
- **Fonts**: Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
- **Persistence**: localStorage for theme, language, sound, high score

## License

Workshop-Diy — Battle Timeline v1.0
