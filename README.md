# Task 10 – Python EDA & Outlier Detection

## Objective
To perform Exploratory Data Analysis (EDA) on a Credit Card Fraud dataset and identify & handle outliers using Python.

---

## Tools & Libraries Used
- Google Colab
- Python
- pandas
- numpy
- matplotlib

---

## Dataset
Credit Card Fraud dataset (CSV format)

---

## Steps Performed

1. Loaded the dataset and checked shape, head, and data types.
2. Performed basic data inspection using `.info()` and `.describe()`.
3. Calculated missing value percentages for all columns.
4. Visualized transaction amount distribution using:
   - Histogram
   - Boxplot
5. Detected outliers using the **IQR (Interquartile Range) method**.
6. Created an outlier flag column.
7. Removed extreme outliers to improve data quality.
8. Performed correlation analysis on numerical features.
9. Exported the cleaned dataset for further use.

---

## Key Findings
- Transaction Amount column was right-skewed.
- Outliers were present and detected using IQR.
- Removing outliers helped reduce skewness.
- Correlation analysis showed weak to moderate relationships.

---

## Files in Repository
- `task10_eda.ipynb` → Google Colab notebook with complete EDA
- `cleaned_dataset.csv` → Dataset after outlier removal
- `eda_findings.txt` → Summary of observations

---

## ✅ Outcome
This task helped in understanding real-world data, handling outliers, and performing structured EDA using Python.
