# Tajweed Rules

**Master the rules of Quran recitation**

An interactive single-file HTML game for Muslim kids to learn and practice tajweed rules. Identify which tajweed rule applies to highlighted text in Quran verse snippets.

## Features

- **16 tajweed rules** across 6 categories with 60+ question variants
- **3 difficulty levels**: Easy (5 rules), Medium (10 rules), Hard (15+ rules)
- **Trilingual**: English, French, Arabic (with RTL support)
- **8 CSS themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **Explanation after each answer** showing the rule name (EN/FR/AR) and description
- **High score** persistence via localStorage
- **Sound effects** via Web Audio API (no files needed)
- **Keyboard shortcuts**: 1-4 for answer choices, Enter to start
- **Sidebar help** with FAQ, How-To, and Wiki tabs
- **Offline**: zero dependencies, single HTML file

## Tajweed Rules Covered

### Noon Sakinah & Tanween
| Rule | Arabic | Description |
|------|--------|-------------|
| Izhar | إظهار | Clear pronunciation before throat letters |
| Idgham with Ghunnah | إدغام بغنة | Merge with nasalization before ي ن م و |
| Idgham without Ghunnah | إدغام بلا غنة | Merge without nasalization before ل ر |
| Iqlab | إقلاب | Conversion to meem before ب |
| Ikhfa | إخفاء | Hidden nasalization before 15 letters |

### Meem Sakinah
| Rule | Arabic | Description |
|------|--------|-------------|
| Ikhfa Shafawi | إخفاء شفوي | Lip hiding before ب |
| Idgham Shafawi | إدغام شفوي | Lip merge with م |
| Izhar Shafawi | إظهار شفوي | Clear before all other letters |

### Madd (Elongation)
| Rule | Arabic | Description |
|------|--------|-------------|
| Madd Tabii | مد طبيعي | Natural 2-count elongation |
| Madd Muttasil | مد متصل | Connected 4-5 counts (hamzah in same word) |
| Madd Munfasil | مد منفصل | Separated 4-5 counts (hamzah in next word) |
| Madd Lazim | مد لازم | Obligatory 6 counts |

### Other Rules
| Rule | Arabic | Description |
|------|--------|-------------|
| Qalqalah | قلقلة | Echoing on letters ق ط ب ج د |
| Ghunnah | غنة | Nasalization on noon/meem with shaddah |
| Lam Shamsiyyah | لام شمسية | Silent lam before sun letters |
| Lam Qamariyyah | لام قمرية | Pronounced lam before moon letters |

## Tech

- Single HTML file, zero external dependencies (fonts loaded from Google Fonts for aesthetics but not required)
- Web Audio API for sound effects
- localStorage for preferences and high scores
- Pure vanilla JS, no frameworks

## Storage Keys

| Key | Purpose |
|-----|---------|
| `wdiy-hs-tajweed-rules` | High score (percentage) |
| `wdiy-lang` | Language preference |
| `wdiy-theme` | Theme preference |
| `wdiy-mute` | Sound mute state |

---

Workshop-Diy — Tajweed Rules v1.0
