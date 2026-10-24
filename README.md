# Datheon Machine Learning & Data Science Internship

## 📌 About This Repository

This repository showcases two hands-on Machine Learning projects completed as part of the **Datheon Machine Learning & Data Science Internship**. The projects demonstrate the application of supervised learning algorithms, data preprocessing, exploratory data analysis, model evaluation, and data visualization using Python.

The goal of this repository is to develop practical Machine Learning skills and build an understanding of how predictive models can solve classification and regression problems.

## 📂 Projects Overview

### 🌸 Project 1: Multi-Class Benchmark Classification Pipeline — Iris Dataset

**Objective:** Develop and compare Machine Learning classification models to identify Iris flower species using their physical measurements.

This project uses the Iris dataset, which contains flower measurements such as sepal length, sepal width, petal length, and petal width. The objective is to classify flowers into three species: Setosa, Versicolor, and Virginica.

**Key Features**
- Load and inspect the Iris dataset using Pandas.
- Perform Exploratory Data Analysis (EDA) using visualizations.
- Split the dataset into training and testing sets using stratified sampling.
- Standardize numerical features using `StandardScaler`.
- Train and compare Logistic Regression and Decision Tree classifiers.
- Evaluate model performance using accuracy, precision, recall, and F1-score.
- Visualize results using confusion matrices and Seaborn plots.

**Technologies Used**
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

**Project Folder:** `project1/`

### 🏠 Project 2: Real Estate House Price Prediction

**Objective:** Build a Machine Learning regression pipeline to predict median house values using the California Housing dataset.

This project explores housing-related features and applies multiple regression algorithms to estimate median house prices. It compares Ordinary Least Squares Linear Regression, Ridge Regression, and Lasso Regression to understand their predictive performance and the effects of regularization.

**Key Features**
- Load and explore the California Housing dataset.
- Perform Exploratory Data Analysis and visualize feature relationships.
- Handle missing numerical values and encode categorical features where applicable.
- Engineer household-level features.
- Investigate feature correlations and multicollinearity.
- Train and compare Linear Regression, Ridge Regression, and Lasso Regression.
- Tune Ridge and Lasso models using `GridSearchCV`.
- Evaluate predictions using RMSE, MAE, and R² score.
- Visualize actual versus predicted values and residual errors.
- Save the trained model pipeline and output visualizations.

**Technologies Used**
- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook
- Joblib

**Project Folder:** `project2/`

## 🛠️ Installation and Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ramavaishnavi55-glitch/Datheon_Machine_Learning_-_Data_Science_Internship.git
```

### 2. Navigate to the Repository

```bash
cd Datheon_Machine_Learning_-_Data_Science_Internship
```

### 3. Install the Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter joblib
```

### 4. Run the Projects

Open the repository in VS Code or Jupyter Notebook, navigate to the required project folder, and run the notebook cells in order.

Ensure that the required dataset files are available at the paths specified in the notebooks before running the projects.

## 📁 Repository Structure

```text
Datheon_Machine_Learning_-_Data_Science_Internship/
│
├── README.md
│
├── project1/
│   ├── README.md
│   ├── Multi_Class_Classifier.ipynb
│   ├── Multi_class_BenchMark_classification.py
│   └── iris.csv
│
└── project2/
    ├── README.md
    ├── house_price_prediction.ipynb
    ├── best_house_price_model.pkl
    ├── housing.csv
    ├── requirements.txt
    └── outputs/
```

*Note: The structure above summarizes the main project files; check each folder for the exact files currently committed.*

## 🎯 Skills Demonstrated

- Python programming for Machine Learning
- Data cleaning and preprocessing
- Exploratory Data Analysis
- Supervised learning: classification and regression
- Feature scaling and categorical encoding
- Model training and comparison
- Hyperparameter tuning
- Model evaluation and performance visualization
- Saving trained models
- Jupyter Notebook development
- Git and GitHub version control

## 📈 Learning Outcomes

These projects provide practical experience in building end-to-end Machine Learning workflows. The Iris classification project focuses on predicting categorical labels, while the house price prediction project focuses on estimating continuous numerical values.

Together, they demonstrate foundational skills in data analysis, predictive modeling, model evaluation, and reproducible project development.

## ⚠️ Limitations

- Model performance depends on the quality and characteristics of the datasets.
- Results should be interpreted using appropriate evaluation metrics rather than a single score.
- House price predictions are based on California census-block-group housing data and should not be treated as current valuations for individual properties.

## 🚀 Future Improvements

- Experiment with additional classification and regression algorithms.
- Improve model performance through systematic hyperparameter tuning.
- Add cross-validation and more detailed model comparisons.
- Build interactive interfaces for making predictions.
- Deploy trained models as simple web applications.

---

**Repository:** [Datheon Machine Learning & Data Science Internship](https://github.com/ramavaishnavi55-glitch/Datheon_Machine_Learning_-_Data_Science_Internship)
