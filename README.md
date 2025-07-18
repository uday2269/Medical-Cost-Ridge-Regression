# Medical-Cost-Ridge-Regression
Here’s a clean, professional README file (without emojis) for your medical cost prediction machine learning project based on the uploaded files:

---

# Medical Cost Prediction Using Machine Learning

## Overview

This project aims to predict medical insurance costs using machine learning techniques. With healthcare costs rising globally, the ability to estimate insurance premiums more accurately and fairly is becoming increasingly important. Traditional actuarial methods are limited in handling complex datasets, making ML models a better alternative for premium prediction.

## Team Members

* **T Uday Kiran** (AV.EN.U4CSE22245)
* **V Gnyana Sai Akshay** (AV.EN.U4CSE22247)
* **Under the Supervision of:** Mr. Dontha Madhusudhana Rao (Assistant Professor)
* **Institution:** Department of Computer Science, Amrita Vishwa Vidyapeetham, Amaravati

---

## Problem Statement

The goal is to develop a machine learning model that:

* Accurately predicts medical insurance costs.
* Balances interpretability, fairness, and computational efficiency.
* Addresses ethical concerns such as bias and model transparency.
* Is scalable and suitable for real-time application.

---

## Dataset

* **Source:** [Kaggle Medical Cost Personal Dataset](https://www.kaggle.com/datasets/mirichoi0218/insurance)
* **Size:** 1,338 rows with 7 main attributes:

  * `age` (int)
  * `sex` (binary categorical)
  * `bmi` (float)
  * `children` (int)
  * `smoker` (binary)
  * `region` (categorical with 4 regions)
  * `charges` (target variable - float)

---

## Preprocessing Techniques

* **Data Cleaning:** Handled missing values using mean/mode imputation.
* **Encoding:**

  * Binary variables (e.g., smoker) using label encoding.
  * Categorical variables (e.g., region) using One-Hot Encoding.
* **Scaling:** Applied `StandardScaler` on `age` and `bmi`.
* **Feature Engineering:** Created derived attributes (e.g., BMI categories, age groups).

---

## Methodology

1. **EDA (Exploratory Data Analysis):**

   * Analyzed distributions and correlation heatmaps.
   * Visualized relationships (e.g., smoker status vs. charges).
2. **Model Selection:**

   * Regression Models: Linear, Ridge, Lasso, Decision Tree, XGBoost, Gradient Boosting.
   * Classification Models: Logistic Regression, KNN, SVM (for categorizing high/low costs).
3. **Hyperparameter Tuning:**

   * Used GridSearchCV and k-fold cross-validation.
4. **Model Evaluation Metrics:**

   * Regression: MSE, MAE, RMSE, R².
   * Classification: Accuracy, Precision, Recall, F1-Score, Confusion Matrix.
5. **Model Interpretation:**

   * Feature importance analysis to identify key cost drivers.

---

## Key Results

* **Logistic Regression:**

  * Training Accuracy: 99.17%
  * Validation Accuracy: 99.17%
* **Important Predictors:** Smoking status and BMI were identified as the most significant contributors to insurance charges.

---

## Conclusion

The developed model provides reliable predictions of insurance premiums. Smoking status, BMI, and region emerged as influential factors. The model shows strong performance metrics and can be further improved through ensemble techniques, feature enrichment, or ethical fairness modeling.

---

## Future Work

* Incorporate socio-economic variables for fairness.
* Explore interpretability tools (e.g., SHAP, LIME).
* Deploy the model using a web interface or API for real-time usage.

---

## References

1. Kulkarni, M., et al., (2022). *Medical Insurance Cost Prediction Using Machine Learning*. International Journal for Research in Applied Science & Engineering Technology.
2. Hassan, C.A., et al., (2021). *A Computational Intelligence Approach for Predicting Medical Insurance Cost*. Mathematical Problems in Engineering.
3. Billa, M.M., & Nagpal, T. (2024). *Medical Insurance Price Prediction Using Machine Learning*. Journal of Electrical Systems.

---
