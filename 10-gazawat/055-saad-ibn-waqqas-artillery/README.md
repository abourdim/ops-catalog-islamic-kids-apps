# Qadisiyyah Artillery

Canvas-based artillery game set at the Battle of Qadisiyyah (636 CE). Sa'd ibn Abi Waqqas commands Muslim forces from a building while ill — the player positions catapults and archers to overcome the Persian war elephants.

## Gameplay

- **Catapult mode**: Launch boulders that damage elephant bodies directly (reduce HP)
- **Archer mode**: Fire arrow volleys targeting the mahouts (elephant drivers) — historically the key tactic that turned the battle. When the driver is hit, the elephant flees uncontrollably
- **5 waves** of elephants approach the Muslim infantry line
- Protect infantry from elephant charges
- **Score** = elephants neutralized x10 + infantry saved x5

## Historical Reference

At Qadisiyyah, the Persian army deployed war elephants that initially terrified the Muslim cavalry. Sa'd ibn Abi Waqqas, one of the ten companions promised Paradise, was ill and commanded from a building overlooking the battlefield. The Muslims discovered that targeting the mahouts (drivers) rather than the elephants themselves was the decisive tactic — without drivers, elephants became uncontrollable and fled.

## Controls

| Input | Action |
|-------|--------|
| 1 / 2 | Switch Catapult / Archer mode |
| Arrow Up/Down | Adjust launch angle |
| Arrow Left/Right | Adjust power |
| Space / Enter | Fire |
| Sliders | Angle and power fine-tuning |

## Features

- Single HTML file, zero dependencies, fully offline
- HTML5 Canvas rendering with theme-aware colors
- 8 themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: EN, FR, AR (with RTL support)
- 3 difficulty levels (Easy / Medium / Hard)
- Web Audio API sound effects (no audio files)
- Persistent preferences (theme, language, sound, high score)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Keyboard and touch/mouse controls

## Storage

| Key | Purpose |
|-----|---------|
| `wdiy-hs-saad-artillery` | High score |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Tech

- Single-file HTML (~400 lines)
- Canvas 2D API for all game rendering
- CSS custom properties for theming
- Web Audio API oscillators for sound
- localStorage for persistence
- No frameworks, no build step, no network calls
