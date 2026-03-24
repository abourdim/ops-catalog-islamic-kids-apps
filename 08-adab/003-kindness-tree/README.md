# Kindness Tree

**Grow your tree with good deeds**

An interactive canvas-based game where Muslim kids grow a virtual tree by choosing the kindest Islamic response to everyday scenarios. Each correct answer sprouts leaves and fruits on the tree, paired with a hadith about kindness.

## Features

- **Canvas-drawn tree** — bare trunk at start; leaves (green ellipses) and colored fruits appear progressively with grow animation
- **30 scenarios** covering: helping at home, kindness to siblings, respecting elders, sharing, forgiving, patience, visiting the sick, feeding animals, picking up litter, kind words, sadaqah, dua for others, smiling, truthfulness, standing up against bullying, and more
- **3 difficulty levels** — Easy (10), Medium (20), Hard (30)
- **Islamic teachings** — each answer reveals a relevant hadith from the Prophet (pbuh)
- **8 CSS themes** — Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual** — English, French, Arabic (RTL auto-enabled)
- **Sound effects** — Web Audio API (grow chime, error buzz, win melody); toggle on/off
- **Splash screen** with Bismillah, theme/language switchers
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Keyboard shortcuts** — 1/2/3 for answers, Enter to start, Escape to close help
- **Persistent preferences** — theme, language, sound, high score saved to localStorage
- **High score tracking** — stored under `wdiy-hs-kindness-tree`
- **Single HTML file, zero dependencies, fully offline**

## How to Play

1. Open `index.html` in any modern browser
2. Click **Start Mission**
3. Select difficulty and press **▶ New Game**
4. Read the scenario and pick the kindest response
5. Watch your tree grow with each correct answer
6. Learn from the hadith shown after each question
7. Try to fill the whole tree with leaves and fruits

## Tech

- Single-file HTML (~400 lines)
- Canvas 2D API for tree rendering with bezier-curve trunk/branches
- Web Audio API for sound (no audio files)
- localStorage for preferences and high scores
- No frameworks, no build tools, no network requests

## Credits

Workshop-Diy — Kindness Tree v1.0
