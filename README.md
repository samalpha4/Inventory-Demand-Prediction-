# Inventory-Demand-Prediction-
AI- based inventory demand prediction using machine learning
# Inventory Demand Prediction

## Problem Statement
Efficient inventory management is critical for reducing losses due to overstocking and stockouts.  
This project predicts future product demand using historical sales data and machine learning.

## Dataset
- Source: Kaggle (Sales Data Forecasting)
- Data contains transaction-level grocery sales information.
- Transactions are aggregated into daily product-level demand.

## Approach
1. Data loading and cleaning
2. Aggregation of transaction data
3. Feature engineering (day, month, year, product)
4. Training a Linear Regression model
5. Evaluating model using Mean Absolute Error (MAE)
6. Predicting future demand for a given date

## Machine Learning Model
- Model used: Linear Regression
- Reason: Simple, interpretable, and suitable for regression tasks

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Google Colab

## Results
The model successfully predicts future inventory demand based on historical patterns.

## Future Scope
- Use advanced models like Random Forest or LSTM
- Include promotional and seasonal factors
- Deploy as a web application
