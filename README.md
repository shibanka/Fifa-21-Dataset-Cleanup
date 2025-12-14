**⚽ FIFA 21 Data Cleaning Project**

📌 Project Summary

This repository contains a data cleaning project focused on the raw FIFA 21 dataset. The goal was to transform a highly messy dataset—featuring inconsistent units, complex string formats, and currency codes—into a clean, structured, and analysis-ready format using Python and Pandas.

🛠️ Key Technologies

Language: Python

Libraries: Pandas, NumPy

Environment: Jupyter Notebook / Jupyter Lab

**🧹 Data Cleaning Highlights**

The cleaning process involved resolving complex issues critical for a Data Analyst role:

**Unit Standardization:**

- Converted player Height (from formats like 5'7" and 170cm) to a standard metric (cm).

- Converted player Weight (from formats like 150lbs and 75kg) to a standard metric (kg).

**Currency Conversion:**

- Cleaned monetary columns (Value, Wage, Release Clause) by removing the € symbol and scaling 'M' (Million) and 'K' (Thousand) text values into absolute numeric values.

**String Parsing & Structuring:**

- Parsed the messy Team & Contract column to extract distinct Team names and separate Contract Start and Contract End years.

- Cleaned and converted star ratings (W/F, SM, IR) from strings (e.g., 4 ★) to integers.

**Type Conversion:**

- Converted the Hits column and all calculated monetary columns to appropriate numeric data types (float or int).

- Converted the Joined column to a standard datetime object.

**📁 Repository Contents**

## 📁 Repository Contents

* [`fifa_cleaning.ipynb`](fifa_cleaning.ipynb): The complete Python cleaning script used in the project.

* [`fifa21_raw_data.csv`](fifa21_raw_data.csv): The original, raw dataset.

* [`fifa21_cleaned_data.csv`](fifa21_cleaned_data.csv): The final, analysis-ready dataset.
