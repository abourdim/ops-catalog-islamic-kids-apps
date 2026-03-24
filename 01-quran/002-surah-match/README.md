# Surah Match

**Match facts to surahs** — an interactive quiz game for Muslim kids.

## How It Works

A fact is displayed (number of ayahs, Makki/Madani, main theme, or a distinctive feature) and the player picks the correct surah name from 4 multiple-choice options. After each correct answer, the surah's Arabic name, number, and a brief description are shown.

## Surah Coverage

- **Major surahs:** Al-Fatiha, Al-Baqarah, Aal-Imran, An-Nisa, Al-Maidah, Al-Anam, Al-Kahf, Maryam, Ya-Sin, Ar-Rahman, Al-Waqiah, Al-Mulk
- **Juz Amma (An-Naba through An-Nas):** 37 surahs
- **Total: 49 surahs** with 4 facts each (ayahs, place, theme, feature)

## Difficulty Levels

| Level  | Questions | Pool |
|--------|-----------|------|
| Easy   | 10        | 10 well-known surahs |
| Medium | 20        | 20 surahs |
| Hard   | 40        | All 49 surahs |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes (Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand)
- Trilingual UI (EN / FR / AR with RTL support)
- Splash screen with Bismillah
- Sound effects via Web Audio API (toggle on/off)
- Keyboard shortcuts (1-4 for choices, Enter to start, Esc to close help)
- High score persistence (localStorage)
- Theme/language/sound preferences persisted
- Sidebar help panel (FAQ, How-To, Wiki)
- Progress bar and timer
- Back-link to catalog

## Storage Keys

- `wdiy-hs-surah-match` — high score (percentage)
- `wdiy-lang` — language preference
- `wdiy-theme` — theme preference
- `wdiy-mute` — sound mute state

## Version

Workshop-Diy — Surah Match v1.0
