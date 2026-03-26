# Plan: Islamic Kids Apps — Full Redesign + Deep Arabic

## Current State
- **725 apps** across 16 categories, all self-contained single HTML files
- **Arabic translation: ~70% broken** — language switcher exists but most apps have no i18n data
- **Design: cloned** — same splash screen, same layout, same buttons across all apps
- Each app is ~30-60KB inline HTML/CSS/JS, no shared templates

## TWO PARALLEL GOALS

### Goal 1: Deep Arabic Translation (all 725 apps)
Every app must have:
1. `const I18N = { ar: {...}, en: {...} }` with ALL strings translated
2. All educational DATA in Arabic (questions, answers, explanations, stories)
3. Help sidebar fully in Arabic
4. Splash screen title + subtitle in Arabic
5. All buttons, labels, status messages in Arabic
6. Arabic as default language on load
7. Proper Islamic terminology (not Google Translate)

### Goal 2: Unique Design DNA (all 725 apps)
Each CATEGORY gets a unique visual identity:
- **01-quran**: Gold calligraphy on deep blue, Quran page borders, mushaf style
- **02-arabic**: Ink/paper classroom style, chalkboard elements
- **03-seerah**: Desert sand + caravan journey style, parchment maps
- **04-hadith**: Library/manuscript aesthetic, hadith scroll cards
- **05-dua**: Soft sky gradients, prayer mat textures, moon/stars
- **06-fiqh**: Geometric Islamic patterns, green mosque theme
- **07-aqeedah**: Cosmic/celestial, deep purple/gold, stars
- **08-adab**: Garden/nature, warm earth tones, floral arabesque
- **09-history**: Timeline/chronicle, ancient map textures, sepia
- **10-gazawat**: Desert battlefield, shield/sword motifs, sand/bronze
- **11-anbiya**: Story book style, illustration borders, warm pastels
- **12-scientists**: Laboratory + Islamic geometry, blueprint style
- **13-sahaba**: Companion cards, badge/medal style, noble gold
- **14-tafsir**: Mushaf-inspired, word-by-word highlight, deep green
- **15-life-tools**: Modern Islamic dashboard, clean/minimal, teal
- **16-arabic-immersion**: Souk/market colorful, Arabic signage style

Each APP within a category gets subtle variations (different accent colors, layouts).

### Design Requirements
- Boys-friendly, kid-appealing, stylish
- Islamic calligraphy fonts (Amiri, Scheherazade, Noto Naskh Arabic)
- Real Islamic geometric patterns in CSS
- Unique splash screens per app (not cloned)
- Unique app layouts (sidebar, controls, game area all different)
- Smooth animations, engaging micro-interactions
- RTL-first design

## Execution Order (by category)
1. 01-quran (50 apps)
2. 02-arabic (40 apps)
3. 03-seerah (50 apps)
4. 04-hadith (35 apps)
5. 05-dua (35 apps)
6. 06-fiqh (50 apps)
7. 07-aqeedah (35 apps)
8. 08-adab (45 apps)
9. 09-history (45 apps)
10. 10-gazawat (110 apps)
11. 11-anbiya (50 apps)
12. 12-scientists (40 apps)
13. 13-sahaba (40 apps)
14. 14-tafsir (30 apps)
15. 15-life-tools (35 apps)
16. 16-arabic-immersion (35 apps)

## Per App Changes
For EACH of the 725 apps:
1. Replace splash screen with category-unique design
2. Replace app layout with category-unique design
3. Add/fix full I18N object with deep Arabic translations
4. Translate all educational content to Arabic
5. Set Arabic as default language
6. Add Islamic calligraphy fonts
7. Add CSS geometric patterns unique to category
8. Update help sidebar in Arabic
9. Keep English as secondary language option

## Estimated Scope
- 725 files to edit
- Each file needs full CSS redesign + full Arabic i18n
- Autonomous execution, category by category
