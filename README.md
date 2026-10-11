# DATA 608 Fall 2026 - Story 3: Why do road deaths differ so much between states?

Quarto report (R) for CUNY SPS DATA 608, Data Story 3.

- `story3.qmd` - report source; reads the data directly from this repo's `data/` folder
- `story3.pdf` - rendered report
- `data/state_master_2024.csv` - IIHS Fatality Facts 2024 state overview (course dataset)
- `data/ems_response_by_state_2023_2024.csv` - FARS 2023-24 EMS response summary (course dataset)

## Render

Requires R with tidyverse, ggrepel, scales, maps and mapproj, plus Quarto. Run `quarto render story3.qmd` (needs internet, since the data is read from GitHub).
