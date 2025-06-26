# Taxi Demand Forecasting (Time Series)

This machine learning project focuses on forecasting hourly taxi demand at airport locations for **Sweet Lift Taxi**.  
The goal is to build a regression model that predicts the number of taxi orders for the next hour, helping the company attract more drivers during peak times.

---

## Dataset

- `taxi.csv` — Time-indexed historical data of taxi orders

### Key Feature:
- `num_orders` — Number of taxi orders (target variable)

---

## Tools & Libraries

- Python
- pandas, numpy
- scikit-learn
- statsmodels
- matplotlib, seaborn

---

## Project Workflow

### 1. Data Preparation
- Resampled the dataset to 1-hour intervals
- Created time-based lag features
- Checked for stationarity and visualized demand trends

### 2. Modeling
- Split data into train/test sets (10% for testing)
- Trained and tuned several models:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting (optional)
- Evaluated model performance using RMSE

### 3. Evaluation
- Compared model scores on validation and test sets
- Final model selected based on test RMSE ≤ 48

---

## Key Results

- The final model achieved RMSE ≤ 48, meeting project success criteria
- Lag features significantly improved prediction quality
- Visualizations confirmed demand patterns over time

---

## How to Run

1. Clone this repository
2. Make sure `taxi.csv` is in the same directory as the notebook
3. Open the notebook in Jupyter
4. Run all cells to train and evaluate the forecasting models

---

## Links

- [My LinkedIn](https://www.linkedin.com/in/ozturkkenes)
- [My GitHub](https://github.com/Harewavy)
