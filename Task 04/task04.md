# **Predicting Insurance Claim Amounts**

## **Objective**

The goal of this task is to estimate medical insurance claim amounts using personal demographic and health information. A Linear Regression model is used to learn relationships between features and insurance charges.

---

## **Dataset**

**Medical Cost Personal Dataset**

Includes the following features:

* Age
* Sex
* BMI (Body Mass Index)
* Number of children
* Smoking status
* Residential region
* Insurance charges (target variable)

---

## **Steps Performed**

### **1. Data Loading & Exploration**

The dataset was inspected for structure, missing values, and overall distribution of features.

### **2. Categorical Encoding**

Categorical variables (sex, smoker, region) were converted into numerical form using one-hot encoding.

### **3. Train/Test Split**

The dataset was divided into training and testing sets to evaluate model performance fairly.

### **4. Model Training**

A Linear Regression model was trained using the training data to learn patterns that influence insurance charges.

### **5. Predictions**

The trained model predicted insurance charges on the test dataset.

### **6. Model Evaluation**

Model performance was evaluated using:

* **MAE (Mean Absolute Error)** – average error between predictions and actual values
* **RMSE (Root Mean Squared Error)** – measures overall prediction error magnitude

### **7. Visualizations**

Several plots were created to understand how features affect insurance charges:

* Age vs Charges
* BMI vs Charges
* Smoking Status vs Charges (Boxplot)

---

## **Key Insights**

* Smokers have **significantly higher** insurance charges compared to non-smokers.
* **Age and BMI** show a positive correlation with insurance costs.
* Linear Regression performs reasonably well but may miss complex non-linear patterns.
