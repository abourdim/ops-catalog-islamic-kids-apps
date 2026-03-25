# Weapons Forge

Interactive crafting game where kids forge swords, shields, spears, and chainmail by selecting materials, heating methods, and shaping techniques.

## Concept

Muslim blacksmiths were renowned for their mastery of metallurgy, particularly Damascus steel (Wootz steel). The Quran itself references Allah teaching Prophet David to make chainmail armor (Surah Saba, 34:10-11). Players learn about historical weapon crafting through a step-by-step forging process.

## Gameplay

1. Choose a weapon type: Sword, Shield, Spear, or Chainmail
2. Select a material: Iron, Steel, Damascus Steel, or Bronze
3. Choose a heating method: Coal Forge, Bellows Forge, or Blast Furnace
4. Pick a shaping technique: Hammering, Oil Quench, Folding, or Polish & Edge
5. Each choice affects the weapon's ATK, DEF, Durability, and Weight stats
6. Quality score is calculated from the combination of all choices

## Weapons & Materials

| Weapon | Base ATK | Base DEF | Base DUR |
|--------|----------|----------|----------|
| Sword | 8 | 3 | 5 |
| Shield | 1 | 9 | 7 |
| Spear | 7 | 2 | 4 |
| Chainmail | 0 | 10 | 8 |

| Material | ATK Mult | DEF Mult | Special |
|----------|----------|----------|---------|
| Iron | 1.0x | 1.0x | Basic |
| Steel | 1.3x | 1.2x | Stronger |
| Damascus Steel | 1.6x | 1.4x | Best quality |
| Bronze | 0.8x | 0.9x | Lighter |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects including forge sounds
- Step-by-step crafting with visual progress indicators
- Weapon stat calculation system
- High score persistence via localStorage

## Lesson

Craftsmanship in Islam: Skilled labor and craftsmanship are highly valued in Islam. The Prophet (peace be upon him) said that Allah loves when one of you does work and perfects it. Muslim metallurgists and blacksmiths advanced the science of metalworking for centuries.

## Technical

- **HS_KEY**: `wdiy-hs-weapons-forge`
- **Footer**: Workshop-Diy — Weapons Forge v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
