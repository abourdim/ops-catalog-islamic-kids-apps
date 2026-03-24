# Prisoner Rights

**Battle of Badr — Prisoner Processing Game**

## Overview

After the Battle of Badr, prisoners arrive at the Muslim camp. The player must ensure each prisoner receives proper Islamic treatment according to the Prophet's (peace be upon him) guidelines: provide food, water, shelter, medical care, register names, offer Islam without compulsion, and arrange release through ransom or literacy teaching.

## Gameplay

- 12 prisoners with unique situations (names, tribes, conditions)
- Match the correct Islamic treatment to each prisoner from 4 choices
- Treatments include: ransom, teach-to-free, feed, give water, shelter, heal wounds, offer Islam, register
- Feedback after each answer explains the historical/Islamic basis
- Score based on percentage of correct Prophetic guidelines followed
- End-of-game summary with lesson recap

## Key Historical Reference

After Badr (2 AH / 624 CE), the Prophet Muhammad (peace be upon him) established prisoner rights:
- Prisoners were fed the same food Muslims ate
- Wounded received medical care first
- Names and tribes were registered
- Literate prisoners who could not pay ransom earned freedom by **teaching 10 Muslims to read and write**
- Islam was presented without any compulsion

## Lesson

- **Dignity of prisoners** — established 1400 years before modern Geneva Conventions
- **Education valued over money** — literacy teaching accepted as ransom equal to wealth

## Features

| Feature | Detail |
|---------|--------|
| Format | Single HTML file, zero dependencies, fully offline |
| Themes | 8 (Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand) |
| Languages | EN / FR / AR (RTL auto-switch) |
| Sound | Web Audio API — no files needed |
| High Score | Persisted in localStorage |
| HS_KEY | `wdiy-hs-prisoner` |
| Sidebar Help | FAQ, How-To, Wiki tabs |
| Keyboard | 1-4 for choices, Enter to start, Esc to close help |
| Privacy | Local-first, no tracking, no external calls |

## Difficulty

| Level | Prisoners |
|-------|-----------|
| Easy | 6 |
| Medium | 9 |
| Hard | 12 |

## File Structure

```
050-prisoner-processing/
  index.html   — Complete game (single file)
  README.md    — This file
```

## Tech

- Pure HTML/CSS/JS
- Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
- localStorage for preferences and high score
- Web Audio API for sound effects
