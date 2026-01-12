# Aadhaar Societal Trends Analysis (2025 Data)

UIDAI Data Hackathon 2026 – Final Submission

## Overview

This project analyses UIDAI’s Aadhaar enrolment, demographic update, and biometric update datasets to understand how the Aadhaar ecosystem functions after reaching near-universal coverage. The focus is on identifying societal trends and system-level service pressure by studying update behaviour rather than only new enrolments.

The analysis highlights how Aadhaar usage has shifted from registration-driven activity to lifecycle maintenance, with biometric and demographic updates forming the majority of transactions.

---

## Project Structure

/notebooks
Contains the primary Jupyter Notebook used for data loading, preprocessing, analysis, and visualisation.

/results
Includes all generated charts and figures used in the final hackathon report.

/scripts
Helper Python scripts for data cleaning, aggregation, and preprocessing.

/data
Directory expected to contain the raw UIDAI CSV datasets.
(Note: Raw Aadhaar datasets are not included in this repository.)

---

## Key Findings

* Aadhaar updates significantly exceed new enrolments, confirming system maturity and a shift toward record maintenance.
* Approximately 76 percent of new enrolments belong to the 0–17 age group, indicating that Aadhaar enrolment is now primarily driven by minors.
* Biometric updates form the largest share of Aadhaar transactions, with a clear surge during the last quarter of the year (Q4), suggesting seasonal and compliance-driven demand.

---

## Methodology Summary

* Multiple UIDAI CSV files were consolidated and processed using Python.
* Date fields were standardised and converted into monthly periods for time-series analysis.
* Data was aggregated at the state and month level to balance scale and interpretability.
* Derived metrics such as total transactions and update-to-enrolment ratios were used to assess system maturity and service load.
* Visualisations were generated to highlight temporal, demographic, and regional patterns.

---

## Tech Stack

Python
Pandas
Matplotlib
Seaborn
Jupyter Notebook

---

## How to Run the Analysis

1. Place all UIDAI Aadhaar CSV files inside the `/data` directory.
2. Open the notebook `Aadhaar_Analysis_2025.ipynb` from the `/notebooks` folder.
3. Run the notebook cells sequentially from top to bottom.
4. Generated charts and outputs will be saved automatically in the `/results` directory.

---

## Reproducibility Note

All analysis steps, transformations, and visualisations used in the UIDAI Hackathon submission are documented within the notebook. The results can be fully reproduced using the same datasets provided by UIDAI.

---

## Author

Manvendra Rai

---

