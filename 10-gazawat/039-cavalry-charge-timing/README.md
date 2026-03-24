# Cavalry Charge — Timing Game

**Workshop-Diy** | Gazawat Series | `039-cavalry-charge-timing`

## Overview

A canvas-based cavalry charge timing game for Muslim kids. Players command cavalry on the left side of the battlefield and must click/tap at the perfect moment as a timing meter fills. Inspired by the tactical genius of Khalid ibn al-Walid (may Allah be pleased with him) and his mastery of cavalry maneuvers.

## Gameplay

- Enemy infantry approaches from the right
- A timing meter fills with colored zones: red (too early/late), yellow (close), green (perfect)
- Player clicks **CHARGE** (or presses Space) at the right moment
- **Too early**: horses tire before reaching the enemy (+0 pts)
- **Too late**: enemy sets spears and braces (+0 pts)
- **Perfect timing**: devastating cavalry impact (+100 pts)
- 10 rounds with increasing meter speed per round
- Score based on timing accuracy

## Difficulty Levels

| Level  | Meter Speed | Green Zone Size | Enemy Speed |
|--------|-------------|-----------------|-------------|
| Easy   | Slow        | 25%             | Slow        |
| Medium | Medium      | 18%             | Medium      |
| Hard   | Fast        | 12%             | Fast        |

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-rendered battlefield with animated cavalry and infantry
- 8 color themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Keyboard support: Space to charge, Enter to start
- Mobile/touch friendly

## Controls

- **Click/Tap** canvas or CHARGE button to charge
- **Space** key to charge during round
- **Enter** key to start game
- **Escape** to close help sidebar

## High Score

- Key: `wdiy-hs-cavalry-charge`
- Stored in localStorage
- Tracks best total score across sessions

## Historical Context

Khalid ibn al-Walid (may Allah be pleased with him) was renowned for his cavalry tactics. At battles such as Yarmouk, he kept cavalry reserves hidden and timed their charges to break enemy formations at the decisive moment. This game teaches children that patience and timing are as important as courage in battle.

## File Structure

```
039-cavalry-charge-timing/
  index.html   — Complete game (single file)
  README.md    — This file
```
