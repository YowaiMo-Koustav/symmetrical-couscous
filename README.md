# 🦠 Epidemic Outbreak Prediction System

An AI-powered epidemic prediction project built using the **Johns Hopkins COVID-19 Time Series Dataset** to forecast outbreak trends, detect hotspots, and generate outbreak risk scores.

## 🚀 Features
- Predicts future case growth
- Detects outbreak hotspots
- Generates Low / Medium / High risk levels
- Produces dashboard-ready outputs
- Uses time-series aware machine learning

## 📊 Dataset
Primary dataset: **Johns Hopkins COVID-19 Time Series Dataset**  
Used for global region-wise outbreak forecasting and trend analysis.

## 🧠 Approach
- Convert raw time-series data into modeling format
- Engineer lag and rolling trend features
- Train a predictive ML model
- Forecast future cases
- Convert predictions into outbreak risk insights

## 🖥️ Outputs
- `predictions.csv`
- `risk_scores.csv`
- `hotspot_regions.csv`
- `feature_importance.csv`
- `summary_metrics.csv`

## 📈 Tech Stack
- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- Google Colab

## 🎯 Goal
To support public health preparedness by turning outbreak data into actionable, interpretable predictions.
