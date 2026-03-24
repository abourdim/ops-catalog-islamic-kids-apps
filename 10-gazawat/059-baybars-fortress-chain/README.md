# Fortress Chain — Baybars Defense Network

> بِسْمِ ٱللَّٰهِ ٱلرَّحْمَـٰنِ ٱلرَّحِيمِ

A canvas-based strategy/builder game where kids build Sultan Baybars' legendary fortress network from Egypt to Syria.

## Concept

Players must create an unbreakable defense chain against both Crusaders (from the west) and Mongols (from the east). Budget is limited — you cannot fortify everything, so strategic choices matter.

Based on the historical fortress and communication network built by Sultan Al-Zahir Baybars (1223–1277) that kept Egypt and Syria safe for centuries.

## Gameplay

1. **Build Fortresses** — Click on city locations to place forts (10 locations, can only build 6–8 depending on difficulty)
2. **Connect Roads** — Draw supply lines between forts so reinforcements can move
3. **Pigeon Post** — Create a carrier pigeon communication network between forts
4. **Station Garrisons** — Assign troops to defend each fortress
5. **Upgrade Walls** — Strengthen fortifications for better defense

Press **Evaluate** when ready to test your chain against simulated attacks.

## Scoring

| Component | Weight | Description |
|-----------|--------|-------------|
| Chain Completeness | 40% | Are all forts connected by roads? |
| Territory Coverage | 30% | Do forts cover all 4 regions (Egypt, Palestine, Jordan, Syria)? |
| Communication Speed | 30% | Pigeon post coverage across the network |
| Bonuses | +5 each | Time bonus, full garrisons, budget surplus |

## 10 Historical Locations

- **Cairo** — Capital of the Mamluk Sultanate
- **Alexandria** — Mediterranean port city
- **Gaza** — Gateway between Egypt and Palestine
- **Jerusalem** — Holy city, vital strategic point
- **Kerak** — Fortress on the King's Highway
- **Safad** — Hilltop fortress in Galilee
- **Damascus** — Key city on the trade routes
- **Homs** — Central Syrian crossroads
- **Aleppo** — Northern fortress against Mongols
- **Antioch** — Former Crusader stronghold

## Costs

| Action | Cost |
|--------|------|
| Build Fort | 120 |
| Build Road | 40 |
| Pigeon Post | 60 |
| Station Garrison | 50 |
| Upgrade Fort | 80 |

Starting budget: **1000**

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-based map rendering with animated pigeon routes
- 8 themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- 3 difficulty levels (Easy: 8 forts, Medium: 7, Hard: 6)
- Persistent preferences (theme, language, sound, high score)
- Sidebar help with FAQ, How-To, and Wiki tabs
- Sound effects via Web Audio API
- Touch-friendly for mobile/tablet
- Keyboard shortcuts (1–5 for tools, E to evaluate)

## High Score

Key: `wdiy-hs-fortress-chain`

Stored in localStorage. Persists across sessions.

## Tech

- Pure HTML/CSS/JS — no frameworks, no build step
- Canvas 2D API for map rendering
- Web Audio API for sound
- localStorage for persistence
- Responsive design with auto-scaling canvas

---

Workshop-Diy — Fortress Chain v1.0
