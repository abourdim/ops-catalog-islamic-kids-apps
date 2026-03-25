# Desert Navigation — Guide Your Army Home

Interactive canvas navigation game where players guide an army across the desert using stars, landmarks, and compass while managing water and morale.

## Concept

Navigate your army across a procedurally generated desert grid. Use the compass to find direction, discover oases for water, avoid sandstorms, and spot landmarks for orientation. Inspired by Khalid ibn al-Walid's legendary desert crossing from Iraq to Syria.

## Gameplay

- 16x16 grid-based desert map with fog of war
- Compass arrow points toward destination
- Stars and Polaris indicator for nighttime navigation
- Manage water (depletes each move, refills at oases)
- Manage morale (drops from travel, storms, and thirst)
- Find oases (water +40, morale +15)
- Avoid moving sandstorms (morale -25, water -10)
- Discover rock landmarks for bonus points and navigation
- Rest option: recovers morale but costs a day
- Arrow keys + spacebar for keyboard controls
- Score based on speed, remaining water, and morale

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Procedural map generation with fog of war
- Moving sandstorms that shift each turn

## Lesson

Desert navigation was a critical military skill. Khalid ibn al-Walid's 5-day crossing of the Syrian desert was considered impossible by his enemies. Knowledge of stars, terrain, and water sources was as important as military prowess.

## Technical

- **HS_KEY**: `wdiy-hs-desert-navigation`
- **Footer**: Workshop-Diy — Desert Navigation v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
