# Hadith Garden

**Grow your garden of knowledge**

An interactive canvas-based garden game where Muslim kids learn authentic hadiths. Each correct answer plants a flower or tree in a visual garden that fills up as more hadiths are learned.

## Features

- **30 Hadiths** across 6 themed garden sections:
  - Kindness Garden (5 hadiths)
  - Knowledge Garden (5 hadiths)
  - Character Garden (5 hadiths)
  - Worship Garden (5 hadiths)
  - Community Garden (5 hadiths)
  - Nature Garden (5 hadiths)
- **Canvas Garden**: Blue sky, green ground, flowers as colored petals on stems, trees as brown trunks with green crowns — all drawn live on HTML5 Canvas
- **Sprouting Animation**: Each correct answer triggers a growth animation for the planted flower/tree
- **3 Difficulty Levels**: Easy (10), Medium (20), Hard (30 hadiths)
- **Hadith Sources**: Every hadith displays its source reference after answering
- **8 CSS Themes**: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 Languages**: English, French, Arabic (with RTL support)
- **Sound Effects**: Web Audio API — correct, wrong, and win sounds (toggle on/off)
- **High Score**: Persisted in localStorage (`wdiy-hs-hadith-garden`)
- **Keyboard Shortcuts**: 1-4 for answer selection, Enter to start, Escape to close help
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Single HTML file, zero dependencies, fully offline**

## How to Play

1. Open `index.html` in any modern browser
2. Click **Start Mission** on the splash screen
3. Choose difficulty (Easy / Medium / Hard)
4. Read the hadith topic and pick the correct hadith text from 4 options
5. Watch your garden grow with each correct answer
6. Fill the entire garden for a perfect score

## Tech

- Single-file HTML (~400 lines)
- HTML5 Canvas for garden rendering
- CSS custom properties for theming
- Web Audio API for sound
- localStorage for preferences and high scores
- Zero external dependencies (fonts loaded from Google Fonts but not required)

---

Workshop-Diy — Hadith Garden v1.0
