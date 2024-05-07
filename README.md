# Forecasting CO2 Emissions in the Agri-Food Sector

In an era where climate change poses significant challenges to our environment, this project aims to forecast global temperature increases by analyzing emissions data from the agri-food sector using advanced machine learning techniques.

## Problem Definition
The agri-food sector is a significant contributor to global emissions. This project tackles the challenge of predicting the impact of emissions on global temperature increases using machine learning models.

## Objectives
- Develop a machine learning algorithm to predict yearly temperature increases.
- Provide a detailed breakdown of emission sources and their correlation with temperature changes.
- Equip stakeholders with the knowledge to make data-driven decisions.

## Data Description
The dataset contains the following features:
- **Area:** Geographic area or country
- **Year:** Year of data recording
- **Savanna Fires:** Emissions in kilotons
- **Forest Fires:** Emissions in kilotons
- **Crop Residues:** Emissions in kilotons
- **Rice Cultivation:** Emissions in kilotons
- **Other Features:** Drained Organic Soils, Pesticides Manufacturing, Food Transport, etc.

[Full Dataset Description & Source](https://www.kaggle.com/datasets/alessandrolobello/agri-food-co2-emission-dataset-forecasting-ml/data)

## Machine Learning Models
### Linear Regression
- Simple statistical model for relationship analysis.

### Random Forest Regression
- Ensemble model using multiple decision trees.

### Gradient Boosting Regression
- Ensemble model optimizing residuals sequentially.

### Other Models
- AdaBoost Regression
- XGBoost Regressor
- KNN Regression

## Model Performance and Evaluation
### Metrics
- **R² Score:** Proportion of variance in the dependent variable predictable by the model.
- **Mean Absolute Error (MAE):** Average magnitude of errors.
- **Mean Squared Error (MSE):** Average of the squares of the errors.
- **Root Mean Squared Error (RMSE):** Square root of the MSE.

### Comparative Analysis
Model | R² Score | MAE | MSE | RMSE
---|---|---|---|---
Linear Regression | 0.3103 | 0.3876 | 0.2601 | 0.5100
Random Forest Regression (After Tuning) | 0.5674 | 0.2952 | 0.1638 | 0.4047
Gradient Boosting Regression (After Tuning) | 0.5567 | 0.3248 | 0.1919 | 0.4380
XGBoost Regressor (After Tuning) | 0.5610 | 0.2979 | 0.1686 | 0.4106
KNN Regression | 0.4148 | 0.3537 | 0.2202 | 0.4693

## Conclusion
This project demonstrates that machine learning models can predict global temperature increases based on agri-food emissions data, with Random Forest and Gradient Boosting showing the best performance. Further improvements can be made through advanced feature engineering and interpretability enhancements.

You can also refer to this [Prei_ppt] (https://prezi.com/view/erYXIqazTu2EycS1bqSs/) for better reference 


## Full Report
For the complete analysis and detailed results, refer to the [Full Report](DATA_MINING_PROJECT_REPORT.pdf).
  
### Acknowledgments
Special thanks to [Kaggle Dataset Provider](https://www.kaggle.com/datasets/alessandrolobello/agri-food-co2-emission-dataset-forecasting-ml/data) and contributors.
