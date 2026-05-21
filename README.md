# ISU Figure Skating Scoring Data (2024–25 Grand Prix Season)

Judge-level scoring data extracted from official ISU protocol PDFs for the 2024–25 Grand Prix season, structured to match the BuzzFeed News dataset schema.

## Source

Protocol PDFs downloaded from https://results.isu.org

## Extraction

Data was extracted using Python with pdfplumber, following the same CSV structure as the BuzzFeed News 2016–17 dataset (https://github.com/BuzzFeedNews/figure-skating-scores).

## Contents

| File | Description | Size |
|------|-------------|------|
| `judge-country_2425.csv` | Judge nationality for each panel | 16 KB |
| `judged-aspects_2425.csv` | Individual judge scores per aspect | 364 KB |
| `judge-scores_2425.csv` | Raw judge score entries | 997 KB |
| `performances_2425.csv` | Performance-level metadata | 67 KB |

Total: 57,321 judge-skater score entries from 7 Grand Prix competitions.
