# Employee-Attrition
Predicted employee attrition using IBM HR Analytics dataset (1,470 employees).  Trained Logistic Regression, Random Forest, and Gradient Boosting models.  Logistic Regression achieved best Recall of 83% and ROC-AUC of 0.87.  Tech Stack: Python, Pandas, Scikit-learn, Matplotlib, Seaborn.
# Employee Attrition Prediction using Machine Learning

## Overview
Built an end-to-end ML system to predict employee attrition using the IBM HR Analytics dataset (1,470 employees, 35 features) as part of an internship project.

## Dataset
[IBM HR Analytics Employee Attrition Dataset](https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset)

## Project Structure

EmployeeAttrition_SajaiS/
├── analysis.ipynb        # Complete Jupyter Notebook
├── HR_Attrition.csv      # Dataset
├── summary.pdf           # HR Director Summary
└── charts/
├── chart1_attrition_by_dept_and_role.png
├── chart2_monthly_income_vs_attrition.png
├── chart3_confusion_matrix.png
├── chart4_feature_importance.png
└── chart5_roc_curve.png

## Tasks Completed
- ✅ Data Loading & Exploration
- ✅ Data Cleaning & Preprocessing
- ✅ Exploratory Data Analysis
- ✅ Model Building & Comparison
- ✅ Model Evaluation
- ✅ Visualizations (5 charts)
- ✅ HR Insights & Recommendations

## Models Trained
| Model | Recall | ROC-AUC |
|-------|--------|---------|
| Logistic Regression | 83% | 0.87 |
| Random Forest | 10% | 0.83 |
| Gradient Boosting | 24% | 0.84 |

## Key Findings
- Sales Representatives have the highest attrition rate at 39.76%
- Employees who left earned Rs.2,000 less per month on average
- Overtime and frequent business travel are strong predictors of attrition
- Attrition is highest in the first 2 years of employment

## Tech Stack
- Python, Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- ReportLab

## Author
Sajai S | Internship Week 2
