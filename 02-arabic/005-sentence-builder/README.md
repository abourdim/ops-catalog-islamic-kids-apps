# Sentence Builder — Build Arabic Sentences

An interactive Arabic sentence builder for Muslim kids. Arrange shuffled Arabic words in the correct right-to-left order to form the translation of an English sentence.

## Features

- **30+ sentences** covering daily Islamic phrases (Bismillah, Salam, Alhamdulillah, etc.), family, school, nature, food, and daily activities
- **3 difficulty levels**: Easy (2-3 words), Medium (3-4 words), Hard (5+ words)
- **Tap to build**: Tap shuffled word cards in the correct RTL order; correct words move to the answer line, wrong words flash red
- **Undo support**: Click placed words or press Backspace to remove them
- **Skip**: Press S to skip a sentence and see the correct answer
- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Trilingual UI**: English, French, Arabic (auto RTL)
- **Sound effects**: Web Audio API — no external files
- **High score**: Persisted in localStorage
- **Keyboard shortcuts**: 1-9 for word cards, Enter to start, S to skip, Backspace to undo, Escape to close help
- **Fully offline**: Single HTML file, zero dependencies

## Usage

Open `index.html` in any modern browser.

## Storage Keys

| Key | Purpose |
|---|---|
| `wdiy-hs-sentence-builder` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Footer

Workshop-Diy — Sentence Builder v1.0
