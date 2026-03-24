# Mountain Pass Defense

Canvas-based tower-defense game for Muslim kids. Defend a narrow mountain pass from enemy waves by placing archers on cliffs, rolling boulders, and positioning infantry at the choke point.

## Gameplay

- **5 waves** of increasing difficulty
- **3 unit types**: Archer (ranged, cliff-only), Boulder (one-shot area damage, cliff-only), Infantry (melee blocker, pass-only)
- **Gold economy**: start with gold, earn more per kill and wave completion
- **3 difficulty levels**: Easy, Medium, Hard (affects enemy count, HP, speed, starting gold, max escapes)
- **Enemy types**: Normal, Fast (low HP, high speed), Armored (high HP, slow)
- **Score**: total enemies stopped. High score saved to localStorage.

## Historical Reference

Inspired by the strategic use of terrain in early Islamic battles:
- **Uhud**: The Prophet (peace be upon him) placed 50 archers on a hill to guard the rear flank
- **Khandaq (Trench)**: A trench was dug across the northern approach to Madinah, using terrain as a defensive barrier

This game teaches kids how terrain and positioning were key strategic elements.

## Controls

| Input | Action |
|-------|--------|
| Click cliff (brown) | Place archer or boulder |
| Click pass (gray) | Place infantry |
| 1 / 2 / 3 keys | Select archer / boulder / infantry |
| Tool bar buttons | Select unit type |
| Enter | Start game |

## Template Features

- **8 themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 languages**: EN, FR, AR (with RTL support)
- **Sidebar help**: FAQ, How-To, Wiki tabs
- **Sound**: Web Audio API (arrow, boulder, sword, victory sounds)
- **High score**: localStorage key `wdiy-hs-mountain-pass`
- **Splash screen** with Bismillah
- **Offline**: Single HTML file, zero dependencies
- **Responsive**: Canvas scales to fit screen, touch support for mobile

## Tech

Single-file HTML with inline CSS and JS. Canvas 2D rendering at 780x500. No external dependencies. Runs fully offline.

## File

```
043-mountain-pass-defense/
  index.html   — complete game (single file)
  README.md    — this file
```
