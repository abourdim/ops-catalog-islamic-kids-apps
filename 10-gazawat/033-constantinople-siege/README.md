# Fall of Constantinople

> The conquest foretold by the Prophet ﷺ

A single-file HTML5 canvas strategy game for Muslim kids about Sultan Mehmed II's historic conquest of Constantinople in 1453 CE.

## Game Phases

| Phase | Title | Interaction |
|-------|-------|-------------|
| 1 | **Position the Orban Cannon** | Drag the giant cannon to optimal range of the triple walls. Wall-breaking power is calculated based on distance. |
| 2 | **Ships Over Land** | The Golden Horn chain blocks the harbor. Drag ships along the overland route behind Galata hill on greased logs — a historical innovation! |
| 3 | **Deploy Forces** | Position land and sea forces for a simultaneous attack from both sides. |
| 4 | **Final Assault** | Fire cannons at the triple walls. After 10 hits the walls are breached — the city falls after 53 days. |
| 5 | **Victory & Mercy** | Mehmed enters, prays at Hagia Sophia, declares safety for people and property. The hadith is displayed. |

## The Hadith

> «لَتُفْتَحَنَّ الْقُسْطَنْطِينِيَّةُ فَلَنِعْمَ الْأَمِيرُ أَمِيرُهَا وَلَنِعْمَ الْجَيْشُ ذَلِكَ الْجَيْشُ»
>
> "You will conquer Constantinople. What a wonderful commander and army that will be." — Prophet Muhammad ﷺ

## Lessons

- **Fulfilling Prophecy** — Mehmed II fulfilled a prophecy made ~800 years earlier
- **Innovation** — Moving 70+ ships overland on greased logs to bypass the chain
- **Mercy in Conquest** — Safety guaranteed for people and property upon entry

## Features

- Single HTML file, zero dependencies, fully offline
- HTML5 Canvas rendering with drag-and-drop interaction
- Touch support for mobile devices
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- Trilingual UI: English, French, Arabic (with RTL support)
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Keyboard shortcuts (Enter, Space, 1, 2, Escape)
- Sidebar help panel with FAQ, How-To, and Wiki tabs

## Controls

| Key | Action |
|-----|--------|
| Enter | Start game |
| Space | Fire cannon (Phase 1 & 4) |
| 1 | Deploy land army (Phase 3) |
| 2 | Deploy navy (Phase 3) |
| Escape | Close help panel |
| Mouse/Touch drag | Position cannon (Phase 1), move ships (Phase 2) |

## Storage Keys

- `wdiy-hs-constantinople` — High score
- `wdiy-lang` — Language preference
- `wdiy-theme` — Theme preference
- `wdiy-mute` — Sound preference

## Tech

- Single HTML file (~15KB)
- No frameworks, no build step, no external assets
- Works in any modern browser

---

Workshop-Diy — Fall of Constantinople v1.0
