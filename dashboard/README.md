# Dashboard Folder

This folder contains the **Power BI Dashboard** for the **FIFA Ranking Analysis and Modeling** project.

The dashboard provides an interactive overview of FIFA team rankings, confederation performance, and analytical insights derived from the processed datasets.

## Folder Structure
```text
dashboard/
├── FIFA_Ranking_Dashboard.pbix
├── Overview.png
├── Insights.png
└── README.md
```

## Dashboard Description

- **FIFA_Ranking_Dashboard.pbix**  
  The main Power BI file containing all data visualizations and interactive reports.  
  It connects to the processed data from `data/processed/`.

- **Overview.png**  
  A snapshot of the dashboard’s main page showing global FIFA ranking trends and key indicators.

- **Insights.png**  
  A snapshot focusing on deeper insights — such as performance by confederation, ranking evolution, and model-based comparisons.

## How to Use

1. Open the file `FIFA_Ranking_Dashboard.pbix` in **Microsoft Power BI Desktop**.  
2. Make sure the paths to the processed CSV files (in `data/processed/`) are correctly set.  
3. Refresh the data source to load the latest processed data.  
4. Explore the visuals interactively.

## Notes
- The dashboard was created using the cleaned and transformed data generated from the main notebook (`FIFA_Ranking_Analysis_and_Modeling.ipynb`).  
- The included images (`Overview.png`, `Insights.png`) serve as quick previews of the dashboard’s key sections.
