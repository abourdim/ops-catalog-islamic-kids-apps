# Tariq's Landing

Canvas-based strategy game about Tariq ibn Ziyad's historic crossing to Iberia in 711 CE.

## Game Phases

| Phase | Title | Gameplay |
|-------|-------|----------|
| 1 | **Load the Troops** | Map showing Morocco coast and Spain. Click ships to load 7,000 troops, then sail across the strait. |
| 2 | **Landing at Gibraltar** | Click Jabal Tariq (Mountain of Tariq) to land troops. Learn the origin of the name "Gibraltar" from "Jabal Tariq" (جبل طارق). |
| 3 | **Tariq's Famous Speech** | Arrange key phrases of Tariq's legendary speech in correct order: "The enemy is before you, the sea is behind you." |
| 4 | **Battle of Guadalete** | Drag-and-drop troop positioning against Visigoth King Roderic. Watch as Roderic's own allies switch sides. |
| 5 | **Advance Through Iberia** | Canvas map showing cities falling one by one. Within 7 years, most of Iberia under Muslim control. |

## Lesson

Courage, determination, and the beginning of Al-Andalus — a civilization that flourished for nearly 800 years as a beacon of knowledge, art, and tolerance.

## Features

- Single HTML file, zero dependencies, fully offline
- HTML5 Canvas rendering with animated maps, ships, troops, and battles
- 3 difficulty levels (Easy / Medium / Hard)
- 8 themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- 3 languages: English, French, Arabic (with RTL support)
- Web Audio API sound effects (no audio files)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- High score persistence via localStorage
- Theme, language, and sound preferences persisted
- Touch support for mobile devices
- Responsive canvas sizing

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-tariq` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Tech

- Single-file HTML (~600 lines)
- Canvas 2D API for all game rendering
- CSS custom properties for theming
- Google Fonts: IBM Plex Mono, Outfit, Noto Sans Arabic
- No frameworks, no build step, no external JS

## Version

v1.0
