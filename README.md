# maternal-mortality-africa-dashboard
Power BI analysis of maternal mortality trends across 7 African countries (2018-2023), examining why Nigeria remains an outlier despite regional and income-peer comparisons.

## Overview

Maternal mortality — deaths per 100,000 live births from pregnancy or childbirth-related causes — is one of the clearest signals of how well a country's health system supports women. This project compares MMR trends, income groups, and regional benchmarks across Angola, Egypt, Ethiopia, Ghana, Kenya, Nigeria, and South Africa between 2018 and 2023, to understand not just *what* changed, but *why*.

## Research Questions

1. How did MMR change for each of the 7 countries between 2018 and 2023?
2. Is there a relationship between income group and maternal mortality outcomes?
3. How does Nigeria's MMR compare to the Sub-Saharan Africa regional average and to its income-level peers?
4. Which country improved the most (or least), and what does that suggest about what's driving change?

## Data Source

World Bank Maternal Mortality Ratio data (indicator `SH.STA.MMRT`), narrowed to 2018-2023 for 7 countries.

## Tools

- **Power Query** — data cleaning and unpivoting (wide year-columns → long format)
- **Power BI** — DAX measures, filters, and visualization
- **PowerPoint** — summary deck

## Key Findings

- Every country studied improved between 2018 and 2023 — but at very different rates (Ethiopia: -34.3% vs. South Africa: -7.8%).
- Income classification alone does not explain outcomes: Nigeria and Egypt share the same "lower-middle-income" status, yet their MMRs differ by 58x.
- Nigeria's 2023 MMR (993) is more than 3x both the Sub-Saharan Africa regional average (312) and its own income-peer average (315.2).
- Faster improvement isn't tied to having more resources — Ethiopia (low income) improved nearly 3x faster than Nigeria (lower-middle income).

## Dashboard Preview

![Trend Overview](trend-overview.png)


![Nigeria Deep Dive](nigeria-deep-dive.png)



## Files in This Repo

| File | Description |
|---|---|
| `Slides_Maternal_Mortality.pptx` | Full summary deck |
| `trend-overview.png` | Page 1 of the Power BI dashboard |
| `nigeria-deep-dive.png` | Page 2 of the Power BI dashboard |
| `Capstone_Maternal_Mortality.pbix` | Full interactive Power BI report file |

## Author

**Mercy Dalhatu**
Data Analyst | Health Data Analytics
