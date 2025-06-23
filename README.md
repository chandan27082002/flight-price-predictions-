# Flight Price Prediction using Machine Learning ✈️💰

## 📌 Overview
This project predicts flight prices based on features like departure time, airline, stops, and days left for the journey. It handles both Economy and Business class data.

## 🧾 Data
- `economy_class.csv` (206,774 rows)
- `business_class.csv` (93,487 rows)
- Null values < 5% were removed

## 📊 Exploratory Data Analysis (EDA)
- Pie Charts, Bar Charts, Line Charts
- Box Plots and Correlation Heatmaps

## 🧠 Models Used
Models were built using pipelines with `StandardScaler`, and tested on multiple algorithms:
- Linear Regression
- KNN Regressor
- Decision Tree
- Random Forest ✅ *(Best)*
- XGBoost

### ✅ **Best Model: Random Forest Regressor**
- **R² Score:** 0.9645
- **MAE:** 2189.39
- **MSE:** 18,250,234.77
- **MAPE:** 0.1361

## 📈 Actual vs Predicted (Sample)
| Actual  | Predicted   |
|---------|-------------|
| 54841.0 | 53419.43    |
| 5441.0  | 5795.86     |
| 52287.0 | 58937.94    |
| 51707.0 | 47834.07    |
| 16624.0 | 13679.08    |

## 🧪 Prediction on Unseen Data
A separate script is provided to load new data and generate predictions using the trained pipeline.

