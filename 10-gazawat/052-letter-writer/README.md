# Prophet's Letters — Letter Writer

Interactive creative writing tool where kids compose diplomatic letters as the Prophet Muhammad ﷺ did, learning the art of respectful communication and invitation to truth.

## Overview

After the Treaty of Hudaybiyyah (6 AH), the Prophet ﷺ sent sealed letters to major world leaders. This tool recreates 6 of those historical letters as interactive exercises.

## Features

- **6 Historical Letters** — Heraclius (Rome), Khosrow II (Persia), Najashi (Abyssinia), Muqawqis (Egypt), Mundhir ibn Sawa (Bahrain), Jaifer & Abd (Oman)
- **2 Game Modes** — Fill in the Blanks / Arrange in Correct Order
- **Letter Structure** — Each letter follows: Bismillah → Greeting → Introduction → Invitation → Consequence
- **Historical Responses** — After completing each letter, see how each ruler responded
- **Lessons** — Diplomacy, respectful communication, inviting to truth
- **8 Themes** — Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand
- **3 Languages** — EN / FR / AR (with RTL support)
- **High Score** — Persisted in localStorage
- **Sound** — Web Audio API (no files)
- **Offline** — Single HTML file, zero dependencies

## Letters & Responses

| Ruler | Empire | Response |
|-------|--------|----------|
| Heraclius | Byzantine Rome | Interested, recognized signs of prophethood |
| Khosrow II | Sassanid Persia | Tore the letter in anger |
| Najashi | Abyssinia (Aksum) | Accepted Islam |
| Muqawqis | Byzantine Egypt | Polite refusal, sent gifts |
| Mundhir ibn Sawa | Bahrain | Accepted Islam |
| Jaifer & Abd | Oman | Accepted Islam |

## Keys

- **HS_KEY**: `wdiy-hs-letters`
- **Arrow Left/Right**: Navigate between letters
- **Enter**: Start
- **Escape**: Close help sidebar

## Tech

- Single HTML file
- Zero external dependencies (fonts loaded from Google Fonts CDN, optional)
- localStorage for preferences (theme, language, sound, high score)
- Web Audio API for sound effects
- Drag-and-drop + click-to-swap for arrange mode
- Fully responsive, works on mobile/tablet/desktop
