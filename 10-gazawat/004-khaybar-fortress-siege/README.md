# Siege of Khaybar

**Conquer the Seven Fortresses**

A canvas-based strategy game for Muslim kids, teaching the story of the Siege of Khaybar (7 AH / 628 CE).

## Gameplay

- **Map view**: 7 fortresses drawn as walled squares on a canvas, connected by paths
- **Strategy**: Choose the order to approach each fortress — outer first to cut supply lines
- **Actions**: For each fortress, pick one of three approaches:
  - **Assault** — fast but costs more troops
  - **Siege** — slower, uses more supplies, but fewer troop losses
  - **Negotiate** — no troop losses if accepted (better chances after conquering more forts)
- **Resources**: 1,400 troops and limited supplies that decrease each day
- **Ali's moment**: Special animated scene at Al-Qamus fortress where Ali carries the gate
- **Victory**: Peace treaty shown — people keep their land, pay tax (justice in victory)

## Fortresses

| # | Name | Tier | Best Approach |
|---|------|------|--------------|
| 1 | Na'im | Outer | Assault |
| 2 | As-Sa'b | Outer | Siege |
| 3 | Az-Zubair | Outer | Siege |
| 4 | Ubayy | Outer | Assault |
| 5 | An-Nizar | Middle | Siege |
| 6 | Al-Qamus | Inner | Assault (Ali!) |
| 7 | Al-Watih & As-Sulalim | Final | Negotiate |

## Lessons

- **Persistence**: Conquering seven fortresses requires patience and planning
- **Bravery**: Ali ibn Abi Talib's legendary strength and courage
- **Justice in victory**: The peace treaty allowed people to keep their land

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based map with interactive fortress selection
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- 3 languages: English, French, Arabic (RTL)
- 3 difficulty levels: Easy, Normal, Hard
- Web Audio API sound effects (no external files)
- High score persistence via localStorage
- Keyboard shortcuts (1-3 for actions, Enter to start, Escape for help)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Touch support for mobile devices

## Technical

- **HS_KEY**: `wdiy-hs-khaybar-siege`
- **Persisted prefs**: theme, language, sound (via localStorage)
- **Footer**: Workshop-Diy — Siege of Khaybar v1.0

## Usage

Open `index.html` in any modern browser. No server required.
