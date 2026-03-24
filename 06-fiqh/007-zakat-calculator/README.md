# Zakat Calculator

**Learn the pillar of giving**

An interactive Zakat learning tool for Muslim kids. Calculate Zakat, explore the 8 recipients from Quran 9:60, and test your knowledge with quizzes.

## Features

### Learn Mode
- **Interactive calculator** — enter a savings amount and see the 2.5% Zakat breakdown
- **Visual bar chart** showing Zakat (2.5%) vs remaining (97.5%)
- **Nisab explanation** — gold (85g), silver (595g), and Hawl (lunar year) requirement
- **8 Zakat recipients** from Quran 9:60 displayed as cards with Arabic names and descriptions:
  1. Al-Fuqara (the poor)
  2. Al-Masakin (the needy)
  3. Al-Amil (Zakat collectors)
  4. Al-Muallafat (new Muslims)
  5. Ar-Riqab (freeing those in bondage)
  6. Al-Gharimin (debtors)
  7. Fi Sabilillah (in Allah's cause)
  8. Ibn as-Sabil (stranded travelers)

### Quiz Mode
- **3 difficulty levels:** Easy (concepts), Medium (calculations), Hard (detailed rules)
- **15+ questions** mixing knowledge and calculation
- Multiple choice and typed-input question types
- Progress bar, score tracking, and high score persistence
- Sound effects via Web Audio API

## Technical

| Detail | Value |
|--------|-------|
| Format | Single HTML file, zero dependencies |
| Offline | Fully offline after first load |
| Themes | 8 (Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand) |
| Languages | EN / FR / AR (RTL auto-enabled) |
| Sound | Web Audio API, no external files |
| Storage | localStorage for theme, language, sound, high score |
| HS_KEY | `wdiy-hs-zakat-calc` |

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `1`-`4` | Select answer in quiz mode |
| `Enter` | Start / submit answer / calculate |
| `Escape` | Close help sidebar |

## Usage

Open `index.html` in any modern browser. No server required.

---

Workshop-Diy — Zakat Calculator v1.0
