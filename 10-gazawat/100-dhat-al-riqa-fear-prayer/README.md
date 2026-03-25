# Dhat al-Riqa Fear Prayer

Interactive step-by-step visualization of Salat al-Khawf (the Fear Prayer) — how Muslims prayed in shifts during battle at Dhat al-Riqa (4 AH). Features animated canvas visualization and a quiz.

## Concept

Salat al-Khawf is mentioned in Quran 4:102. The army splits into two groups that take turns praying while the other guards against the enemy. This app teaches the complete process through 7 animated steps, then tests understanding with a 6-question quiz.

## The 7 Steps

| Step | What Happens |
|------|-------------|
| 1 | Army splits into Group A and Group B |
| 2 | Group A prays 1st rak'ah with Imam; Group B guards |
| 3 | Group A goes to guard; Group B comes to pray |
| 4 | Group B prays 1st rak'ah with Imam (his 2nd); Imam finishes |
| 5 | Group B completes 2nd rak'ah individually |
| 6 | Group A returns and completes 2nd rak'ah individually |
| 7 | Both groups have prayed fully; enemy was never unguarded |

## Quiz (6 Questions)

| # | Topic |
|---|-------|
| 1 | Number of groups |
| 2 | What the guarding group does |
| 3 | Quran verse reference (4:102) |
| 4 | Total rak'ahs per group |
| 5 | Origin of the name "Dhat al-Riqa" |
| 6 | Lesson about prayer's importance |

## Features

- Single HTML file, zero dependencies, fully offline
- Canvas-rendered animated visualization of prayer positions
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- High score persistence via localStorage
- Two-phase gameplay: Learn (7 steps) then Quiz (6 questions)

## Lesson

Prayer is so important in Islam that it is never abandoned — even on the battlefield. Allah provided Salat al-Khawf as a special method to maintain worship during danger. This shows that the connection to Allah takes priority over everything else.

## Technical

- **HS_KEY**: `wdiy-hs-dhat-al-riqa-fear-prayer`
- **Footer**: Workshop-Diy — Dhat al-Riqa Fear Prayer v1.0
- **Stack**: Single-file HTML + CSS + JS + Canvas, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
