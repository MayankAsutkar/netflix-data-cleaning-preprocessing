# Netflix Data Cleaning and Preprocessing

## Overview

This project demonstrates a complete data cleaning and preprocessing workflow on the Netflix Movies & TV Shows dataset using Python and Pandas. The objective is to improve data quality by handling missing values, correcting inconsistent records, removing duplicate entries, converting data types, and performing feature engineering. The cleaned dataset is suitable for further exploratory data analysis (EDA), visualization, and machine learning applications.

---

## Dataset

* **Dataset:** Netflix Movies & TV Shows
* **Source:** Kaggle
* **Records:** Approximately 8,800
* **Features:** 12

---

## Objectives

* Inspect and understand the dataset
* Handle missing values using appropriate strategies
* Correct inconsistent and invalid records
* Remove duplicate observations
* Convert data into appropriate formats
* Engineer additional features for future analysis
* Export a clean and analysis-ready dataset

---

## Data Cleaning and Preprocessing

The following preprocessing steps were performed:

* Examined dataset structure and summary statistics.
* Identified and handled missing values.
* Corrected records where movie durations were incorrectly stored in the `rating` column.
* Imputed missing `country` values using a hierarchical approach:

  * Director
  * Cast
  * Unknown
* Filled missing values in `director` and `cast`.
* Converted the `date_added` column to datetime format.
* Removed duplicate records.
* Performed feature engineering.
* Exported the cleaned dataset as a CSV file.

---

## Feature Engineering

The following features were created:

* Year Added
* Month Added
* Content Age
* Duration (Numeric)

---

---

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

---

## Output

The project produces a cleaned and preprocessed dataset that can be used for:

* Exploratory Data Analysis (EDA)
* Data Visualization
* Machine Learning
* Statistical Analysis

---

## Future Work

* Perform comprehensive exploratory data analysis
* Build interactive dashboards
* Develop recommendation systems
* Train machine learning models using the cleaned dataset

---

## Author

**Mayank Asutkar**
