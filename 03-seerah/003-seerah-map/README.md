# Seerah Map

**Journey through the Prophet's life ﷺ**

An interactive canvas-based map quiz for Muslim kids. Read an event from the life of Prophet Muhammad ﷺ, then click the correct location on a simplified map of the Arabian Peninsula.

## Features

- **Canvas map** with labeled location dots across the Arabian Peninsula
- **24 events/questions** covering birth, hijrah, battles, treaties, and more
- **3 difficulty levels**: Easy (6 locations), Medium (9), Hard (12)
- **Fun facts** displayed after each answer
- **Progress bar, timer, and score tracking** with persistent high score
- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages**: English, French, Arabic (with RTL support)
- **Sound effects** via Web Audio API (no external files)
- **Keyboard shortcuts**: Enter to start, Escape to close help
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Fully offline** — single HTML file, zero dependencies

## Locations

| Tier | Locations |
|------|-----------|
| Easy (6) | Mecca, Medina, Taif, Badr, Uhud, Cave Hira |
| +Medium (9) | Khandaq, Hudaybiyyah, Khaybar |
| +Hard (12) | Cave Thawr, Tabuk, Abyssinia |

## How to Play

1. Open `index.html` in any modern browser
2. Click **Start Mission**
3. Select difficulty and press **New Game**
4. Read the event question at the top
5. Click the correct location dot on the map
6. Learn a fact after each answer

## Storage Keys

- `wdiy-hs-seerah-map` — High score (percentage)
- `wdiy-lang` — Language preference
- `wdiy-theme` — Theme preference
- `wdiy-mute` — Sound preference

## Tech

Single-file HTML. No build step, no dependencies, no network calls. Runs entirely in the browser.

---

Workshop-Diy — Seerah Map v1.0
