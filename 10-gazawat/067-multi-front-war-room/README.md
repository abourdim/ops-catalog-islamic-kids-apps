# Multi-Front War Room — Strategic Command

Turn-based strategy game where players allocate armies to multiple fronts simultaneously, balancing resources and reinforcements.

## Concept

Command a multi-front campaign. Allocate limited troops from your central reserve to 4 fronts (North, South, East, West). Each turn, enemy threats escalate randomly. Inspired by Abu Bakr al-Siddiq's management of simultaneous campaigns during the Ridda wars.

## Gameplay

- 4 fronts with independent enemy threat levels
- Central reserve pool of troops to distribute
- Each turn: allocate troops, then resolve combat on all fronts
- Fronts where your troops >= enemy strength hold; otherwise they collapse
- Lose any front and the campaign fails
- Reinforcements arrive each turn (5-10 + bonus per held front)
- Enemy threat escalates each turn with randomness
- Survive 10 turns to win

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- DOM-based interactive card UI for each front

## Lesson

Abu Bakr al-Siddiq simultaneously managed campaigns across Arabia, Iraq, and Syria. This required strategic vision, careful resource allocation, and trust in capable commanders like Khalid ibn al-Walid.

## Technical

- **HS_KEY**: `wdiy-hs-multi-front-war-room`
- **Footer**: Workshop-Diy — Multi-Front War Room v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
