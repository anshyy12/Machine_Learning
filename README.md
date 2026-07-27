# Machine_Learning
An end-to-end Machine Learning project using Scikit-Learn to predict California median house values, featuring extensive EDA, feature engineering, and model evaluation (Linear Regression vs. Random Forest).

# 🏡 California House Price Prediction (End-to-End ML Pipeline)

An end-to-end machine learning project predicting median house values across California census blocks using Scikit-Learn, Pandas, and Data Science best practices.

## 📌 Project Overview
Predicting house prices is a classic regression problem. This project walks through the complete data science lifecycle:
1. **Data Cleaning & Handling Missing Values**: Imputing or handling missing numerical/categorical entries.
2. **Exploratory Data Analysis (EDA)**: Log transformations for right-skewed distributions and geospatial visualization.
3. **Feature Engineering**: Creating domain-specific ratios (e.g., `bedroom_ratio`, `household_rooms`).
4. **Model Building & Preprocessing**: Pipeline integration with `StandardScaler` and categorical encoding (`OneHotEncoder` / `get_dummies`).
5. **Model Evaluation & Tuning**: Comparing baseline models against ensemble algorithms using $R^2$, MAE, and RMSE metrics.

---

## 📊 Model Performance Summary

| Model | $R^2$ Score | Mean Absolute Error (MAE) | Root Mean Squared Error (RMSE) |
| :--- | :---: | :---: | :---: |
| **Linear Regression (Baseline)** | 0.6687 | $48,660.76 | $67,305.50 |
| **Random Forest Regressor** | **0.8194** | **$32,559.57** | **$49,690.99** |

* **Key Takeaway**: Moving to an ensemble approach (Random Forest) significantly reduced prediction error by **~$16,100 per house** and explained over **81.9%** of price variance.

---

## 🛠️ Tech Stack & Libraries
* **Language**: Python 3
* **Data Processing**: Pandas, NumPy
* **Visualization**: Matplotlib, Seaborn
* **Machine Learning**: Scikit-Learn (`LinearRegression`, `RandomForestRegressor`, `StandardScaler`, `train_test_split`)

---

## 🚀 Quickstart & Setup

1. **Clone the repository**:
   ```bash
   git clone [https://github.com/your-username/california-housing-ml.git](https://github.com/your-username/california-housing-ml.git)
   cd california-housing-ml
