# Battle of Hunayn — When Numbers Aren't Enough

A canvas-based action/strategy game for Muslim kids, teaching the lessons of the Battle of Hunayn (8 AH / 630 CE).

## Game Overview

The player experiences the four phases of the Battle of Hunayn:

1. **Phase 1 — Confidence**: Watch the 12,000-strong Muslim army march into the narrow valley. Some soldiers boast about their numbers.
2. **Phase 2 — Ambush**: The Hawazin tribe attacks from the hills with arrows. The army scatters in chaos. The Prophet (peace be upon him) stands firm with ~100 companions. Abbas (RA) calls out to the Ansar. **Tap scattered soldier groups** to rally them back to the Prophet.
3. **Phase 3 — Counterattack**: Direct the regrouped Muslim units to defeat the enemy positions on the hills. **Tap enemy positions** to send your units.
4. **Phase 4 — Victory**: Review your score and the two key lessons of Hunayn.

## Lessons

1. Numbers alone do not guarantee victory — only Allah grants success.
2. Standing firm with faith, even when others flee, is the mark of true believers.

**Quran Reference**: Surah At-Tawbah 9:25

## Features

- Single-file HTML, zero dependencies, fully offline
- Canvas-based rendering with animated soldiers, arrows, terrain
- 4-phase gameplay: march, ambush, rally, counterattack
- 3 difficulty levels (Easy, Medium, Hard) — more scattered groups and enemies on harder settings
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- 3 languages: English, French, Arabic (with RTL support)
- Web Audio API sound effects (no audio files needed)
- High score persistence via localStorage
- Theme, language, and sound preferences persist across sessions
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Keyboard shortcuts: Enter (start), Space (auto-direct in Phase 3), H (help), Escape (close help)
- Touch support for mobile devices
- Responsive canvas scaling

## Storage Keys

- `wdiy-hs-hunayn-trap` — High score (percentage)
- `wdiy-lang` — Language preference
- `wdiy-theme` — Theme preference
- `wdiy-mute` — Sound mute state

## Usage

Open `index.html` in any modern browser. No server required.

---

Workshop-Diy — Battle of Hunayn v1.0
