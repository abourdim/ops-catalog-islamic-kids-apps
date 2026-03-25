# Camp Layout Designer

Interactive grid-based strategy game where kids design a military camp layout by placing tents, watchtowers, supply areas, stables, kitchen, prayer area, and more.

## Concept

The Prophet (peace be upon him) organized military camps with designated areas for prayer, supplies, and rest. The commander's tent was central, with guards posted at the perimeter. Even during campaigns, prayer was never abandoned. Players learn about camp organization and strategic placement.

## Gameplay

1. Start with a fresh 7x7 grid
2. Select structure types from the palette (8 types available)
3. Click grid cells to place structures
4. Watchtowers on edges earn bonus defense points
5. Including a prayer area is essential and earns significant bonus
6. Click Evaluate Camp to calculate your layout score

## Structures

| Structure | Icon | Points | Bonus |
|-----------|------|--------|-------|
| Tent | tent | 3 | Soldier housing |
| Watchtower | tower | 5 | +5 on edges |
| Supplies | box | 4 | Storage |
| Stables | horse | 4 | Cavalry housing |
| Kitchen | pot | 3 | Feeding troops |
| Prayer Area | mosque | 8 | +15 bonus |
| Commander | star | 6 | +8 bonus |
| Water Well | drop | 5 | +5 bonus |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- 7x7 interactive grid with click-to-place
- Variety bonus for using all structure types
- Edge placement strategy for watchtowers
- High score persistence via localStorage

## Lesson

Organization and priorities: The Prophet (peace be upon him) always ensured a prayer area was established first, even in military camps. This teaches children that spiritual duties remain important regardless of circumstances, and that good planning leads to success.

## Technical

- **HS_KEY**: `wdiy-hs-camp-layout-designer`
- **Footer**: Workshop-Diy — Camp Layout Designer v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
