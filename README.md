# Credit Risk Prediction using XGBoost

## Overview

This project builds a machine learning model to predict loan default risk using the Lending Club dataset. The goal is to identify high-risk borrowers and support better credit decision-making.

The final model uses XGBoost with threshold tuning and SHAP explainability to provide both strong performance and interpretability.


 ## Features
	•	Data preprocessing and feature engineering
	•	Handling missing values and categorical encoding
	•	Class imbalance handling (SMOTE + class weighting)
	•	Model comparison (Logistic Regression, Random Forest, XGBoost)
	•	Threshold tuning for business optimization
	•	Model explainability using SHAP



## Model Performance
	•	Model: XGBoost
	•	ROC-AUC: 0.73
	•	Final Threshold: 0.4
	•	Recall (Defaulters): 81%



##  Results

🔹 ROC Curve
🔹 SHAP Summary (Global Feature Importance)
🔹 SHAP Waterfall (Single Prediction Explanation)



## Key Insights
	•	Higher interest rates and debt-to-income ratio increase default risk
	•	Higher income reduces risk
	•	Loan grade is a strong predictor of creditworthiness
	•	Longer loan terms are associated with higher default probability




##  Dataset
	•	Lending Club Loan Dataset (Kaggle)
	•	Dataset not included due to size constraints

  ## how to Run 
  1. clone the repository
  2. install dependencies

         pip install -r requirements.txt
4. run the notebook 


## Tech Stack
	•	Python
	•	Pandas, NumPy
	•	Scikit-learn
	•	XGBoost
	•	SHAP
	•	Matplotlib


## Business Impact

- Helps lenders identify high-risk borrowers
- Reduces financial losses due to loan defaults
- Enables risk-based loan pricing
- Improves decision-making using interpretable AI (SHAP)



👤 Author

Ananya Narang




