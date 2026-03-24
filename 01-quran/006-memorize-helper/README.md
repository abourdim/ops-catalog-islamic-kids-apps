# Memorize Helper

**Memorize the Quran step by step**

A single-file HTML interactive Quran memorization aid for Muslim kids using a progressive hiding technique. Zero dependencies, fully offline.

## How It Works

1. **Select a surah** from the grid (12 short surahs available)
2. **Step 1** — Read the full surah text in large, clear Arabic
3. **Step 2** — 25% of words are hidden; fill them in by selecting from the word bank
4. **Step 3** — 50% of words hidden
5. **Step 4** — 75% of words hidden
6. **Step 5** — All words hidden; reconstruct the entire surah from memory

## Surahs Included

Al-Fatiha, Al-Ikhlas, Al-Falaq, An-Nas, Al-Kawthar, Al-Asr, Al-Fil, Quraysh, Al-Maun, An-Nasr, Al-Masad, Al-Kafirun

## Difficulty Levels

| Level  | Steps     | Description                        |
|--------|-----------|------------------------------------|
| Easy   | 1-2       | Read + fill 25% blanks             |
| Medium | 1-4       | Up to 75% hidden                   |
| Hard   | 1-5       | Full reconstruction from memory    |

## Progress Tracking

- 0-5 stars per surah (one per completed step)
- Checkmark for fully memorized surahs (all 5 steps)
- Progress persisted in localStorage

## Features

- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: EN / FR / AR (RTL auto-switch)
- Splash screen with Bismillah
- Sidebar help panel (FAQ, How-To, Wiki)
- Web Audio API sound effects (toggle on/off)
- Keyboard shortcuts (1-9 word bank, Tab cycle blanks, Enter advance, Esc close help)
- All preferences persisted (theme, language, sound, progress)
- Single HTML file, zero dependencies, fully offline
- Back-link to catalog

## Storage Keys

- `wdiy-hs-memorize` — High score (number of surahs memorized)
- `wdiy-memorize-progress` — Per-surah step progress
- `wdiy-lang` / `wdiy-theme` / `wdiy-mute` — Shared preferences

## Footer

Workshop-Diy — Memorize Helper v1.0
