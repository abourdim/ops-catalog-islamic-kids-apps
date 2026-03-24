# March to Dumat al-Jandal

> 800km through the desert

Canvas-based expedition management game for Muslim kids. Lead 1000 soldiers from Medina to Dumat al-Jandal (modern Sakaka), 800km north through the Arabian desert.

## Gameplay

- **15-day expedition** across the northern desert toward the Byzantine border
- **Resource management**: water supplies, morale, stamina
- **March pace**: Fast (more distance, drains resources), Normal (balanced), Cautious (slow but safe)
- **Send scouts**: reveal oases, spot hostile tribes, find shortcuts
- **Random events**: oasis found, sandstorm, hostile tribe, messenger from Medina, friendly caravan, scorching heat, illness, clear stars navigation
- **Win condition**: reach 800km before the tribal coalition assembles
- **Outcome**: tribes scatter when they see the Muslim army — victory through deterrence

## Historical Context

The expedition to Dumat al-Jandal (5 AH / 626 CE) was led by Prophet Muhammad (peace be upon him) with 1000 soldiers. It demonstrated that Muslim reach extended all the way to the Byzantine border. The hostile tribal coalition scattered without fighting — a strategic victory achieved without bloodshed.

### Key Lesson

Projection of power, long-range expeditions, and deterrence without bloodshed. Preparation and logistics made a 800km desert march possible.

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas map with day-by-day progress marker and waypoints
- Resource bars (water, morale, stamina) with visual feedback
- Event popup system with player choices
- 3 difficulty levels (Easy / Normal / Hard)
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Web Audio API sound effects (no files needed)
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Keyboard shortcuts: 1-4 for actions, Enter to confirm, Escape to close help
- High score persistence via localStorage
- Theme, language, and sound preferences persisted

## Controls

| Key | Action |
|-----|--------|
| `1` | Fast March |
| `2` | Normal Pace |
| `3` | Cautious |
| `4` | Send Scouts |
| `Enter` | Start / Confirm popup |
| `Escape` | Close help sidebar |

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-dumat` | High score |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Footer

Workshop-Diy — March to Dumat al-Jandal v1.0
