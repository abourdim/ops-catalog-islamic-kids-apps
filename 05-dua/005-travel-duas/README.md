# Travel Duas

**Supplications for every journey** — An interactive game for Muslim kids to learn and memorize the 20 essential duas for travelling.

## Features

- **Learn Mode**: Browse beautifully presented dua cards with flip animation. Each card shows the travel situation on the front; tap to reveal the full Arabic dua with tashkeel, transliteration, and English meaning.
- **Quiz Mode**: A travel situation is displayed and the player picks the correct dua (shown as the first few Arabic words) from 4 options.
- **3 Difficulty Levels**: Easy (8 common duas), Medium (14), Hard (all 20).
- **20 Travel Duas** covering: boarding a vehicle, starting a journey, arriving at destination, entering a new city, leaving home, returning from travel, during turbulence/fear, seeing a new place, staying at a place, sleeping away from home, entering a hotel, morning/evening of travel, crossing water, climbing uphill, going downhill, travel prayer, breaking fast while travelling, rain during travel, and seeing something amazing.
- **8 CSS Themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand.
- **Trilingual UI**: English, French, Arabic (with RTL support).
- **Sound Effects**: Web Audio API — correct, wrong, and win tones. Toggle on/off.
- **High Score**: Persisted in localStorage (`wdiy-hs-travel-duas`).
- **Keyboard Shortcuts**: 1-4 for quiz answers, arrow keys for learn navigation, Space to flip card, Enter to start, Escape to close help.
- **Sidebar Help**: FAQ, How-To, and Wiki tabs.
- **Offline**: Single HTML file, zero external dependencies beyond Google Fonts (cached after first load).

## Usage

Open `index.html` in any modern browser. No build step or server required.

## Storage Keys

| Key | Purpose |
|---|---|
| `wdiy-hs-travel-duas` | High score (quiz mode, percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

## Credits

Workshop-Diy — Travel Duas v1.0
