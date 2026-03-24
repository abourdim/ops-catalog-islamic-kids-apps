# Conquest of Egypt — فتح مصر

Canvas map strategy game where kids lead **Amr ibn al-As (RA)** and 4,000 Muslim troops through Egypt (640 CE).

## Gameplay

- **Canvas map** of Egypt showing 6 cities: Sinai, Pelusium, Bilbeis, Heliopolis, Babylon Fortress, Alexandria
- At each city the player chooses between two strategic options (negotiate vs. siege, tactics vs. brute force)
- **6 strategic decisions** shape the campaign outcome
- Troop count changes based on decisions (start: 4,000; reinforcements from Zubayr at Babylon)
- Babylon Fortress is the key battle — longest siege, reinforcements arrive from Medina
- After Babylon falls, Alexandria surrenders
- Campaign ends with the founding of **Fustat** (seed of modern Cairo)

## Historical Lesson

A small force of 4,000 achieved remarkable results through faith and strategy. Amr ibn al-As founded Fustat and built the first mosque in Africa.

## Features

| Feature | Detail |
|---------|--------|
| Single file | `index.html` — zero dependencies, fully offline |
| Canvas map | Animated Egypt map with Nile, cities, army movement |
| 8 themes | Terminal, Midnight, Ember, Phosphor, Signal, Redshift, Arctic, Sand |
| 3 languages | EN / FR / AR (RTL auto) |
| Sidebar help | FAQ, How-To, Wiki tabs |
| Sound | Web Audio API — no files needed |
| High score | `localStorage` key: `wdiy-hs-egypt` |
| Persisted prefs | Theme, language, sound mute saved to `localStorage` |
| Keyboard | `1`/`2` for choices, `Enter` to start, `Esc` to close help |
| Responsive | Canvas resizes to fit any screen |

## How to Run

Open `index.html` in any modern browser. No server needed.

## Stack

HTML + CSS + Canvas + vanilla JS. No frameworks, no build step, no external assets beyond Google Fonts.
