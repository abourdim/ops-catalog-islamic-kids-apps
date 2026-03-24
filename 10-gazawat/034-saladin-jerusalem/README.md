# Saladin's Victory — Mercy Conquers Jerusalem

> **Workshop-Diy** — Islamic Kids Apps Catalog
> Category: 10-gazawat (Battles & Campaigns)

## Overview

A canvas-based interactive strategy game teaching Muslim kids about Sultan Salahuddin Al-Ayyubi's liberation of Jerusalem in 1187 CE. Covers the Battle of Hattin, Saladin's legendary mercy, and the restoration of Al-Masjid Al-Aqsa.

## Gameplay — 6 Phases

| Phase | Title | Mechanic |
|-------|-------|----------|
| 1 | **Unite the Armies** | Drag army units from Egypt, Syria, and Mesopotamia to the rally point |
| 2 | **Cut Off the Water** | Position troop divisions to block Crusaders from the Sea of Galilee |
| 3 | **Battle of Hattin** | Watch the battle unfold; witness Saladin giving water to captured King Guy |
| 4 | **March to Jerusalem** | Advance Saladin's army to Jerusalem; city surrenders through negotiation |
| 5 | **Mercy vs Vengeance** | Split-screen contrast: 1099 Crusader massacre vs 1187 Saladin's mercy |
| 6 | **Al-Aqsa Restored** | Mosque cleaned with rose water; first Jumu'ah prayer in 88 years |

## Key Lessons

- **Mercy over vengeance** — Saladin freed captives and paid ransom for the poor
- **Chivalry** — Gave iced water to the defeated King Guy
- **Justice** — Protected churches, synagogues, and all civilians
- **Unity** — Success required uniting divided Muslim lands
- **Protecting holy sites** — Al-Aqsa restored and purified

## Technical Details

- **Single HTML file**, zero external dependencies (offline-ready)
- **Canvas-based** rendering with drag-and-drop interaction
- **8 CSS themes**: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 languages**: English, French, Arabic (with RTL support)
- **Web Audio API** sound effects (no audio files)
- **LocalStorage** persistence for theme, language, sound, and high score
- **Touch + mouse** support for mobile and desktop
- **Keyboard shortcuts**: Enter/Space to advance, 1-9 for action buttons, Escape to close help

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-saladin` | High score |
| `wdiy-theme` | Selected theme |
| `wdiy-lang` | Selected language |
| `wdiy-mute` | Sound mute state |

## Structure

```
034-saladin-jerusalem/
  index.html    ← Single-file app (HTML + CSS + JS)
  README.md     ← This file
```

## Version

**v1.0** — Workshop-Diy — Saladin's Victory
