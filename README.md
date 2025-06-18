# 🏠 Melbourne Housing Price Prediction

This project analyzes the [Melbourne Housing Dataset](https://www.kaggle.com/datasets/dansbecker/melbourne-housing-snapshot) to predict house prices using machine learning. The focus is on data cleaning, feature engineering, and model stacking to improve prediction accuracy.


## 📌 Key Features

- Data cleaning (handling nulls, outliers)
- Feature engineering (date features, categorical encoding, etc.)
- Model training: Linear Regression & Stacked Ensemble
- Evaluation using MSE, RMSE, and R² metrics
- Visualizations for better interpretability

## 📊 Model Performance

| Model                               | MSE               | RMSE        | R² Score |
|------------------------------------|-------------------|-------------|----------|
| Linear Regression (Raw Data)       | Very High         | Very High   | Low      |
| Linear Regression (Cleaned Data)   | 116,390,523,263   | 341,160.55  | 0.6708   |
| Stacked Model (Cleaned Data)       | 66,969,863,686    | 258,785.36  | 0.8106   |

✅ Feature engineering and cleaning had a major impact on model accuracy. The stacked model clearly outperformed basic regression.




