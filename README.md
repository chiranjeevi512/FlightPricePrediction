# ✈️ Flight Price Prediction (PRCP-1025)

This project is part of a capstone task to predict flight ticket prices using machine learning techniques. The goal is to provide price estimations based on features like airline, route, duration, total stops, and other attributes. This helps customers plan better and airlines optimize their pricing strategy.

## 📌 Problem Statement

Flight ticket prices can change frequently and seem unpredictable. This project aims to develop a predictive model that forecasts flight prices using historical data, which includes various flight details.

## 📊 Tasks Completed

- ✅ Task 1: Exploratory Data Analysis (EDA)
  - Data cleaning, transformation
  - Feature extraction (date, time, duration, etc.)
  - Visualization of trends and relationships

- ✅ Task 2: Predictive Modeling
  - Built regression models to estimate flight prices
  - Applied algorithms: Linear Regression, Decision Tree, Random Forest, Gradient Boosting, XGBoost
  - Compared models using R² Score, MAE, RMSE

- ✅ Model Comparison Report
  - Evaluated models and selected the best-performing one

- ✅ Challenges Faced Report
  - Addressed missing values, outliers, inconsistent formats
  - Used techniques like label encoding, feature scaling, and grid search for tuning

## 📂 Dataset

- **Source:** [Flight Fare Dataset (Download)](https://d3ilbtxij3aepc.cloudfront.net/projects/CDS-Capstone-Projects/flight-fare.zip)
- **Attributes include:**
  - Airline
  - Date_of_Journey
  - Source & Destination
  - Route
  - Arrival_Time
  - Duration
  - Total_Stops
  - Additional_Info
  - Price (target)

## 🛠️ Tech Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- Jupyter Notebook

## 📈 Model Results

| Model               | R² Score | MAE     | RMSE    |
|--------------------|----------|---------|---------|
| Linear Regression  | 0.61     | 1900.54 | 2762.45 |
| Random Forest      | 0.91     | 760.32  | 1242.18 |
| Gradient Boosting  | 0.89     | 800.21  | 1356.70 |
| XGBoost            | 0.90     | 770.84  | 1301.33 |

✅ **Best Model:** Random Forest Regressor

## 🧠 Challenges Faced

- Handled missing values and irrelevant columns
- Standardized `Duration`, `Date_of_Journey`, `Arrival/Departure` fields
- Feature Engineering from datetime fields
- Imbalanced feature categories
- Model tuning and overfitting prevention

## 📁 File Structure
