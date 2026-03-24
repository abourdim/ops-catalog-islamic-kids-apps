# Islamic Landmarks — Interactive World Map

> Workshop-Diy — Islamic Landmarks v1.0

An interactive canvas-based world map for Muslim kids to explore 20 iconic Islamic landmarks across the globe.

## Features

- **Explore Mode** — Click any glowing dot on the map to learn the landmark's name, city, country, year built, and a fun fact
- **Quiz Mode** — "Click on [landmark name]!" challenges kids to find the correct location on the map
- **3 Difficulty Levels** — Easy (6 famous landmarks), Medium (12), Hard (all 20)
- **Canvas-based Map** — Simplified Mercator-projected world map with continent outlines, grid lines, and interactive dots at approximate real-world positions
- **8 Themes** — Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 Languages** — English, French, Arabic (with automatic RTL support)
- **Sound Effects** — Web Audio API (correct, wrong, win sounds; toggleable)
- **High Score** — Persisted in localStorage (`wdiy-hs-islamic-map`)
- **Timer** — Tracks quiz duration
- **Sidebar Help** — FAQ, How-To, and Wiki tabs
- **Keyboard Shortcuts** — Enter to start, Escape to close help
- **Fully Offline** — Single HTML file, zero external dependencies (except Google Fonts on first load)

## Landmarks (20)

| # | Landmark | City | Country | Tier |
|---|----------|------|---------|------|
| 1 | Masjid al-Haram | Mecca | Saudi Arabia | Easy |
| 2 | Masjid an-Nabawi | Medina | Saudi Arabia | Easy |
| 3 | Al-Aqsa Mosque | Jerusalem | Palestine | Easy |
| 4 | Hassan II Mosque | Casablanca | Morocco | Easy |
| 5 | Sultan Ahmed (Blue) Mosque | Istanbul | Turkey | Easy |
| 6 | Taj Mahal | Agra | India | Easy |
| 7 | Hagia Sophia | Istanbul | Turkey | Medium |
| 8 | Great Mosque of Cordoba | Cordoba | Spain | Medium |
| 9 | Al-Azhar Mosque | Cairo | Egypt | Medium |
| 10 | Alhambra | Granada | Spain | Medium |
| 11 | Badshahi Mosque | Lahore | Pakistan | Medium |
| 12 | Istiqlal Mosque | Jakarta | Indonesia | Medium |
| 13 | Faisal Mosque | Islamabad | Pakistan | Medium |
| 14 | Sheikh Zayed Mosque | Abu Dhabi | UAE | Medium |
| 15 | Dome of the Rock | Jerusalem | Palestine | Medium |
| 16 | Registan | Samarkand | Uzbekistan | Hard |
| 17 | Great Mosque of Djenne | Djenne | Mali | Hard |
| 18 | Suleymaniye Mosque | Istanbul | Turkey | Hard |
| 19 | Sankore Mosque | Timbuktu | Mali | Hard |
| 20 | Crystal Mosque | Kuala Terengganu | Malaysia | Hard |

## Usage

Open `index.html` in any modern browser. No build step or server required.

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-islamic-map` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |
