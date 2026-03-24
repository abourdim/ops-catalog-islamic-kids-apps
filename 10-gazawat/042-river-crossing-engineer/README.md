# River Crossing — Workshop-Diy

Canvas-based engineering puzzle for Muslim kids. Part of the Gazawat (battles) series.

## Concept

The river blocks the Muslim army's advance. The player must engineer a crossing under time pressure while enemy forces wait on the opposite bank.

### Tools
- **Ford** — Mark shallow areas (lighter blue patches) for troops to wade across
- **Pontoon** — Place log/boat bridge segments across the river
- **Archer** — Station bowmen on the friendly bank to protect crossing troops

### 3 Historical Rivers
1. **Euphrates at Qadisiyyah** (636 CE) — Medium width, moderate current
2. **Nile — Crossing into Egypt** (639 CE) — Wide, deep, strong current
3. **Mountain Stream to Andalus** (711 CE) — Narrow, shallow, weaker current

### Scoring
- Percentage of troops crossed safely per river
- Time bonus (faster = more points)
- Cumulative across all 3 rivers

## Tech

| Detail | Value |
|---|---|
| File | Single `index.html` |
| Dependencies | Zero (fonts via Google Fonts CDN) |
| Offline | Yes, after first load |
| Rendering | HTML5 Canvas |
| Audio | Web Audio API (no files) |
| Storage | `localStorage` key `wdiy-hs-river-cross` |
| Themes | 8 (terminal, midnight, ember, arctic, phosphor, signal, redshift, sand) |
| Languages | EN / FR / AR (RTL) |

## Controls

| Key | Action |
|---|---|
| `1` | Select Ford tool |
| `2` | Select Pontoon tool |
| `3` | Select Archer tool |
| `Enter` | Start / New Game |
| `Esc` | Close help sidebar |
| Click/Tap | Place selected item on canvas |

## Structure

Follows the standard Workshop-Diy app template: splash screen with bismillah, 8-theme switcher, trilingual support, sidebar help (FAQ / How-To / Wiki), activity log, high score persistence, keyboard shortcuts, Web Audio sound effects, and responsive canvas.
