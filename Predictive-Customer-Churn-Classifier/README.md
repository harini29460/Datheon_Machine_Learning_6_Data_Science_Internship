# Predictive Customer Churn Classifier

## Project Overview
This project predicts customer churn using machine learning algorithms. It uses telecom customer subscription records to identify customers who are likely to discontinue their services.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Imbalanced-learn

## Machine Learning Algorithms
1. Random Forest Classifier
2. XGBoost Classifier

## Project Workflow
1. Load the Telco Customer Churn dataset.
2. Perform data cleaning and preprocessing.
3. Convert TotalCharges into numeric format.
4. Encode categorical features using OneHotEncoder.
5. Split data into training and testing sets.
6. Handle class imbalance using SMOTE.
7. Train Random Forest and XGBoost models.
8. Evaluate models using classification metrics.
9. Perform 5-fold cross-validation.
10. Visualize ROC curves and confusion matrices.
11. Identify the top 10 important features.

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Visualizations
- Confusion Matrix
- ROC Curve
- Model Comparison
- Feature Importance

## Dataset
IBM Telco Customer Churn Dataset

[Download Dataset](https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv)

## Project Structure
```text
Predictive-Customer-Churn-Classifier/
│
├── README.md
├── Predictive_Customer_Churn_Classifier.ipynb
└── Results/
```

## Objective
To compare ensemble machine learning algorithms and evaluate their ability to predict customer churn using ROC-AUC and other classification metrics.

## Author
Harini
