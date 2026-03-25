# Fortification Builder

Interactive grid-based strategy game where kids design defensive fortifications with walls, towers, gates, moats, and archer positions.

## Concept

Islamic military history features impressive fortification engineering — from the trench (khandaq) dug around Medina on Salman al-Farisi's advice (5 AH) to the great ribat fortress cities of North Africa. Players learn about defensive strategy by designing their own fortress.

## Gameplay

1. Start with a budget of 50 gold
2. Select structure types from the palette (wall, tower, gate, moat, archer post)
3. Click grid cells to place structures — each costs gold
4. Walls block attackers, towers provide ranged defense, moats slow enemies
5. Test your defense against a simulated attack
6. Score depends on placement strategy, coverage, and structure synergy

## Structures

| Structure | Cost | Defense | Purpose |
|-----------|------|---------|---------|
| Wall | 2 | 3 | Block attackers |
| Tower | 5 | 8 | Ranged defense |
| Gate | 4 | 2 | Controlled entry |
| Moat | 3 | 5 | Slow enemies |
| Archer Post | 4 | 6 | Active defense |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- 8x8 interactive grid with click-to-place mechanics
- Budget management system
- Defense scoring with edge bonuses
- High score persistence via localStorage

## Lesson

Defensive engineering in Islam: The Battle of the Trench showed that innovative fortification can protect without bloodshed. The Prophet (peace be upon him) valued strategic preparation and consultation (shura) in military planning.

## Technical

- **HS_KEY**: `wdiy-hs-fortification-builder`
- **Footer**: Workshop-Diy — Fortification Builder v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
