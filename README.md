# MicroFinCo ISO 27001 Compliance Dashboard

A static dashboard showing ISO 27001 control coverage and a risk heat map for the fictional company MicroFinCo.

**Live dashboard:** https://aleezakhannn.github.io/microfinco-dashboard/

## Usage

- Open the link above. No install needed.
- The page reads the gap analysis and risk register CSV files from GitHub on every load, so the charts update when those files change (GitHub may cache raw files for a few minutes).
- **Bar chart:** number of controls that are Implemented, Partial, and Not.
- **Heat map:** risks placed by impact and likelihood, coloured green (low) to red (high).
- Summary cards and a Top Risks table sit alongside the charts.

## Files

- `index.html`: page, styling, and script (commented)

## Data Sources

- [Gap analysis CSV](https://github.com/aleezakhannn/ISO27001-gap-analysis/blob/main/iso27001_gap_analysis.csv)
- [Risk register CSV](https://github.com/aleezakhannn/Microfinco-risk-resgister/blob/main/risk_register.csv)

Training exercise only. All data is fictional.