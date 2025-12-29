# Task 1: Term Deposit Subscription Prediction (Bank Marketing)

## Overview
This project predicts whether a bank customer will subscribe to a term deposit as a result of a marketing campaign. The goal is to help the bank identify potential customers more effectively, reducing wasted resources and improving campaign efficiency.

The project also includes **explainable AI (XAI)** using **LIME** to interpret model predictions.

---

## Dataset
- **Name:** Bank Marketing Dataset (Full version)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- **Records:** 41,188 customers
- **Target Variable:** `y` (1 = subscribed, 0 = not subscribed)
- **Features:**
  - **Categorical:** job, marital, education, contact, month, poutcome
  - **Numerical:** age, balance, duration, campaign, pdays, previous


---

## Objective
- Build a classification model to predict term deposit subscription.
- Evaluate models using Confusion Matrix, F1-Score, and ROC Curve.
- Provide explainable AI insights using **LIME** for 5 individual predictions.

---

## Approach
1. **Data Preprocessing**
   - Encode categorical features using OneHotEncoder.
   - Scale numerical features using StandardScaler.
   - Split dataset into train (80%) and test (20%) sets.

2. **Modeling**
   - Logistic Regression
   - Random Forest Classifier (best-performing model)

3. **Evaluation Metrics**
   - F1-Score
   - Confusion Matrix
   - ROC Curve and AUC

4. **Explainability**
   - Used **LIME** to interpret individual predictions on the test set.
   - Displayed feature contributions for 5 randomly selected customers.

---

## Results
- **Random Forest F1-Score:** 0.77 (higher than Logistic Regression)
- Key features influencing subscription:
  - Duration of last call
  - Contact type
  - Number of previous contacts
  - Month of contact
- LIME explanations provide transparency on why the model predicted subscription or not for each individual.

---

## Tools & Libraries
- Python 3.x
- pandas, numpy
- scikit-learn
- matplotlib, seaborn
- lime

---
## Conclusion
This project successfully predicts customer subscription behavior and provides clear explanations using LIME. It demonstrates both strong predictive performance and model interpretability, suitable for real-world banking decision support systems.


