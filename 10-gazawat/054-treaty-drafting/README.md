# Treaty Workshop

Interactive treaty drafting workshop for kids, inspired by historical Islamic diplomacy.

## Overview

Players read a historical scenario and draft treaty clauses by selecting options across six categories. Their treaty is then compared against the actual historical agreement and scored on fairness, completeness, and historical accuracy.

## Features

- **5 Scenarios** based on real treaties: Constitution of Medina, Treaty of Hudaybiyyah, Alliance of Banu Damra, Covenant with Christians of Najran, Post-Battle Peace Accord
- **6 Clause Categories**: Duration, Trade Terms, Military Terms, Prisoner Exchange, Sacred Months, Violation Consequences
- **Triple Scoring**: Fairness (balanced terms), Completeness (all clauses filled), Historical Accuracy (match to real treaty)
- **Educational Lessons**: Each scenario ends with a lesson about Islamic diplomacy and justice
- **8 Themes**: Terminal, Midnight, Ember, Arctic, Phosphor, Signal, Redshift, Sand
- **3 Languages**: English, French, Arabic (with RTL support)
- **Sound Effects**: Web Audio API, no external files
- **High Score**: Persisted via localStorage (`wdiy-hs-treaty`)
- **Preferences Persistence**: Theme, language, and sound settings saved locally
- **Sidebar Help**: FAQ, How-To, and Wiki tabs
- **Fully Offline**: Single HTML file, zero dependencies

## How to Play

1. Click **Start Mission** on the splash screen
2. Read the scenario describing the historical situation
3. Select one option per clause category (Duration, Trade, Military, Prisoners, Sacred Months, Consequences)
4. Click **Submit Treaty** to see your evaluation
5. Review the comparison against the historical treaty
6. Continue through all 5 scenarios
7. Aim for the highest average score

## Scoring

| Criteria | Description |
|---|---|
| Fairness | Are your chosen terms balanced for both parties? |
| Completeness | Did you address all six clause categories? |
| Historical Accuracy | How many of your choices match the real historical treaty? |

Final score is the average of all three criteria across all scenarios.

## Technical

- **HS_KEY**: `wdiy-hs-treaty`
- **Single file**: `index.html` — no build step, no dependencies
- **Offline-ready**: Works without internet after initial load
- **Template**: Follows Workshop-Diy standard template structure

## Lesson Themes

- Justice and balance in agreements
- Religious freedom and coexistence
- Patience and trust in Allah's plan
- Mercy toward prisoners and defeated parties
- Respect for sacred traditions
