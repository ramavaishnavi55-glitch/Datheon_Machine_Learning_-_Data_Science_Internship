# Multi-Class Benchmark Classification Pipeline (Iris Dataset)

An end-to-end machine learning classification pipeline built using Python, Scikit-learn, Pandas, and Seaborn to classify flower species based on physical sepal and petal measurements.

## Project Overview

This project implements and compares supervised classification models on the benchmark Iris dataset. It covers the complete machine learning lifecycle, from exploratory data analysis and feature scaling to model training, performance evaluation, and confusion matrix visualization.

## Key Features & Workflow

1. **Data Loading & Inspection:** Loaded tabular iris records via Pandas, verifying data types, column integrity, and complete absence of missing values.
2. **Exploratory Data Analysis (EDA):** Visualized feature distributions and inter-class correlations using Seaborn pairplots.
3. **Data Preprocessing & Splitting:** 
   * Separated features (`X`) and target labels (`y`).
   * Performed an 80/20 train-test split using stratified sampling.
   * Applied `StandardScaler` to standardize feature scales and prevent data leakage.
4. **Model Training:** Trained and optimized two distinct classifiers:
   * **Logistic Regression:** A linear model well-suited for well-separated classes.
   * **Decision Tree Classifier:** A non-linear, tree-based model utilizing hierarchical split rules.
5. **Model Evaluation & Benchmarking:** Evaluated performance metrics including accuracy, precision, recall, and F1-score via classification reports and comparative confusion matrix heatmaps.

## Technologies Used

* **Python 3.x**
* **Scikit-Learn:** For data preprocessing, model training, and performance metrics.
* **Pandas & NumPy:** For data manipulation and numerical operations.
* **Matplotlib & Seaborn:** For exploratory pairplots and confusion matrix visualizations.

## How to Run

1. Open Jupyter Notebook in your project directory:
   ```bash
   jupyter notebook
