# Prophet Timeline

**Order the Prophets of Allah** — an interactive chronological sorting game for Muslim kids.

## How It Works

Cards showing the 25 prophets mentioned in the Quran appear in random order. The player must tap them in the correct chronological sequence. Each correct tap adds the prophet to a visual timeline and reveals a brief fact.

## Prophets (25)

Adam, Idris, Nuh, Hud, Salih, Ibrahim, Lut, Ismail, Ishaq, Yaqub, Yusuf, Shuaib, Ayyub, Musa, Harun, Dhul-Kifl, Dawud, Sulaiman, Ilyas, Al-Yasa, Yunus, Zakariya, Yahya, Isa, Muhammad ﷺ

## Features

- **3 Difficulty Levels**: Easy (10 prophets), Medium (15), Hard (all 25)
- **8 Themes**: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 Languages**: English, French, Arabic (with RTL support)
- **Progress Tracking**: Timer, progress bar, accuracy score, high score persistence
- **Fun Facts**: Each prophet card reveals a brief fact after correct placement
- **Sound Effects**: Web Audio API — correct, wrong, and win sounds (toggleable)
- **Keyboard Shortcuts**: Enter to start, 1-9 to tap cards, Escape to close help
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Offline**: Single HTML file, zero dependencies, works without internet
- **Privacy**: No tracking, no analytics, all data stays in localStorage

## Tech

Single-file HTML with inline CSS and JS. No build step, no frameworks, no external assets beyond Google Fonts.

## Storage Keys

| Key | Purpose |
|---|---|
| `wdiy-hs-prophet-timeline` | High score (accuracy %) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

---

Workshop-Diy — Prophet Timeline v1.0
