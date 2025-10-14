# 🏎️ F1 Lap Time Prediction – 2023 Hungarian Grand Prix

## 🎯 Objective
To build and compare machine learning models that predict Formula 1 lap times using telemetry data from the 2023 Hungarian GP.

## 📂 Data Source
- Extracted using the **FastF1** Python library
- Dataset includes detailed lap information for all drivers

## 🧩 Features Used
Initial model:
- `Sector1Time`
- `Sector2Time`
- `Sector3Time`

Extended model:
- All telemetry and timing-related features available in the dataset

## ⚙️ Models
- **Linear Regression** – baseline model
- **XGBoost Regressor** – gradient boosting model optimized for performance

## 🧪 Methodology
1. Data cleaning and preprocessing 
2. Feature selection using mutual information scores
3. Model training and comparison
4. Cross-validation to assess model stability
5. Performance evaluation using **Mean Absolute Error (MAE)**

## 📈 Results
| Model | MAE | Notes |
|--------|-----|-------|
| Linear Regression |  0.388000127853491s |  model using sector times |
| XGBoost |  0.11020679197273424s |  generalization with more features |



## 🔍 Insights
- Sector times alone are highly predictive of total lap time (R² > 0.95).
- XGBoost showed improved performance over linear regression with minimal overfitting.
- Mutual information analysis confirmed sector timing as dominant predictors of lap time.

## 🧠 Key Skills Demonstrated
- Data extraction using **FastF1**
- Data cleaning & feature selection
- Model building & validation (Linear Regression, XGBoost)
- Cross-validation, MAE, and error analysis
- Data visualization & telemetry interpretation

## 👨‍💻 Author
**Emmanuel Gyan**  
*Aerospace Engineering Student  

