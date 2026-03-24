# Battle Signals

**Battle Communication System** — Canvas-based signal relay puzzle for Muslim kids.

## Concept

Players act as the communications officer for a Muslim army commander. Each round, the commander issues an order that must be relayed to the correct wing of the army using the appropriate signal method. Orders are time-sensitive — delays mean the wing acts on outdated commands.

## Gameplay

1. **Read the order** — the commander issues one of 5 orders: Advance, Hold, Retreat, Reinforce, Cavalry Charge
2. **Choose signal method** — pick the correct communication method:
   - **Flag signals** (day only) — colored flags visible across the battlefield
   - **Mounted messengers** (any time) — rider on horseback carries the order
   - **Fire beacons** (night only) — fire signals on hilltops
   - **Drum signals** (any time) — rhythmic drum patterns
3. **Select target wing** — click the correct destination: Left Wing, Right Wing, Reserve, or Vanguard
4. **Beat the timer** — each round has a countdown; delays lose points

## Features

- Canvas-rendered battlefield map with commander at center, wings on sides, reserve behind, vanguard ahead
- Animated signal delivery (flag waving, horse riding, beacon glow, drum waves)
- Day/night cycle — later rounds switch to night, restricting available methods
- 10 rounds of increasing difficulty (shorter timers, night conditions)
- 3 difficulty levels: Easy (8), Medium (10), Hard (14)
- Score tracking: correct orders + on-time delivery rate
- High score persistence via localStorage

## Tech

- Single HTML file, zero dependencies, fully offline
- HTML5 Canvas for battlefield rendering
- Web Audio API for sound effects (flag, drum, beacon, horn, win/error)
- 8 themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- 3 languages: EN, FR, AR (with RTL support)
- Sidebar help with FAQ, How-To, Wiki tabs
- Keyboard shortcuts: 1-4 for selection, Enter to start

## HS_KEY

`wdiy-hs-battle-signals`

## File

```
046-battle-communication/
  index.html   — complete game (single file)
  README.md    — this file
```
