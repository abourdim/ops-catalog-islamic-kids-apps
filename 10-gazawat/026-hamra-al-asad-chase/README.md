# Hamra al-Asad — Rise the Day After Defeat

A single-file, canvas-based HTML strategy game for Muslim kids about the expedition to Hamra al-Asad (3 AH).

## Overview

The day after the Battle of Uhud, the Prophet (peace be upon him) ordered a bold march to Hamra al-Asad. Only those who had fought the previous day were allowed to join. Despite their wounds, the Muslims marched 13 km and lit large campfires at night, creating the illusion of a massive army. Abu Sufyan's scouts saw the fires, panicked, and the Quraysh retreated without a fight — a masterclass in psychological warfare.

## Gameplay (5 Phases)

1. **Rally** — Click wounded soldiers to rally them for the march (only Uhud veterans allowed)
2. **March** — Click/tap repeatedly to advance 13 km to Hamra al-Asad despite injuries
3. **Campfires** — Place 10 campfires across the night desert to simulate a massive army
4. **Scouts** — Watch Abu Sufyan's scouts approach, see the fires, and panic
5. **Victory** — Quraysh retreats without fighting. Quran verse (3:172-174) displayed

## Lessons

- Show of strength even when weak
- Psychological warfare as a legitimate strategy
- Courage and obedience after defeat
- Unity of the believers

## Quran Reference

> "Those who responded to Allah and the Messenger after injury had struck them. For those who did good among them and feared Allah is a great reward."
> — Surah Aal-Imran, 3:172-174

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based interactive gameplay with animations
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- Trilingual: English, French, Arabic (RTL support)
- Web Audio API sound effects (no external files)
- Best-time high score saved to localStorage
- Keyboard shortcuts: Enter (start), Space (march), Escape (close help)
- Touch support for mobile devices
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Persistent preferences (theme, language, sound, high score)

## Keys

| Key | Action |
|-----|--------|
| `Enter` | Start Mission / New Game |
| `Space` | March forward (Phase 2) |
| `Escape` | Close help panel |

## Storage Keys

- `wdiy-hs-hamra-asad` — Best completion time (seconds)
- `wdiy-theme` — Selected theme
- `wdiy-lang` — Selected language
- `wdiy-mute` — Sound mute state

## Tech

| Spec | Value |
|------|-------|
| File | `index.html` (single file) |
| Dependencies | None (Google Fonts optional) |
| Canvas | 560 x 380 |
| Audio | Web Audio API |
| Storage | localStorage |
| Offline | Yes |

---

Workshop-Diy — Hamra al-Asad v1.0
