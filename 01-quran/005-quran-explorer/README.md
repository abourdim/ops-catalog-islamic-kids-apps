# Quran Explorer

**Discover the surahs of the Quran** — An interactive Juz Amma browsing tool for Muslim kids.

## Features

- **37 Juz Amma surahs** (An-Naba #78 through An-Nas #114) with full metadata
- **Surah cards** showing: Arabic name, English name, surah number, ayah count, Makki/Madani, theme, and 3 key lessons
- **Quiz mode** with random questions (ayah count, Makki/Madani, main theme)
- **3 difficulty levels**: Easy (explore only), Medium (quiz after exploring), Hard (quiz without seeing the card)
- **Navigation**: dropdown selector, Prev/Next buttons, Random button
- **Progress tracking**: explored surahs count saved in localStorage
- **High score**: best quiz percentage saved in localStorage
- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages**: English, French, Arabic (with RTL support)
- **Sound effects** via Web Audio API (no external files)
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Keyboard shortcuts**: Left/Right arrows (navigate), R (random), Q (quiz), 1-4 (answer), Escape (close help), Enter (start)
- **Fully offline** — single HTML file, zero dependencies

## Usage

Open `index.html` in any modern browser. No server required.

## Storage Keys

| Key | Purpose |
|---|---|
| `wdiy-hs-quran-explorer` | Best quiz score (percentage) |
| `wdiy-quran-explored` | Array of explored surah numbers |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Tech

- Single-file HTML (~15KB)
- Zero external dependencies (fonts loaded from Google Fonts for aesthetics, works without)
- Web Audio API for sound
- localStorage for persistence
- CSS custom properties for theming

---

Workshop-Diy — Quran Explorer v1.0
