# Arabic Numbers — Number Matching Game

**Workshop-Diy — Arabic Numbers v1.0**

An interactive Arabic number matching game for Muslim kids. Single HTML file, zero dependencies, fully offline.

## Game

Kids are shown a number in one of three forms and must match it:

1. **Eastern Arabic numeral** (e.g. ٧) → pick the Western digit (7)
2. **Arabic word** (e.g. سَبْعَة) → pick the correct digit
3. **Western digit** (e.g. 7) → pick the Arabic word

After each correct answer, all three forms are displayed together (Eastern Arabic numeral, Arabic word, Western digit).

## Numbers Covered

- **Easy**: 0–10
- **Medium**: 0–20
- **Hard**: 0–100 (including tens: 30, 40, 50, 60, 70, 80, 90, 100)

All numbers include full tashkeel (diacritics).

## Features

- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- Trilingual UI: English, French, Arabic (with RTL)
- Splash screen with Bismillah
- Multiple choice (4 options)
- Sound effects via Web Audio API (no files)
- High score persistence (localStorage)
- Theme/language/sound preferences persisted
- Keyboard shortcuts: 1–4 for answers, Enter to start, Escape to close help
- Sidebar help panel with FAQ, How-To, Wiki tabs
- Back-link to catalog
- Progress bar and score tracking
- Activity log

## Storage Key

`wdiy-hs-arabic-numbers`

## Usage

Open `index.html` in any modern browser. No server or build step required.
