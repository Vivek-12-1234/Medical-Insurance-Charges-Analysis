# Medical-Insurance-Charges-Analysis

## Business Problem
Identify key factors that influence medical insurance charges to support fair and data-driven premium pricing.

## Dataset
- 1338 records
- Features: age, sex, bmi, children, smoker, region
- Target variable: charges

## Approach
- Data Cleaning and EDA
- Hypothesis Testing
- Feature Engineering
- Model Building and Comparison

## Models Used
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor
- XGBoost Regressor

## Model Performance Summary

| Model | R² Score | RMSE |
|------|---------|------|
| Linear Regression | ~0.88 | Log-scale |
| Random Forest | ~0.88 | ~4700 |
| Gradient Boosting | **~0.90** | **~4257** |
| XGBoost | ~0.89 | ~4434 |

**Final Model:** Gradient Boosting Regressor

## Key Insights
- Smoking status has the strongest impact on insurance charges
- Age is a major risk factor
- BMI and number of children have weaker but statistically significant effects

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, XGBoost, Seaborn

 **Full Project Report (PDF)**  
The complete analysis report exported from Google Colab is available here:
## Project Results

📄 **Full Project Report (PDF)**  
[View Project Report]([https://github.com/Vivek-12-1234/Medical-Insurance-Charges-Analysis/blob/main/results/insurance_analysis_report.pdf](https://github.com/Vivek-12-1234/Medical-Insurance-Charges-Analysis/tree/9c2a02e7ac29b5facfedda13cbe9552f51dacc59/results])

**Interactive Notebook (Google Colab):**  
[Open in Google Colab](https://colab.research.google.com/drive/16aY2t8agvFZyfdsQVgNCFBQSykoI6BwH)
