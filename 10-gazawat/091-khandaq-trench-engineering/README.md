# Khandaq Trench Engineering

Interactive engineering game about digging the trench to defend Medina during the Battle of the Trench (Khandaq, 5 AH / 627 CE).

## Concept

Based on Salman al-Farisi's brilliant suggestion to dig a defensive trench on the unprotected northern side of Medina. Players must calculate trench dimensions, compute soil volumes, and assign the right number of workers to each section before the Confederate armies of 10,000 soldiers arrive.

## Gameplay

The player faces 10 trench sections, each with randomized dimensions:

| Phase | Task | Points |
|-------|------|--------|
| Volume Calculation | Calculate L x W x D for soil removal | 10 |
| Worker Assignment | Divide volume by worker rate to assign workers | 10 |

Total possible score: 200 points across 10 sections.

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Theme/language/sound preferences persisted
- Randomized dimensions each playthrough
- Timer tracking

## Lesson

Engineering and planning are essential to defense. Salman al-Farisi's innovation — bringing Persian military engineering to Arabia — shows how Islam valued knowledge from all cultures and how the companions worked together selflessly to protect their community.

## Technical

- **HS_KEY**: `wdiy-hs-khandaq-trench-engineering`
- **Footer**: Workshop-Diy — Khandaq Trench Engineering v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
