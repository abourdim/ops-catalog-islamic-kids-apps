# Hajj Journey

**Walk through the pilgrimage step by step**

An interactive step-by-step Hajj learning game for Muslim kids. Cards showing the steps of Hajj are displayed in random order — the player must tap them in the correct sequence to complete the pilgrimage.

## Features

- **14 Steps of Hajj** — from Ihram to Return Home, each with emoji, Arabic term, English description, and significance
- **3 Difficulty Levels** — Easy (7 main steps), Medium (10 steps), Hard (all 14 steps)
- **Canvas Mini-Map** — visual journey tracker showing movement between Mecca, Mina, Arafah, and Muzdalifah
- **Step Info Cards** — after each correct tap, displays the step's description and Islamic significance
- **8 CSS Themes** — Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **Trilingual** — English, French, Arabic (with RTL support)
- **Sound Effects** — Web Audio API (correct, wrong, win sounds; toggle on/off)
- **High Score** — persisted in localStorage (`wdiy-hs-hajj-journey`)
- **Keyboard Shortcuts** — Enter to start, 1-9 to pick cards, Escape to close help
- **Sidebar Help** — FAQ, How-To, and Wiki tabs
- **Single HTML file** — zero dependencies, fully offline

## How to Play

1. Click **Start Mission** on the splash screen
2. Choose difficulty (Easy / Medium / Hard)
3. Press **▶ New Game**
4. Tap the step cards in the correct order of Hajj
5. Watch the mini-map track your journey across the holy sites
6. Read the significance of each step after a correct tap
7. Complete all steps to finish the pilgrimage

## Steps of Hajj

| # | Step | Arabic | Location |
|---|------|--------|----------|
| 1 | Ihram | إحرام | Mecca |
| 2 | Tawaf Al-Qudum | طواف القدوم | Mecca |
| 3 | Sa'i | سعي | Mecca |
| 4 | Day of Tarwiyah | يوم التروية | Mina |
| 5 | Day of Arafah | يوم عرفة | Arafah |
| 6 | Muzdalifah | مزدلفة | Muzdalifah |
| 7 | Rami Al-Jamarat | رمي الجمرات | Mina |
| 8 | Sacrifice (Qurbani) | الأضحية | Mina |
| 9 | Halq / Taqsir | حلق / تقصير | Mina |
| 10 | Tawaf Al-Ifadah | طواف الإفاضة | Mecca |
| 11 | Sa'i (again) | سعي مرة أخرى | Mecca |
| 12 | Days of Tashreeq | أيام التشريق | Mina |
| 13 | Tawaf Al-Wada | طواف الوداع | Mecca |
| 14 | Return Home | العودة | Mecca |

## Tech

- Single HTML file, zero external dependencies (except Google Fonts)
- Works fully offline after first load
- All state stored in `localStorage`
- Web Audio API for sound (no audio files)
- Canvas API for mini-map rendering

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-hajj-journey` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

---

Workshop-Diy — Hajj Journey v1.0
