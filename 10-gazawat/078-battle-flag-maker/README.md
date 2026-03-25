# Battle Flag Maker

Interactive creative tool where kids design battle flags and banners with Islamic calligraphy, colors, patterns, and symbols using a canvas-based editor.

## Concept

The Prophet (peace be upon him) had two main banners: Al-Liwa (white banner) and Ar-Raya (black standard). Islamic banners often featured calligraphy and served as rallying points during battles. Players design their own banners, learning about the role of flags in Islamic military history.

## Gameplay

1. Choose a background color from 8 historical options
2. Select a text color for contrast
3. Pick a pattern: solid, horizontal stripes, vertical stripes, border, diamond, or cross
4. Choose Arabic calligraphy text (shahada, takbir, etc.)
5. Add a symbol (star, crescent, sword, flag, or none)
6. The canvas updates live with each choice
7. Complete the flag to earn a design score

## Design Options

| Category | Options |
|----------|---------|
| Colors | Black, White, Green, Red, Blue, Gold, Purple, Brown |
| Patterns | Solid, H-Stripes, V-Stripes, Border, Diamond, Cross |
| Calligraphy | La ilaha illallah, Allahu Akbar, Nasr min Allah, Ya Rabb |
| Symbols | Star, Crescent, Swords, Flag |

## Features

- Single HTML file, zero dependencies, fully offline
- 8 CSS themes: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- Trilingual: English, French, Arabic (with RTL support)
- Splash screen with Bismillah
- Sidebar help panel with FAQ, How-To, and Wiki tabs
- Web Audio API sound effects (no audio files)
- Live canvas rendering with HTML5 Canvas API
- Multiple design customization options
- Arabic calligraphy rendering with Noto Sans Arabic
- High score persistence via localStorage

## Lesson

Identity and symbols in Islam: Banners served practical military purposes as rallying points and communication tools. The Islamic tradition of calligraphy on banners reflects the central role of the Word of Allah in Muslim identity.

## Technical

- **HS_KEY**: `wdiy-hs-battle-flag-maker`
- **Footer**: Workshop-Diy — Battle Flag Maker v1.0
- **Stack**: Single-file HTML + CSS + JS, Google Fonts (Outfit, IBM Plex Mono, Noto Sans Arabic)
