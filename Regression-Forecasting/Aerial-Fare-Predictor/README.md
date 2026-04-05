# ✈️ Aerial Fare Predictor

Predict flight fares with high precision using historical route data and airline analytics.

## 📊 Overview
This project focuses on predicting the prices of flight tickets using various machine learning regression techniques. The model considers factors such as airline, source/destination, duration, and stops to forecast the most accurate fare.

## 🛠️ Features
- **Exploratory Data Analysis (EDA)**: Understanding price trends based on airline and seasonality.
- **Preprocessing**: Handling categorical data (Label Encoding/One Hot Encoding) and scaling.
- **Model Training**: Implementation of `RandomForestRegressor`, `GradientBoostingRegressor`, and `CatBoost`.
- **Evaluation**: Visualizing residuals and accuracy metrics (R2 Score, MSE).

## 🚀 Getting Started

### Prerequisites
Ensure you have the following libraries installed:
```bash
pip install pandas numpy seaborn matplotlib scikit-learn catboost
```

### Usage
Open the core experiment notebook to see the full modeling process:
- **[Forecasting_Model.ipynb](Forecasting_Model.ipynb)**

## 📂 Project Structure
- `Forecasting_Model.ipynb`: The primary research and modeling notebook.
- `data.csv`: Historical airfare dataset used for training and validation.

---
Part of the [AI Universe](file:///e:/00%20Projects/AI-Universe/README.md) project.
