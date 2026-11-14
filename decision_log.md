# Decision log

Every choice that affects the data, the metrics or what the dashboard shows. One row per decision. Add new rows at the bottom.

| # | Date | Phase | Decision | Reason | Impact |
|---|---|---|---|---|---|
| 1 | 2026-11-14 | 0 | Use Tableau Public as the only visualisation tool | Free; dashboard can be shared publicly with a link for recruiters | Dashboard and workbook are public; no Tableau Prep, so cleaning happens on the Data Source page and in calculated fields |
| 2 | 2026-11-14 | 0 | Project folder structure: `01_raw`, `02_clean`, `03_tableau`, `04_screenshots`, `05_writeup` | Keep raw data untouched and separate from outputs | Raw files can always be re-used to reproduce results |
| 3 | 2026-11-14 | 0 | Public GitHub repo `nhs-gp-missed-appointments`; raw NHS CSVs not uploaded | Files too large for GitHub; data is openly available from NHS England | README links to the NHS England source instead of hosting the data |
|   |  |  |  |  |  |

## How to write a good entry
- **Decision:** what you chose, specifically (e.g. "Exclude appointments with status Booked or Unknown from the DNA rate").
- **Reason:** why, ideally with a source or number (e.g. "NHS England notes 3–6% of appointments keep a final status of 'booked'").
- **Impact:** what changes as a result, with a count if you have one (e.g. "[X] appointments ([Y]%) excluded from the denominator").
