# Data Folder

This folder contains the datasets used in the **FIFA Ranking Analysis and Modeling** project.

## Folder Structure
```text
data/
├── raw/
│ └── fifa_ranking.csv
│
└── processed/
├── dim_confederation.csv
├── dim_country.csv
├── dim_date.csv
└── fact_ranking.csv
```

## Data Source

The original dataset was downloaded from Kaggle:

🔗 [FIFA World Ranking Dataset – Kaggle](https://www.kaggle.com/datasets/cashncarry/fifaworldranking)

Original file: `fifa_ranking.csv`

---

## ETL Process Overview

1. **Extraction:**
   - Loaded the raw data from `fifa_ranking.csv`.

2. **Transformation:**
   - Cleaned missing and inconsistent values.
   - Standardized column names and date formats.
   - Removed duplicates.
   - Engineered additional features such as regional ranking and time-based statistics.

3. **Loading:**
   - Structured the transformed data into dimensional tables following a star schema:
     - `dim_confederation.csv` — Confederation dimension.
     - `dim_country.csv` — Country dimension.
     - `dim_date.csv` — Date dimension.
     - `fact_ranking.csv` — Fact table containing ranking metrics per country and date.

---

## Notes
- All ETL steps were implemented using **Python (Pandas)**.
- Processed data is ready for analysis, modeling, and dashboard visualization.

