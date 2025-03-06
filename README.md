# Flood-Prediction-model
# Flood Prediction using Machine Learning

## Overview
This project aims to predict flood probability using machine learning models, specifically **Gradient Boosting Regressor** and **XGBoost Regressor**. The dataset consists of multiple environmental and anthropogenic factors that influence flood occurrence.

## Dataset
The dataset includes various factors such as:
- Monsoon Intensity
- Topography Drainage
- River Management
- Deforestation
- Urbanization
- Climate Change
- Dams Quality
- Siltation
- Agricultural Practices
- Encroachments
- Drainage Systems
- Coastal Vulnerability
- Landslides
- Watersheds
- Population Score
- Wetland Loss

### Download Kaggle Dataset
kaggle datasets download -d your-dataset-name

### Data Preprocessing
- Handled missing values by **imputation**.
- Scaled the data using **MinMaxScaler**.
- Selected relevant features using **Feature Importance**.

## Models Used
1. **Gradient Boosting Regressor**
2. **XGBoost Regressor** (Final Model)

### Performance Metrics (Mean Squared Error - MSE)
| Model | Train MSE | Test MSE |
|--------|------------|-------------|
| Gradient Boosting | 0.000239 | 0.001656 |
| XGBoost | 0.000518 | 0.001564 |

## Feature Importance
A feature importance analysis was performed, and key influential factors in flood prediction were identified:
- **Agricultural Practices**
- **Coastal Vulnerability**
- **Watersheds**
- **Monsoon Intensity**
- **Topography Drainage**
- **Deforestation**
- **Siltation**
- **Drainage Systems**
- **Landslides**
- **Wetland Loss**
- **Encroachments**
- **Dams Quality**

## How to Use
### 1. Install Dependencies
```bash
pip install numpy pandas matplotlib seaborn scikit-learn xgboost
```

### 2. Run the Code
```python
python flood_prediction.py
```
