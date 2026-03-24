# Battlefield Medic

Canvas-based triage game inspired by **Rufaydah al-Aslamiyyah**, the first Muslim nurse who set up field hospital tents during the time of Prophet Muhammad (peace be upon him).

## Gameplay

- 15 wounded soldiers appear on the battlefield after battle
- Players must **triage** by severity: Critical (red) > Moderate (yellow) > Light (green)
- Click a patient to select, apply the correct treatment, then transport to Rufaydah's hospital tent
- **Treatments**: Bandage (bleeding), Splint (fracture), Herbal medicine (infection)
- Patients lose health over time — critical patients deteriorate fastest
- Score = lives saved out of 15

## Difficulty Levels

| Level  | Health Decay | Treatment Bonus |
|--------|-------------|-----------------|
| Easy   | 0.5x        | +60 HP          |
| Medium | 1.0x        | +40 HP          |
| Hard   | 1.6x        | +25 HP          |

## Controls

- **Click** patient on canvas to select
- **1** = Bandage, **2** = Splint, **3** = Herbal, **4/T** = Transport
- **Enter** = Start/New Game
- **Esc** = Close help sidebar

## Features

- Single HTML file, zero dependencies, fully offline
- HTML5 Canvas rendering with real-time game loop
- 8 themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Web Audio API sound effects (no audio files)
- LocalStorage persistence: high score (`wdiy-hs-medic`), theme, language, sound preference
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Touch support for mobile devices
- Responsive canvas sizing

## Tech

- Pure HTML/CSS/JS — no frameworks, no build step
- Canvas API for battlefield rendering
- Web Audio API for procedural sound
- LocalStorage for preferences and high scores

## Reference

Rufaydah bint Sa'ad al-Aslamiyyah was a companion of the Prophet (peace be upon him) from the Banu Aslam tribe. She is recognized as the first female Muslim nurse and surgeon, known for setting up medical tents on the battlefield to care for wounded soldiers.
