# Fear Prayer — Salat al-Khawf Learning Game

**How Muslims pray during battle**

## Overview

An interactive single-file HTML game that teaches Muslim kids about Salat al-Khawf (the Fear Prayer) — the special congregational prayer performed when there is danger nearby. Set in the context of the Dhat al-Riqa expedition, this app uses canvas animation and a quiz to explain how the Prophet (peace be upon him) organized prayer so that neither group missed their Salah and the enemy never found an opening.

## Features

- **Canvas Animation**: Step-by-step animated tutorial showing how the army splits, swaps, prays, and guards
- **Quiz Mode**: 12 questions testing comprehension of the Fear Prayer procedure
- **Speed Control**: Watch the animation at 0.5x, 1x, or 2x speed
- **Replay**: Replay the animation at any time
- **High Score**: Persisted quiz high score via localStorage
- **8 CSS Themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 Languages**: EN / FR / AR (Arabic enables RTL)
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Keyboard Shortcuts**: 1-4 for quiz answers, Enter to start, R to replay, A/Q to switch modes, Escape to close help
- **Sound Effects**: Web Audio API tones (no external files)
- **Offline**: Single HTML file, zero dependencies

## Animation Steps

1. Army is together, prayer time comes
2. Army splits into Group A and Group B
3. Group A prays 1 rakah with the Imam; Group B guards
4. Group A finishes, goes to guard; Group B comes to pray
5. Group B prays 1 rakah with the Imam
6. Imam does salam; Group B completes their 2nd rakah alone
7. Both groups have prayed 2 rakahs — enemy never had an opening

## Lesson

Prayer never stops, even in the middle of danger. Allah revealed a brilliant method (Surah An-Nisa 4:102) so that the Muslims could fulfill their obligation to pray while staying safe. This teaches trust in Allah and the importance of Salah above all else.

## Storage Keys

| Key | Purpose |
|---|---|
| `wdiy-hs-fear-prayer` | Quiz high score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Usage

Open `index.html` in any modern browser. No server, no build step, no internet required.

## Footer

Workshop-Diy — Fear Prayer v1.0
