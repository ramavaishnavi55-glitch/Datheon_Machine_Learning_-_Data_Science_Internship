# Real Estate House Price Prediction

## Project Overview
This project predicts median house values using the California housing dataset provided in `housing.csv`. It compares Ordinary Least Squares, Ridge Regression (L2), and Lasso Regression (L1).

## Objectives
- Explore and visualize the dataset.
- Handle missing numerical values.
- Encode categorical variables.
- Engineer household-level features.
- Investigate feature correlation and multicollinearity.
- Tune Ridge and Lasso using GridSearchCV.
- Evaluate models using RMSE, MAE, and R².
- Visualize actual versus predicted values and residual errors.

## Technologies
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Jupyter Notebook, and Joblib.

## Files
- `housing.csv` — supplied dataset
- `house_price_prediction.ipynb` — complete analysis and model training
- `best_house_price_model.pkl` — saved trained pipeline
- `outputs/` — visualizations and model comparison results
- `requirements.txt` — Python dependencies

## How to Run
1. Install the dependencies.
2. Place `housing.csv` beside the notebook.
3. Open the notebook in VS Code.
4. Run the cells in order.
5. Review the evaluation metrics and plots.

## Limitations
The dataset represents California census-block-group housing data, not current individual property listings. Predictions are estimates for educational purposes and should not be treated as current market valuations.
