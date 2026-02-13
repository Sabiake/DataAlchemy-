**DataAlchemy**

Transforming messy data into meaningful business and research insights—turning raw datasets into clean, actionable analyses ready for real-world impact.
This repository is a curated collection of data analysis projects, showcasing workflows from raw data to clean, analysis-ready datasets with business-relevant insights.

🛠 Tech Stack
Python: pandas, numpy
Excel / Google Sheets
Jupyter Notebooks
Data Visualization: matplotlib, seaborn, plotly, Power BI
Version Control: Git & GitHub

| Project                 | Description                                                        | Raw Dataset               | Cleaned Dataset               | Key Insights                                                       |
| ----------------------- | ------------------------------------------------------------------ | ------------------------- | ----------------------------- | ------------------------------------------------------------------ |
| Inventory Data Cleaning | Standardized product data, resolved duplicates, normalized formats | `messy_warehouse_data.csv` | `cleaned_warehouse_data.csv` | Dataset ready for reporting, dashboarding, and predictive modeling |
| *Upcoming Project*      | Short description                                                  | Link                      | Link                          | Summary of insights                                                |


**Inventory Data Cleaning: Before vs After**
🔍 Initial Data Audit & Key Issues

1. Text & Categorical Fields: Inconsistent naming, casing, and whitespace → unreliable grouping and pivot tables.
2. Quantity Column: Mixed types, text numerics, missing values → numeric aggregation errors.
3. Price Column: Missing values, text formatting → revenue calculations distorted.
4. Date Column: Mixed formats and text dates → time-based analysis blocked.
5. Duplicates: Repeated Product IDs → violates entity uniqueness, inflates counts.

✅ Cleaning Approach & Actions
1. Text Normalization: Trim whitespace, unify capitalization, standardize names → reliable grouping.
2. Quantity Column: Convert to numeric, median imputation → aggregation-safe.
3. Price Column: Numeric coercion, median imputation → accurate financial metrics.
4. Date Column: Convert text to consistent date format → time-series analysis enabled.
5. Duplicates: Detect and remove invalid duplicates → maintain referential integrity.

📈 Final Dataset Improvements
1. Numeric fields strictly numeric, no "NaN" text values
2. Standardized categorical fields
3. Dates fully normalized
4. Missing data handled strategically
5. Logical validation checks applied
6. Structured as Excel Table for scalability
Outcome: Dataset is now ready for EDA, dashboarding (Power BI/Tableau), SQL imports, and predictive modeling.

🎯 Skills Demonstrated
1. Data auditing & quality assessment
2. Data type coercion & validation
3. Median-based imputation strategy
4. Text normalization & categorical standardization
5. Date normalization & validation logic
6. Duplicate detection & entity integrity validation
7. Analytical thinking applied to business data

Reflection: Data cleaning is analytical decision-making. Each transformation considered business meaning, statistical impact, and downstream effects to ensure accurate, actionable insights
