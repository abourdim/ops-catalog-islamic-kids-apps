# Spy Network

Canvas-based intelligence gathering game for Muslim kids.

## Concept

Send scouts to gather intel on enemy positions, then report findings to the commander through a quiz. Based on the Sunnah of the Prophet ﷺ who sent scouts before every major battle.

## Gameplay

**5 missions per campaign. 3 phases per mission:**

1. **Scout Phase** — Drag scouts from your camp (green zone) onto the map. Place them in enemy territory (red, high risk / high reward) or neutral zone (yellow, lower risk). Click "Send" when ready.
2. **Intel Phase** — Review the intelligence report. Some scouts may have been captured. Surviving scouts report: troop count, movement direction, supply level, morale. Confidence depends on number and placement of scouts.
3. **Quiz Phase** — Answer questions about the gathered intel to report to the commander. Questions test observation: "How many enemy troops?", "Which direction are they moving?", "What is their supply level?", "What is their morale level?"

## Difficulty

| Setting | Scouts | Base Detection |
|---------|--------|----------------|
| Easy    | 6      | 10%            |
| Medium  | 5      | 20%            |
| Hard    | 4      | 30%            |

Detection risk increases with zone danger (enemy > neutral > friendly) and total scouts deployed.

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based map with drag-and-drop scout placement (mouse + touch)
- 8 themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Web Audio API sound effects (no files)
- High score persistence via localStorage (`wdiy-hs-spy-network`)
- Sidebar help panel with FAQ, How-To, Wiki tabs
- Keyboard shortcuts: 1-4 for quiz answers, Enter to start, Escape to close help

## Islamic Reference

The Prophet ﷺ consistently sent scouts and reconnaissance parties before military engagements. Intelligence gathering was a fundamental part of early Islamic military strategy, teaching children the value of preparation, observation, and careful planning.

## Tech

- Single `index.html` file
- HTML5 Canvas for map rendering
- CSS custom properties for theming
- localStorage for preferences and high scores
- No external dependencies beyond Google Fonts
