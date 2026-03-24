# Night March Navigator

Canvas-based celestial navigation puzzle for Muslim kids. Guide armies through night marches using stars, constellations, and the moon — just like historical Muslim commanders.

## Game

- **Genre**: Canvas navigation puzzle
- **HS_KEY**: `wdiy-hs-night-march`
- **Missions**: 5 with increasing complexity
- **Phases per mission**: 3 (Star ID → Path Choice → March)

### Gameplay

1. **Phase 1 — Star Navigation**: Identify Polaris (North Star) by clicking on it in the night sky canvas
2. **Phase 2 — Path Selection**: Choose the safest route through terrain (avoid mountains, rivers, obstacles)
3. **Phase 3 — March**: Click to guide your army from camp to target. Units follow the leader in formation

### Missions

| # | Name | Direction | Terrain | Historical Reference |
|---|------|-----------|---------|---------------------|
| 1 | Scout to the Oasis | N | Desert | Basic navigation |
| 2 | Khalid's Flank at Mu'tah | E | Plains | Khalid ibn al-Walid, 629 CE |
| 3 | Mountain Pass Crossing | NE | Mountain | Mountain warfare |
| 4 | River Ford by Starlight | NW | River | River crossing tactics |
| 5 | Mehmed's Final Advance | N | Siege | Sultan Mehmed II, Constantinople 1453 |

### Scoring

- Correct star identification: +20 pts
- Good path choice: +20 pts (risky path: +5 pts)
- Reaching target: +20 pts
- Formation bonus: +15 pts (perfect) / +5 pts (scattered)
- Wrong star click: -5 pts
- Obstacle collision: -2 pts

## Features

- **8 themes**: Terminal, Midnight (default), Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 languages**: EN, FR, AR (RTL support)
- **3 difficulties**: Easy, Medium, Hard (affects obstacle count and movement speed)
- **Constellations**: Ursa Minor, Ursa Major, Orion, Cassiopeia (added progressively)
- **Sound**: Web Audio API (no files)
- **High scores**: localStorage persistence
- **Sidebar help**: FAQ, How-To, Wiki tabs
- **Splash screen**: Bismillah, description, start button
- **Offline**: Single HTML file, zero dependencies

## Historical Context

Muslim armies extensively used night marches for tactical surprise:
- **Khalid ibn al-Walid at Mu'tah (629 CE)**: Used night repositioning to manage forces
- **Sultan Mehmed II at Constantinople (1453 CE)**: Moved troops and ships under cover of darkness
- **Celestial navigation**: Muslim astronomers refined star catalogues and navigation methods that armies relied upon

## Tech

- Single HTML file
- HTML5 Canvas for rendering
- Zero external dependencies (fonts loaded but not required)
- Runs fully offline after first load
- Touch support for mobile devices
