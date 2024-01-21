# Credit Risk Assessment Using Machine Learning
 Finance and Banking Sector

---

## Objective 

This project aims to build and evaluate machine learning models for assessing credit risk using the German Credit Data. It covers various stages including data preprocessing, exploratory data analysis, feature engineering, and model tuning.

## Project Overview

- **Data Exploration and Preprocessing**: Understanding the data, handling missing values, and encoding categorical variables.
- **Exploratory Data Analysis (EDA)**: Analyzing distributions and relationships between variables.
- **Feature Selection**: Identifying the most relevant features for the model.
- **Model Building**: Building different machine learning models for classification.
- **Model Evaluation**: Evaluating models using metrics like accuracy, precision, recall, and ROC-AUC.
- **Model Selection and Tuning**: Selecting the best model and tuning hyperparameters if necessary.

## Key Insights

> **Impact of SMOTE**: The application of SMOTE significantly improved the models' performances, indicating that class imbalance was a major factor affecting accuracy.

**Key Features**: Custom features like `DebtIncomeRatio`, `CreditAmountPerInstallment`, and `AgeCategory` played a significant role in enhancing model predictions.

**Model Complexity vs. Performance**: More complex models like XGBoost required more tuning but ultimately provided better results.

## Models Used

1. **Logistic Regression**
2. **Random Forest**
3. **Gradient Boosting**
4. **XGBoost**

### Model Performance

- **Logistic Regression**: Showed the best initial performance in terms of accuracy and ROC-AUC.
- **XGBoost**: Emerged as the most effective after applying SMOTE and tuning, exhibiting the highest accuracy and ROC-AUC.

## Conclusion

This project demonstrates the effectiveness of machine learning in credit risk assessment. The insights can assist financial institutions in making more informed decisions, leading to effective risk management.

---
