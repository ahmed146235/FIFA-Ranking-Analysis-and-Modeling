# FIFA Ranking Analysis and Modeling

A project analyzing FIFA World Rankings to provide insights on team performance, confederation trends, and historical ranking evolution. Includes a full ETL pipeline, dimensional modeling, and a Power BI dashboard.

---

## Project Structure
```text
FIFA-Ranking-Analysis-and-Modeling/
├── data/
│ ├── raw/fifa_ranking.csv
│ └── processed/
│ ├── dim_confederation.csv
│ ├── dim_country.csv
│ ├── dim_date.csv
│ └── fact_ranking.csv
├── notebooks/FIFA_Ranking_Analysis_and_Modeling.ipynb
├── dashboard/
│ ├── FIFA_Ranking_Dashboard.pbix
│ ├── Overview.png
│ └── Insights.png
└── README.md
```

---

## Data

- **Raw:** Original `fifa_ranking.csv`.
- **Processed:** Cleaned and transformed tables (`dim_confederation`, `dim_country`, `dim_date`, `fact_ranking`) following a star schema.
- **Source:** [Kaggle Notebook & Dataset](https://www.kaggle.com/code/ahmedmmmahmoud/fifa-ranking-anaylsis-and-modeling)

---

## Notebook

- Main Jupyter notebook implements the ETL pipeline: load → clean → feature engineering → dimensional modeling → export processed tables.
- Tools: Python (Pandas, NumPy, Matplotlib)
- Sequential execution ensures reproducibility.

---

## Dashboard

- **FIFA_Ranking_Dashboard.pbix:** Interactive Power BI dashboard connecting to processed data.
- **Overview.png / Insights.png:** Key snapshots of trends and insights.
- Open in Power BI Desktop, refresh data, explore visuals.

---

## Summary

This project demonstrates:

- Full data workflow: raw → processed → modeled
- Feature engineering for rankings and confederation analysis
- Interactive visual insights via Power BI

A practical example of combining Python ETL, dimensional modeling, and BI tools for sports analytics.
