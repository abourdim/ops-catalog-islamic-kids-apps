# Siege Engine Workshop

Interactive siege engine building game where kids assemble catapults, trebuchets, and battering rams used in historic Islamic military campaigns.

## Concept

Muslim armies used various siege engines (manjaniq) in battles such as the Siege of Ta'if (8 AH / 630 CE). Players learn about these machines by assembling their components and testing them against fortress walls.

## Gameplay

1. Choose a siege engine type: Catapult, Trebuchet, or Battering Ram
2. Drag parts from the parts tray into the correct build slots
3. Each engine has unique components that must be placed correctly
4. Once assembled, test the engine against a fortress wall
5. Power score depends on engine type, accuracy, and speed

## Siege Engines

| Engine | Parts | Base Power | Historical Use |
|--------|-------|------------|----------------|
| Catapult (Manjaniq) | 5 parts | 70 | Siege of Ta'if |
| Trebuchet | 6 parts | 90 | Various campaigns |
| Battering Ram (Dabbabah) | 5 parts | 60 | Gate breaching |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- Drag-and-drop assembly with touch support
- Canvas animation for engine testing
- High score persistence via localStorage
- Theme/language/sound preferences persisted

## Lesson

Engineering in Islamic history: Muslim armies innovated in siege warfare, adapting and improving upon existing technologies. The Prophet (peace be upon him) embraced practical military engineering when necessary for defense.

## Technical

- **HS_KEY**: `wdiy-hs-siege-engine-workshop`
- **Footer**: Workshop-Diy — Siege Engine Workshop v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
