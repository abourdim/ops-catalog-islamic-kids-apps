# Archers of Uhud

**Will you hold your position?**

A canvas-based first-person archer simulator set during the Battle of Uhud (3 AH / 625 CE). The player is one of the 50 archers stationed on the hill by the Prophet (peace be upon him) with strict orders not to leave.

## Gameplay

### Phase 1: Defend the Flank
Quraysh cavalry approach from the sides. Click or tap on the battlefield to shoot arrows and repel them. Each wave sends more enemies.

### Phase 2: The Temptation
The Muslims are winning below. Quraysh retreat. Gold spoils appear on the field. Two buttons appear:
- **Leave hill to collect spoils** (glowing, tempting)
- **Stay on the hill — obey the Prophet** (steady, disciplined)

### Phase 3a: Hero Ending (Stayed)
Khalid ibn al-Walid's cavalry attacks the unguarded flank but the archers hold. More waves of cavalry are repelled. The Muslims win completely. Bonus +100 points for obedience.

### Phase 3b: Disaster Ending (Left)
Khalid's cavalry charges through the gap left by the archers. The battlefield reverses. Animated cavalry overrun. Score penalty of -50 points.

## Lesson
Obedience, discipline, and resisting temptation even when winning. The Prophet's order echoes throughout the game:

> "Do not leave this hill even if you see birds eating our flesh."

## Scoring
- Each arrow hit: 10 points
- Each enemy repelled: 20 points
- Staying on the hill bonus: +100
- Leaving the hill penalty: -50

## Controls
- **Click/Tap**: Shoot arrows at enemy cavalry
- **S key**: Stay on the hill (during choice)
- **L key**: Leave the hill (during choice)
- **Enter**: Start game
- **Escape**: Close help panel

## Difficulty
- **Easy**: Slower enemies, fewer waves, smaller groups
- **Medium**: Balanced challenge
- **Hard**: Fast enemies, more waves, larger groups

## Features
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- 3 languages: English, French, Arabic (RTL)
- Splash screen with Bismillah
- Sidebar help panel (FAQ, How-To, Wiki)
- High score persistence (localStorage)
- Sound/theme/language preferences persisted
- Web Audio API sounds (no external files)
- Fully offline, single HTML file, zero dependencies
- Touch-friendly for mobile/tablet

## Storage Keys
- `wdiy-hs-uhud-archer` — High score
- `wdiy-lang` — Language preference
- `wdiy-theme` — Theme preference
- `wdiy-mute` — Sound mute state

## Footer
Workshop-Diy — Archers of Uhud v1.0
