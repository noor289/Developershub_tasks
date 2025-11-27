# Customer Churn Prediction

## Objective
Predict which bank customers are likely to leave (churn) using historical customer data.

## Dataset
- **Source:** [Churn Modelling Dataset](https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling)
- **Entries:** 10,000 customers  
- **Features:** CreditScore, Geography, Gender, Age, Tenure, Balance, NumOfProducts, HasCrCard, IsActiveMember, EstimatedSalary  
- **Target:** Exited (1 = churn, 0 = stayed)

## Approach
1. Data cleaning: removed unnecessary columns (`RowNumber`, `CustomerId`, `Surname`)  
2. Categorical encoding:  
   - Gender → Label Encoding  
   - Geography → One-Hot Encoding  
3. Exploratory Data Analysis (EDA) with plots and correlation heatmap  
4. Train/Test split (80/20)  
5. Model: Random Forest Classifier  
6. Evaluation using accuracy, confusion matrix, and classification report  
7. Feature importance analysis to identify key factors influencing churn

## Results
- **Accuracy:** 86.6%  
- **Key Features Influencing Churn:** Age, EstimatedSalary, CreditScore, Balance, NumOfProducts  
- Model predicts staying customers well but has lower recall for churners.

## Insights
- Older customers with higher balance or multiple products are more likely to churn.  
- Gender and country are less significant.  
- Handling class imbalance or trying other models could improve churn prediction.

