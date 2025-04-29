# Food Inspection Data Analysis Project

## Project Overview
This project focuses on exploring and cleaning food inspection data collected from various establishments.  
The goal is to prepare a clean and reliable dataset that can be used to extract insights related to health inspections, violations, and overall establishment compliance.

We use **Python** and **Pandas** for data loading, exploration, cleaning, and preparation for further analysis.

---

## Problem Statement
Food safety inspections are critical for protecting public health. However, raw inspection data often contains missing values, duplicate records, and inconsistent entries, which can hinder effective analysis.  
The main problem addressed in this project is cleaning and preparing the inspection data to ensure it is suitable for deriving meaningful insights about the compliance of different establishments.

---

## Hypothesis
We hypothesize that:
- Certain types of establishments (e.g., restaurants, food courts) have higher violation rates compared to others (e.g., schools, hospitals).
- Violations may cluster around specific time periods or geographical areas.
- Proper data cleaning will reveal clearer patterns and allow for better predictive modeling in future analysis phases.

---

## Project Scope
- Focus on cleaning inspection records for missing values, duplicates, and inconsistencies.
- Standardize establishment-related fields for better categorization.
- Prepare the dataset for subsequent exploratory data analysis (EDA) and visualization.
- No advanced modeling (e.g., machine learning) is performed in this phase; the primary focus is data readiness.

---

## Goals
- Understand the structure and quality of the inspection dataset.
- Identify missing values and inconsistent entries.
- Remove duplicate records to ensure data accuracy.
- Standardize the data for further exploratory data analysis (EDA).

---

## Tools and Technologies
- **Python 3.x**
- **Pandas**
- **Jupyter Notebook**
- **Visual Studio Code**

---

## Key Steps
1. **Data Loading:**  
   Import the inspection dataset into a Pandas DataFrame.

2. **Initial Data Exploration:**  
   Use `.info()`, `.head()`, `.describe()` to explore column types, sample rows, and basic statistics.

3. **Missing Values Handling:**  
   Analyze missing data patterns using `.isna().sum()`, and apply strategies to fill or remove missing entries as appropriate.

4. **Duplicate Records Removal:**  
   Detect duplicate inspections (using `Inspection ID` or other relevant identifiers) and remove them using `.drop_duplicates()`.

5. **Data Cleaning:**  
   - Standardize establishment names if necessary.
   - Correct inconsistent values.
   - Adjust data types (e.g., dates, numeric columns).

6. **Saving the Cleaned Dataset:**  
   Export the cleaned version to a new CSV file, ready for detailed analysis and visualization.

---

## How to Run the Project
1. Clone the repository or download the project files.
2. Open the Jupyter Notebook related to this project.
3. Run the notebook cells sequentially to follow the cleaning process.
4. Review the final cleaned dataset and use it for further analysis or modeling.

---

## Notes
- Maintaining a copy of the original raw data is important before applying cleaning operations.
- Each step of the cleaning process is clearly documented within the notebook to ensure reproducibility.

---

## Author
Hazem Sulaiman
