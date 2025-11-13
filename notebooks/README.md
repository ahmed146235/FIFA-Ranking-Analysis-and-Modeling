# Notebooks Folder

This folder contains the main Jupyter notebook used for the **FIFA Ranking Analysis and Modeling** project.

## File Structure
```text
notebooks/
└── FIFA_Ranking_Analysis_and_Modeling.ipynb
```

## Notebook Overview

The notebook follows a structured data engineering and analysis workflow that includes reading, preprocessing, transformation, and modeling of the FIFA World Ranking dataset.

### Table of Contents

1. **Getting Data and Reading**  
   - Loads the original dataset (`fifa_ranking.csv`) from `data/raw/`.  
   - Displays dataset structure, shape, and sample records.

2. **Preprocessing of Data and Cleaning**
   - **2.1 Info and Describe:**  
     Reviews data types, null values, and statistical summaries.  
   - **2.2 Data Cleaning:**  
     Handles missing values, removes duplicates, and standardizes column names and formats.

3. **Data Transformation and Feature Engineering**
   - **3.1 Create Additional Columns:**  
     Generates new variables such as rank change, confederation-based averages, and date-based metrics.

4. **Splitting the Dataset into Fact and Dimension Tables**
   - **4.1 Dimensions Tables:**  
     Builds `dim_country`, `dim_confederation`, and `dim_date` dimension tables.  
   - **4.2 Fact Table:**  
     Constructs `fact_ranking` with ranking metrics and foreign keys to dimension tables.  
   - **4.3 Saving Tables:**  
     Exports all processed tables to `data/processed/`.

---

## Notes
- Implemented entirely in **Python 3.10+** using **Pandas**, **NumPy**, and **Matplotlib**.  
- The notebook demonstrates the complete ETL (Extract, Transform, Load) process.  
- Run sequentially from top to bottom for a reproducible data pipeline.
