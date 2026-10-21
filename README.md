# Fitbit Sleep Data Analysis

## Project Overview

This project documents the cleaning and transformation of Fitbit sleep data using Python and pandas. It supports the sleep-related analysis and visualizations in my Bellabeat Smart Device Usage Analysis capstone, completed as part of the Google Data Analytics Professional Certificate.

## Data Preparation

The analysis uses two CSV exports containing minute-level Fitbit sleep records. The notebook:

- Inspects the original data for missing values and duplicate records.
- Investigates duplicate observations within and between the two exports.
- Combines the exports and removes 4,300 exact duplicate records.
- Reconstructs individual sleep sessions from minute-level observations.
- Prepares unique participant-date records for use in the capstone analysis.
- Exports sleep-session data to Excel for a sleep-duration histogram.

## Repository Contents

- `Fitbit_Sleep_Analysis.ipynb` — Python notebook containing the data preparation process and outputs.
- `data/minuteSleep3_merged.csv` — Original Fitbit sleep export.
- `data/minuteSleep4_merged.csv` — Original Fitbit sleep export.

## Reproducing the Analysis

Download the notebook and the `data` folder, keeping the same folder structure. Open the notebook in Jupyter and run all cells in order. The analysis uses Python, pandas, and Excel export support through openpyxl.

## Generative AI Disclosure

ChatGPT was used extensively as a learning, coding, troubleshooting, and documentation assistant. The author directed the analytical process, evaluated and verified the code and results, and made the final decisions regarding data preparation, interpretation, and presentation.
