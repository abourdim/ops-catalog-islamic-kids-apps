# Banu Mustaliq — The Raid at Al-Muraysi

Canvas-based quick-strike strategy game for Muslim kids about the Ghazwah of Banu Mustaliq (6 AH).

## Gameplay

Four-phase interactive campaign played on an HTML5 canvas map:

| Phase | Title | Interaction |
|-------|-------|-------------|
| 1 | Intel & Planning | Choose approach route: direct charge, flanking maneuver, or night approach |
| 2 | Rapid Deployment | Position archers, cavalry, and infantry on the tactical map |
| 3 | Surprise Attack | Click enemy fighters on the canvas to advance Muslim forces at the well |
| 4 | Mercy in Victory | Story of Juwayriyah, the tribe's freedom, and final quiz |

Scoring rewards historically sound decisions (night/flanking routes score higher). Difficulty affects enemy count and bonus multiplier.

## Key Lessons

- Swift decisive action prevents greater harm
- Mercy after victory wins hearts
- One marriage of wisdom freed over 100 families
- Compassion and diplomacy are mightier than the sword
- Aisha (RA) called Juwayriyah "the most blessed woman for her people"

## Features

- **Single HTML file** — zero dependencies, fully offline
- **Canvas rendering** — tactical map with terrain, well, camps, routes, armies
- **8 CSS themes** — Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 languages** — EN / FR / AR (with RTL support)
- **Sidebar help** — FAQ, How-To, Wiki tabs
- **Sound** — Web Audio API (no files), toggle on/off
- **High score** — persisted in localStorage (`wdiy-hs-mustaliq`)
- **Keyboard shortcuts** — 1-3 for choices, Enter to start, Escape closes help
- **Responsive** — canvas scales for mobile
- **Preferences persist** — theme, language, sound mute saved to localStorage
- **3 difficulty levels** — Easy, Medium, Hard (affects enemy count and scoring)

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-mustaliq` | High score |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Run

Open `index.html` in any modern browser. No build step, no server needed.
