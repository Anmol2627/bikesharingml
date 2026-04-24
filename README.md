# Bike Sharing Demand Forecasting

Predicting **hourly bike rental demand** using time series analysis, feature engineering, and supervised machine learning.

## 📊 Dataset

The UCI Bike Sharing Dataset contains **~17,000+ hourly records** spanning two years (2011–2012), with weather, calendar, and temporal features.

### Features
| Column | Description |
|--------|-------------|
| `instant` | Record index |
| `dteday` | Date (YYYY-MM-DD) |
| `season` | Season (1=Spring, 2=Summer, 3=Fall, 4=Winter) |
| `yr` | Year (0=2011, 1=2012) |
| `mnth` | Month (1–12) |
| `hr` | Hour (0–23) |
| `holiday` | Whether the day is a holiday |
| `weekday` | Day of the week (0–6) |
| `workingday` | Whether the day is a working day |
| `weathersit` | Weather situation (1=Clear, 2=Mist, 3=Light Rain/Snow, 4=Heavy Rain) |
| `temp` | Normalized temperature in Celsius |
| `atemp` | Normalized feeling temperature |
| `hum` | Normalized humidity |
| `windspeed` | Normalized wind speed |
| `casual` | Count of casual users |
| `registered` | Count of registered users |
| `cnt` | Total rental count (target variable) |

## 🛠️ Technologies Used

- **Python 3**
- **Pandas** - Data manipulation
- **NumPy** - Numerical computing
- **Matplotlib/Seaborn** - Data visualization
- **Scikit-learn** - Machine learning models
- **LightGBM** - Gradient boosting
- **XGBoost** - Extreme gradient boosting
- **Statsmodels** - Time series decomposition

## 📋 Notebook Outline

1. **Introduction** - Problem statement and dataset description
2. **Data Loading & Overview** - Import libraries, load data, initial inspection
3. **Data Cleaning** - Handle missing values, duplicates, outliers
4. **Exploratory Data Analysis (EDA)** - Visualize patterns and relationships
5. **Time Series Analysis** - Trend, seasonality, decomposition
6. **Feature Engineering** - Create new features for better predictions
7. **Model Building** - Train multiple models (Linear Regression, Random Forest, XGBoost, LightGBM, Stacking)
8. **Evaluation & Comparison** - Compare model performance using RMSE and MAE
9. **Conclusion & Insights** - Key findings and recommendations

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn lightgbm xgboost statsmodels
```

### Run the Notebook
```bash
jupyter notebook bike_sharing_forecasting.ipynb
```

## 📈 Models Evaluated

| Model | RMSE | MAE |
|-------|------|-----|
| Linear Regression |  | - |
| Random Forest | - | - |
| XGBoost | - | - |
| LightGBM | - | - |
| Stacking Regressor | - | - |

## 📝 License

This project is for educational purposes.
