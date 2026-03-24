# The Great Cannon — Fath al-Qustantiniyyah

A canvas-based physics/engineering game about the conquest of Constantinople (1453 CE / 857 AH) by Sultan Muhammad al-Fatih.

## Game Phases

| Phase | Description |
|-------|-------------|
| **1 — Build** | Drag cannon components (barrel, wheel base, firing mechanism) into the assembly zone. Adjust barrel length and bore diameter with sliders. |
| **2 — Position** | Choose the optimal distance from Constantinople's walls. Too close = vulnerable to arrows, too far = shots miss. |
| **3 — Fire!** | Adjust angle and powder charge. Physics simulation — cannonball arcs toward the wall. Wall has HP; each hit damages it. Breach the wall in as few shots as possible. |
| **4 — Ships Over Land** | Drag Ottoman ships across the greased log path behind Galata to bypass the chain across the Golden Horn. |
| **5 — Final Assault** | Lead the army through the breach. Sultan Mehmed enters Constantinople, goes to Hagia Sophia, prays, and declares safety for all inhabitants. Hadith displayed. |

## Score

- **Accuracy** = hits / total shots fired (percentage)
- Fewer shots to breach = higher score
- High score persisted to `localStorage`

## Technical Details

- **Single HTML file**, zero external dependencies (offline-ready)
- **Canvas-based** rendering with physics simulation
- **8 themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages**: EN, FR, AR (with RTL support)
- **Sidebar help** panel with FAQ, How-To, and Wiki tabs
- **Web Audio API** sound effects (cannon fire, impacts, victory)
- **Touch + mouse** input support
- **Keyboard**: Enter to start, Space to fire, Escape to close help
- **localStorage keys**:
  - `wdiy-hs-fatih-cannon` — high score
  - `wdiy-lang` — language preference
  - `wdiy-theme` — theme preference
  - `wdiy-mute` — sound preference

## HS_KEY

```
wdiy-hs-fatih-cannon
```

## Run

Open `index.html` in any modern browser. No server required.
