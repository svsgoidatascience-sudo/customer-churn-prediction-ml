# Customer Churn Prediction using Machine Learning

## Project Overview

This project develops an end-to-end Machine Learning solution to predict customer churn. The goal is to identify customers who are at risk of leaving so that businesses can take proactive retention actions.

The project covers data preprocessing, exploratory analysis, model development, class imbalance handling, model evaluation, threshold analysis, and business interpretation.

## Machine Learning Workflow

1. Data loading and exploration
2. Data preprocessing
3. Categorical feature encoding
4. Train-test splitting
5. Logistic Regression model
6. Random Forest model
7. Class imbalance analysis
8. SMOTE oversampling
9. Model comparison
10. ROC-AUC evaluation
11. Classification threshold analysis
12. Feature interpretation
13. Business insights

## Models Used

- Logistic Regression
- Random Forest
- Logistic Regression with SMOTE
- Random Forest with SMOTE

## Final Model

The selected model is **Logistic Regression with SMOTE**.

### Model Performance

| Metric | Result |
|---|---:|
| Accuracy | 64% |
| ROC-AUC | 0.713 |
| Churn Recall | 75% |
| Churn Precision | 46% |
| Churn F1-Score | 57% |

The model correctly identified **47 out of 63 customers who actually churned**.

## Why Recall Matters

For customer churn prediction, identifying customers who may leave is particularly important.

A higher churn recall helps the business identify more at-risk customers so that retention strategies can be applied before those customers leave.

## Key Business Insights

The analysis indicates that:

- Longer-term contracts are associated with lower churn probability.
- Customers making more support calls show increased churn risk.
- Machine Learning can help businesses identify customers who may require retention attention.

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Imbalanced-learn
- Matplotlib
- SMOTE
- Google Colab

## Skills Demonstrated

- Data Preprocessing
- Exploratory Data Analysis
- Machine Learning Classification
- Logistic Regression
- Random Forest
- Handling Imbalanced Data
- SMOTE
- Confusion Matrix Analysis
- Precision, Recall and F1-Score
- ROC Curve and ROC-AUC
- Threshold Optimization
- Model Interpretation
- Business Insight Generation

## Conclusion

This project demonstrates a complete Machine Learning classification workflow, from raw data preparation to model evaluation and business interpretation.

Rather than relying only on accuracy, the project evaluates recall, precision, F1-score and ROC-AUC to select a model appropriate for the customer-retention objective.

## Author

**Yasin Ali Mohammed**

Machine Learning & Data Science Portfolio Project

