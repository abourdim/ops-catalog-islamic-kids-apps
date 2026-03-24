# Adhkar Counter — Your Digital Tasbeeh

A single-file HTML interactive adhkar (remembrance) counter app for Muslim kids and families. Zero dependencies, fully offline.

## Features

- **Large circular counter** with SVG progress ring — tap or press Space to increment
- **7 preset adhkar** with authentic target counts:
  - SubhanAllah x33
  - Alhamdulillah x33
  - Allahu Akbar x34
  - La ilaha illallah x100
  - Astaghfirullah x100
  - Salawat x100
  - SubhanAllahi wa bihamdihi x100
- **Custom dhikr** — set your own text and target count
- **Auto-advance** post-salah sequence: SubhanAllah (33) -> Alhamdulillah (33) -> Allahu Akbar (34)
- **Haptic vibration** on each tap (device-dependent)
- **Audio click** via Web Audio API (toggleable)
- **Daily total** tracked in localStorage, resets each day
- **High score** persistence (best daily total)

## Controls

| Action | Input |
|--------|-------|
| Count | Tap circle / Space |
| Reset | Click Reset / press R |
| Help | Click ? button / Escape to close |

## Themes

8 built-in themes: Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand.

## Languages

Trilingual UI: English, French, Arabic (with RTL support).

## Technical

- Single HTML file, zero external dependencies (except Google Fonts)
- All preferences persisted in localStorage
- HS_KEY: `wdiy-hs-adhkar-counter`
- Fully offline after first load

## License

Workshop-Diy — Adhkar Counter v1.0
