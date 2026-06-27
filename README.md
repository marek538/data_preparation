# Data Cleaning & Wrangling: The Met Museum Dataset

## Project Description
A comprehensive data preprocessing and data quality analysis project using "The Metropolitan Museum of Art Open Access" dataset. The primary focus is on transforming raw, inconsistent, and messy real-world data into a clean, structured format ready for Big Data analysis or Machine Learning pipelines.
Main focus of the task is to get used with large datasets

## Key Operations & Methodology
* **Data Consistency Checks:** Identified and analyzed structural inconsistencies across key features (e.g., `Object Name`), proposing robust cleaning strategies.
* **Data Integrity Verification:** Validated logical relationships between different columns to detect missing, corrupted, or logically impossible data entries.
* **Memory & Type Optimization:** Systematically casted raw string columns into optimal data types (Categorical, Numeric, Boolean, Datetime, and String) to significantly reduce memory footprint and improve processing speed.
* **Handling Missing Values (NaN):** Analyzed the distribution of missing data (e.g., in dimension features like `Dim1_cm`) to determine appropriate imputation or dropping strategies.

# Advanced Feature Engineering & Dimensionality Reduction

## Project Description
A comprehensive machine learning pipeline focused on the critical steps of data preprocessing for binary classification. This project tackles common real-world data challenges: handling imbalanced datasets, transforming skewed features, and reducing high-dimensional spaces to optimize model performance.

## Key Operations & Methodology
* **Data Balancing:** Applied strategies to mitigate class imbalance, ensuring the classification model does not become biased toward the majority class.
* **Feature Transformation & Binning:** Processed continuous variables by grouping them into categorical bins (e.g., `xcalc_bin` features) to handle outliers, capture non-linear relationships, and improve model robustness.
* **Dimensionality Reduction (PCA):** Implemented Principal Component Analysis (PCA) to project high-dimensional data into a lower-dimensional space, removing noise and computational overhead while preserving the maximum possible variance.
* **Pipeline Optimization:** Systematically evaluated how different preprocessing techniques (transformations vs. raw data) impact the final classification metrics.
