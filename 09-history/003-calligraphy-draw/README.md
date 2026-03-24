# Calligraphy Practice

> Trace beautiful Islamic phrases — a canvas-based calligraphy tool for Muslim kids.

## Overview

An interactive drawing tool where children practice Islamic calligraphy by tracing over guide text rendered as faded Arabic phrases on an HTML5 canvas. Supports mouse and touch input with variable-width lines that respond to drawing speed for a natural calligraphy feel.

## Phrases Included

| # | Arabic | Transliteration | Meaning |
|---|--------|-----------------|---------|
| 1 | بِسْمِ اللَّهِ | Bismillah | In the name of Allah |
| 2 | الْحَمْدُ لِلَّهِ | Alhamdulillah | All praise is due to Allah |
| 3 | اللَّهُ أَكْبَرُ | Allahu Akbar | Allah is the Greatest |
| 4 | سُبْحَانَ اللَّهِ | SubhanAllah | Glory be to Allah |
| 5 | لَا إِلَهَ إِلَّا اللَّهُ | La ilaha illallah | There is no god but Allah |
| 6 | مَا شَاءَ اللَّهُ | MashaAllah | As Allah has willed |
| 7 | إِنْ شَاءَ اللَّهُ | InshaAllah | If Allah wills |
| 8 | الله | Allah | Allah (God) |
| 9 | محمد | Muhammad | Prophet Muhammad (PBUH) |
| 10 | سلام | Salam | Peace |

## Features

- **Guide text** rendered at 0.15 opacity in Noto Sans Arabic (56px)
- **Variable-width drawing** — speed-sensitive line width for calligraphy feel
- **3 brush sizes** — thin (2px), medium (4px), thick (8px)
- **Ink color** follows the current theme accent color
- **Free Draw mode** — blank canvas for freehand practice
- **Touch support** — touchstart/touchmove with passive:false
- **Phrase navigation** — dropdown, prev/next buttons
- **Practice log** — tracks phrases traced with timestamps
- **High score** persistence via localStorage

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `Arrow Right` / `n` | Next phrase |
| `Arrow Left` / `p` | Previous phrase |
| `c` | Clear canvas |
| `f` | Toggle Free Draw |
| `1` / `2` / `3` | Brush: thin / medium / thick |
| `Enter` | Start (from splash) |
| `Escape` | Close help sidebar |

## Tech

- **Single HTML file**, zero dependencies, fully offline
- **8 CSS themes**: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 languages**: EN, FR, AR (with RTL support)
- **Canvas API** with quadratic curves for smooth strokes
- **Web Audio API** for sound feedback
- **localStorage** for persisting theme, language, sound, and high score

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-calligraphy` | High score (phrases traced) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## License

Workshop-Diy — Calligraphy Practice v1.0
