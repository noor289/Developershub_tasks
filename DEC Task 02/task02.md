# Customer Segmentation Using Unsupervised Learning

## Objective
The objective of this project is to segment mall customers based on their demographic
attributes and spending behavior using unsupervised learning techniques. By applying
K-Means clustering and dimensionality reduction methods such as PCA and t-SNE, the goal
is to identify distinct customer groups and propose targeted marketing strategies for
each segment to support data-driven business decision-making.

---

## Dataset
**Mall Customers Dataset**

The dataset contains customer information collected from a shopping mall, including:
- Customer ID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1–100)
---

## Approach
The following steps were followed in this project:

1. Loaded and explored the dataset to understand its structure and features
2. Performed Exploratory Data Analysis (EDA) to identify patterns in age, income,
   gender, and spending behavior
3. Encoded categorical variables and standardized numerical features
4. Applied the Elbow Method to determine the optimal number of clusters
5. Implemented K-Means clustering to segment customers
6. Used PCA and t-SNE for cluster visualization
7. Analyzed cluster characteristics and derived marketing strategies

---

## Results & Insights
The K-Means algorithm successfully segmented customers into **five distinct clusters**.
Each cluster represents customers with similar demographic and spending patterns.
The segmentation revealed clear differences in income levels, spending behavior,
and age groups across clusters, enabling meaningful business interpretation.

---

## Marketing Strategy Recommendations
Based on the identified customer segments, the following strategies are recommended:

- **High Income, High Spending Customers:** Target with premium products, exclusive
  offers, and loyalty programs
- **High Income, Low Spending Customers:** Use personalized promotions to encourage
  higher engagement
- **Low Income, High Spending Customers:** Offer value-for-money bundles and rewards
  for frequent purchases
- **Low Income, Low Spending Customers:** Focus on discounts, coupons, and budget-friendly
  product offerings
- **Moderate Customers:** Apply balanced marketing strategies such as cross-selling
  and upselling

---

## Conclusion
This project demonstrates the effectiveness of unsupervised learning in understanding
customer behavior. By leveraging K-Means clustering and dimensionality reduction
techniques, meaningful customer segments were identified, enabling targeted marketing
strategies that can improve customer engagement and business performance.
