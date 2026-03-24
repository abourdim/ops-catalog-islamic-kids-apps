# Shuhada Garden

Interactive memorial to learn about the famous shuhada (martyrs) of early Islam.

## Features

- **Canvas Garden Scene** — 20 trees, each representing a shaheed. Click a tree to read their story.
- **20 Shuhada** — Hamza, Mus'ab, Ja'far, Zayd, Abdullah ibn Rawahah, Sumayyah, Yasir, Anas ibn Nadr, Sa'd ibn Muadh, Ubayy ibn Ka'b, Hanzala, Abdullah ibn Jahsh, Khubayb ibn Adiy, Asim ibn Thabit, Harithah ibn Suraqah, Umayr ibn al-Humam, Sa'd ibn ar-Rabi, Umm Umarah, Talhah ibn Ubaydullah, Ammar ibn Yasir.
- **Story Details** — For each shaheed: name (English + Arabic), battle, how they were martyred, and the Prophet's words about them.
- **Quiz Mode** — 10 questions per round. Match the shaheed to their story, battle, or hadith. 4 options per question.
- **8 Themes** — Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand.
- **3 Languages** — English, French, Arabic (RTL auto-enabled).
- **Sound** — Web Audio API tones for correct, wrong, and win. Toggle on/off.
- **Sidebar Help** — FAQ, How-To, Wiki tabs.
- **High Score** — Best quiz percentage persisted in localStorage (`wdiy-hs-shuhada`).
- **Preferences Persisted** — Theme, language, sound mute saved in localStorage.

## Tech

- Single HTML file, zero dependencies, fully offline.
- Canvas-based garden with hover effects, visited state tracking.
- Keyboard shortcuts: 1-4 for quiz answers, Enter to start, Escape to close help.

## HS_KEY

```
wdiy-hs-shuhada
```
