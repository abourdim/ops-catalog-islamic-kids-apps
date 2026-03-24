# Books & Prophets

**Match divine books and prophet miracles** — an interactive quiz for Muslim kids.

## Overview

An offline, single-file HTML game that teaches children about the prophets of Allah, the divine books revealed to them, their miracles, and key lessons from their stories.

## Game Mechanics

Two quiz types are mixed randomly:

1. **Book → Prophet**: A divine book is shown; the child picks which prophet received it.
2. **Prophet → Attribute/Miracle**: A prophet is shown; the child picks the correct attribute, miracle, or associated event from 4 options.

After each correct answer, an info card displays the prophet's Arabic name, miracle/book detail, and a key lesson.

## Divine Books

| Book | Prophet | Arabic |
|------|---------|--------|
| Quran | Muhammad ﷺ | القرآن |
| Injil (Gospel) | Isa | الإنجيل |
| Tawrat (Torah) | Musa | التوراة |
| Zabur (Psalms) | Dawud | الزبور |
| Suhuf (Scrolls) | Ibrahim | الصحف |

## 25 Prophets Included

Adam, Idris, Nuh, Hud, Salih, Ibrahim, Lut, Ismail, Ishaq, Yaqub, Yusuf, Shuayb, Ayyub, Dhul-Kifl, Musa, Harun, Dawud, Sulaiman, Ilyas, Al-Yasa, Yunus, Zakariyya, Yahya, Isa, Muhammad ﷺ.

## Difficulty Levels

| Level | Prophets | Questions |
|-------|----------|-----------|
| Easy | 5 major (Tier 1) | 10 |
| Medium | 15 (Tier 1+2) | 15 |
| Hard | All 25 (Tier 1+2+3) | 20 |

## Features

- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual UI**: English, French, Arabic (with RTL support)
- **Splash screen** with Bismillah
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Keyboard shortcuts**: 1-4 for answers, Enter to start, Escape to close help
- **High score** persistence via localStorage (`wdiy-hs-books-prophets`)
- **Sound effects** via Web Audio API (no external files)
- **Timer** tracking per game session
- **Info cards** after each answer showing Arabic name, miracle, and lesson
- **Progress bar** and score tracking
- **Back-link** to catalog

## Technical

- Single HTML file, zero dependencies, fully offline
- All preferences (theme, language, sound, high score) persisted in localStorage
- No external API calls, no tracking, no analytics

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-books-prophets` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

---

Workshop-Diy — Books & Prophets v1.0
