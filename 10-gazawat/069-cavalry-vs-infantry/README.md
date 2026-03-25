# Cavalry vs Infantry — Tactical Battle Simulator

Interactive battle simulator comparing cavalry and infantry strengths across different formations and terrains.

## Concept

Choose your army composition, formation, and terrain, then simulate battles against random enemy armies. Learn which tactical combinations work best in different situations, inspired by the cavalry mastery of Khalid ibn al-Walid and the disciplined infantry of early Muslim armies.

## Gameplay

- Choose army: Cavalry-Heavy (high ATK), Balanced, or Infantry-Heavy (high DEF)
- Pick formation: Wedge (+25% ATK), Shield Wall (+30% DEF), or Crescent (+20% both)
- Select terrain: Plains (cavalry +30%), Hills (infantry +25%), Forest (infantry +35%)
- Battle simulates 10 rounds with calculated damage per round
- Enemy army, formation are randomized each battle
- Win by having more HP remaining after all rounds
- Track win record across multiple battles

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Round-by-round battle log with HP tracking

## Lesson

Understanding the strengths and weaknesses of different military units was essential to early Islamic commanders. Khalid ibn al-Walid's genius lay in choosing the right tactics for each situation — using cavalry on open plains and adapting formations to terrain.

## Technical

- **HS_KEY**: `wdiy-hs-cavalry-vs-infantry`
- **Footer**: Workshop-Diy — Cavalry vs Infantry v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
