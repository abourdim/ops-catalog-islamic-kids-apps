# Khaybar Food Tester

Interactive food safety observation game based on the historical incident at Khaybar (7 AH / 628 CE) where poisoned food was offered to the Prophet (peace be upon him).

## Concept

After the Battle of Khaybar, Zaynab bint al-Harith placed poison in a lamb shoulder and offered it to the Prophet. He was divinely warned after one bite. Players learn to identify safe vs unsafe food by reading observation clues — color, smell, source, and context.

## The 12 Food Items

| # | Item | Safe? | Key Clue |
|---|------|-------|----------|
| 1 | Roasted Lamb Shoulder | Unsafe | Offered by stranger, bitter smell |
| 2 | Fresh Barley Bread | Safe | Baked by companion's family |
| 3 | Goat Milk | Safe | Freshly milked from camp livestock |
| 4 | Sealed Honey Jar | Safe | Intact seal, known storage |
| 5 | Mystery Stew | Unsafe | Unknown source, strange color |
| 6 | Olive Oil | Safe | Known Khaybar farm, sealed |
| 7 | Dried Meat | Unsafe | Abandoned area, green discoloration |
| 8 | Lentil Soup | Safe | Camp kitchen, others eating safely |
| 9 | Dried Grapes | Safe | From Medina supplies |
| 10 | Herbal Drink | Unsafe | Stranger insists, murky color |
| 11 | Fresh River Fish | Safe | Caught by companions, clear eyes |
| 12 | Well Water | Unsafe | Enemy fortress, tampered seal |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Theme/language/sound preferences persisted
- Items shuffled each playthrough
- Timer tracking

## Lesson

Food safety and vigilance are important Islamic values. The Prophet taught us to say Bismillah before eating, to eat only halal and tayyib (wholesome) food, and to be cautious about food from unknown sources. Trust but verify.

## Technical

- **HS_KEY**: `wdiy-hs-khaybar-food-tester`
- **Footer**: Workshop-Diy — Khaybar Food Tester v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
