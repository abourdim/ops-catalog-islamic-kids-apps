# Islamic Greetings (Salam Game)

**Say the right words at the right time**

An interactive game teaching Muslim kids the correct Islamic greetings, du'as, and phrases for daily situations.

## How It Works

A social situation is presented (with emoji and description). The player picks the correct Islamic greeting or response from 4 options. After answering, a detailed info panel shows the full Arabic phrase, transliteration, English meaning, and when to use it.

## Difficulty Levels

| Level  | Questions | Content                                      |
|--------|-----------|----------------------------------------------|
| Easy   | 10        | Common greetings (salam, bismillah, etc.)    |
| Medium | 15        | Adds responses and less frequent phrases     |
| Hard   | 25+       | Full set including mosque, sleep, travel du'as|

## 27 Situations Covered

- Meeting someone / Responding to salam
- Sneezing etiquette (Yarhamukallah / Yahdikumullah)
- Good news (MashaAllah) / Future plans (InshaAllah)
- Thanking (JazakAllahu Khayran) / Responding (Wa Iyyak)
- Before eating (Bismillah) / After eating (Alhamdulillah)
- Seeing beauty (SubhanAllah) / Calamity (Inna Lillahi)
- Entering home / Farewell to traveler (Fi Amanillah)
- Congratulating (BarakAllahu) / Praising (TabarakAllah)
- Waking up / Going to sleep
- Entering / Leaving the mosque
- Breaking fast (iftar) / Seeing new moon
- During rain / Seeking forgiveness (Astaghfirullah)
- Leaving the house / Entering bathroom / Boarding vehicle

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- Trilingual UI: English, French, Arabic (with RTL support)
- Keyboard shortcuts: 1-4 for answers, Enter to start, Escape to close help
- Sound effects via Web Audio API (no audio files)
- High score persistence via localStorage
- Theme and language preferences persisted
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Progress bar and score tracking
- Detailed info panel after each answer

## Storage Keys

| Key                  | Purpose          |
|----------------------|------------------|
| `wdiy-hs-salam-game` | High score (%)  |
| `wdiy-lang`          | Language pref    |
| `wdiy-theme`         | Theme pref       |
| `wdiy-mute`          | Sound mute state |

## Usage

Open `index.html` in any modern browser. No server required.

---

Workshop-Diy — Islamic Greetings v1.0
