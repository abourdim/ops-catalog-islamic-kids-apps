# Battle of Uhud — Mountain Defense

> Hold the hill or lose the battle

A single-file HTML5 Canvas strategy game for Muslim kids about the Battle of Uhud (3 AH / 625 CE).

## Gameplay

1. **Deploy Phase** — Drag 50 archers to position them on the strategic hill. Choose infantry formation (line, wedge, or circle) in the valley.
2. **Phase 1: Battle** — Watch the Muslims push back the Quraysh forces. The enemy retreats and spoils appear on the battlefield.
3. **Decision Point** — Choose: **Stay on the hill** (obey the Prophet's order) or **Go collect spoils** (leave the flank exposed).
4. **Outcome** — If you stay, Khalid ibn al-Walid's cavalry charge is blocked and the Muslims win. If you leave, the cavalry flanks the army and chaos follows.
5. **Lesson** — Learn about obedience to the leader and discipline in victory. Replay to try the other choice.

## Historical Context

At the Battle of Uhud, the Prophet Muhammad (peace be upon him) stationed 50 archers on a hill with clear orders not to leave under any circumstances. When the Quraysh began retreating, most archers left to collect spoils. Khalid ibn al-Walid seized the opportunity and led a cavalry charge around the now-unguarded hill, attacking the Muslims from behind.

## Features

- Canvas-based battlefield with Mount Uhud, valley, and archers' hill
- Drag-to-position archer placement
- 3 infantry formations: line, wedge, circle
- Animated battle phases with particle effects
- Two branching outcomes based on player choice
- Historical lesson with Quran reference (Aal Imran 3:152)
- 8 CSS themes (Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand)
- 3 languages (EN, FR, AR with RTL support)
- Sound effects via Web Audio API (no files needed)
- High score persistence via localStorage
- Keyboard shortcuts (1/2 for choices, Enter to start, H for help, Esc to close help)
- Fully offline, zero dependencies, single HTML file

## Keys

| Key | Action |
|-----|--------|
| `Enter` | Start mission / New game |
| `1` | Choose "Stay on the hill" |
| `2` | Choose "Go collect spoils" |
| `H` | Open help sidebar |
| `Esc` | Close help sidebar |

## Storage

| Key | Purpose |
|-----|---------|
| `wdiy-hs-uhud-defense` | High score |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Footer

Workshop-Diy — Battle of Uhud v1.0
