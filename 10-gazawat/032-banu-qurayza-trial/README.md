# Banu Qurayza — Justice After Betrayal

Interactive story for Muslim kids about treaties, treason, and justice in wartime.

## Overview

Single-file HTML app (zero dependencies, fully offline) that walks children through the historical event of Banu Qurayza in 6 interactive phases with comprehension questions.

## Phases

1. **The Betrayal** — Treaty of Medina context; Banu Qurayza breaks treaty during Battle of the Trench, opening a second front from inside Medina while families are defenseless
2. **The Siege** — 25-day siege of Banu Qurayza fortresses with interactive canvas map showing Medina layout
3. **The Surrender** — Banu Qurayza choose Sa'd ibn Muadh (their former ally) as arbitrator; both sides agree to accept his ruling
4. **The Judgment** — Sa'd rules based on the Torah's own law for wartime treason (Deuteronomy 20:12-14)
5. **Understanding the Judgment** — Multiple perspectives: treaty law, stakes, their own scripture, due process. Three reflection questions
6. **Lessons Learned** — Treaties are sacred, justice even in war, arbitration system, judged by own standard, context matters

## Key Lessons

- Treaties carry consequences — honoring agreements is a fundamental Islamic principle
- Justice requires due process even in wartime — 25-day siege, chosen arbitrator, agreed terms
- The arbitration model — both sides agree to a judge before hearing the verdict
- Judged by their own standard — Sa'd applied Torah law, not a foreign system
- Context matters — this was a response to treason that endangered thousands of innocents

## Features

- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: EN / FR / AR (RTL auto-enabled)
- Splash screen with bismillah
- Sidebar help panel (FAQ, How-To, Wiki)
- Interactive canvas map of Medina during the siege
- 7 comprehension questions across 6 phases
- Timeline navigation (click dots to revisit phases)
- Keyboard shortcuts: 1-4 answers, Enter start, Arrow keys navigate phases, Escape close help
- High score persistence (localStorage)
- Sound effects via Web Audio API (no files)
- Fully offline, single HTML file, zero dependencies

## Storage

- `wdiy-hs-qurayza` — high score (percentage)
- `wdiy-lang` — language preference
- `wdiy-theme` — theme preference
- `wdiy-mute` — sound mute state

## Footer

Workshop-Diy — Banu Qurayza v1.0
