# Satellite Launch Trends – Payload to Orbit

Analysis of satellite launch activity using the **UCS Satellite Database** (May 2023 version, 7,560 entries).

## What it shows

- Annual number of satellites launched (1990s → 2022/23)
- Total payload mass to orbit per year (million kg, with simple imputation for missing masses)
- Breakdown of launches by orbit class (LEO, GEO, MEO, Elliptical)
- Comparison of trends with vs. without mass imputation

## Key insights

- Explosive growth in satellite count since ~2018 (mostly small LEO constellations)
- Payload mass grows more slowly → many new satellites are small (<600 kg)
- LEO dominates recent activity

## Requirements

```bash
pip install pandas matplotlib seaborn numpy openpyxl
