# Morning & Evening — Daily Adhkar Practice

> Part of the **Workshop-Diy** Islamic Kids Apps catalog.

## Overview

An interactive single-file HTML app for Muslim kids to practice their daily morning and evening adhkar (remembrances of Allah). Two modes: **Read** (scroll through adhkar with tap-to-count repetitions) and **Quiz** (match descriptions to the correct Arabic text).

## Features

- **Two Periods**: Morning (12 adhkar) and Evening (12 adhkar) with period-specific duas
- **Read Mode**: Each dhikr displayed as a card with Arabic text (with tashkeel), transliteration, English meaning, benefit, and a tap counter for repetitions. Auto-advances after completing all reps.
- **Quiz Mode**: Shows the benefit/description of a dhikr; pick the correct Arabic text from 4 options
- **Difficulty Levels**: Easy (6 core adhkar), Medium (10), Hard (all 12)
- **Daily Tracking**: Completed adhkar saved per day in localStorage with checkmarks
- **8 CSS Themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual UI**: English, French, Arabic (RTL auto-switch)
- **Sound Effects**: Web Audio API — no external files
- **Keyboard Shortcuts**: Space (tap counter), 1-4 (quiz answers), Arrow keys (navigate), Enter (start), Escape (close help)
- **High Score**: Best completion percentage persisted in localStorage
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Offline**: Single HTML file, zero dependencies, works without internet

## Adhkar Included

1. Ayat al-Kursi
2. Last 2 ayahs of Al-Baqarah
3. Al-Ikhlas (x3)
4. Al-Falaq (x3)
5. An-Nas (x3)
6. Morning/Evening dua (Asbahna.../Amsayna...)
7. Allahumma bika asbahna/amsayna
8. Sayyid al-Istighfar
9. SubhanAllah wa bihamdihi (x100)
10. La ilaha illallah wahdahu (x10)
11. SubhanAllahi wa bihamdihi SubhanAllahil Azeem
12. Salawat on the Prophet (x10)

## Usage

Open `index.html` in any modern browser. No server or build step required.

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-morning-evening` | High score (best %) |
| `wdiy-daily-morning-YYYY-MM-DD` | Daily morning completion |
| `wdiy-daily-evening-YYYY-MM-DD` | Daily evening completion |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Version

**v1.0** — Workshop-Diy
