# Islamic Battles — Strategy Learning Game

**Workshop-Diy — Islamic Battles v1.0**

An interactive quiz game that teaches Muslim kids about the major battles of early Islam, their strategies, outcomes, and spiritual lessons.

## Features

- **10 Battles Covered**: Badr (624), Uhud (625), Khandaq/Trench (627), Khaybar (628), Mu'tah (629), Conquest of Mecca (630), Hunayn (630), Tabuk (630), Riddah Wars (632), Yarmouk (636)
- **30 Quiz Questions**: Mixed question types covering strategies, locations, commanders, outcomes, and lessons
- **Canvas Battle Maps**: Each correct answer reveals a simplified tactical map showing terrain, army positions, and movement arrows
- **Battle Info Cards**: Full details including year, location, forces, opponent, outcome, key strategy, and Islamic lesson
- **3 Difficulty Levels**: Easy (4 battles, 8 Qs), Medium (7 battles, 12 Qs), Hard (all 10, 15 Qs)
- **8 CSS Themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual**: English, French, Arabic (RTL support)
- **Sound Effects**: Web Audio API — correct, wrong, win sounds (toggle on/off)
- **High Score**: Persisted in localStorage (key: `wdiy-hs-battles`)
- **Keyboard Shortcuts**: 1-4 for answer selection, Enter to start, Escape to close help
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Fully Offline**: Single HTML file, zero external dependencies (except Google Fonts on first load)

## How to Play

1. Open `index.html` in any modern browser
2. Click **Start Mission** on the splash screen
3. Select difficulty (Easy / Medium / Hard)
4. Read each question and pick the correct battle from 4 options
5. Correct answers show a battle map and info card with strategic and Islamic lessons
6. Try to beat your high score!

## Battles & Lessons

| Battle | Year | Key Lesson |
|--------|------|------------|
| Badr | 624 | Trust in Allah (Tawakkul) |
| Uhud | 625 | Obedience to the Prophet (peace be upon him) |
| Khandaq | 627 | Shura (consultation) |
| Khaybar | 628 | Patience (Sabr) and persistence |
| Mu'tah | 629 | Planning ahead and courage |
| Conquest of Mecca | 630 | Mercy and forgiveness |
| Hunayn | 630 | Humility — never rely on numbers alone |
| Tabuk | 630 | Courage and answering the call |
| Riddah Wars | 632 | Firmness in faith |
| Yarmouk | 636 | Unity of the Ummah |

## Tech

- Single-file HTML (no build step, no dependencies)
- CSS custom properties for theming
- Canvas 2D for battle maps
- Web Audio API for sound
- localStorage for preferences and high scores

## Local Storage Keys

- `wdiy-hs-battles` — High score (percentage)
- `wdiy-lang` — Language preference
- `wdiy-theme` — Theme preference
- `wdiy-mute` — Sound mute state
