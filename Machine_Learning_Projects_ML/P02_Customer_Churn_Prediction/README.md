# Customer Churn Prediction
**1. Overview:**
   
This project focuses on predicting customer churn for a subscription-based service using machine learning. The primary objective is to identify customers who are at risk of discontinuing their subscriptions. With accurate churn predictions, businesses can take proactive measures to retain valuable customers and reduce revenue loss.

**2. Objective:**
- Build an end-to-end churn prediction pipeline.
- Understand the drivers of customer churn.
- Evaluate machine learning models to accurately predict churn.
- Provide interpretable outputs to support business decisions.
  
**3. Dataset Description:**

The dataset comprises various attributes related to customer demographics, account information, service usage patterns, and billing details. The target variable is 'Churn', indicating whether a customer has left the service.

**4. Project Workflow:**

**4.1 Data Preprocessing**
- Handled missing values, specifically in the 'TotalCharges' column.
- Encoded categorical variables using appropriate techniques (Label Encoding and One-Hot Encoding).
- Standardized numerical features using StandardScaler.
- Performed feature engineering, including tenure grouping.
  
**4.2 Exploratory Data Analysis (EDA)**
Churn was analyzed across key customer attributes using bar charts and count plots. Key observations include:
- Higher churn among customers with month-to-month contracts.
- Customers with electronic check payments and no tech support had higher churn probability.
- High monthly charges and short tenure correlated with higher churn.
  
**4.3 Model Building & Evaluation**
- Train-test split (70-30).
- Algorithms tested: Logistic Regression, Decision Tree, and Random Forest.
- Evaluation metrics: Accuracy, Precision, Recall, F1-score.

  <img width="260" alt="image" src="https://github.com/user-attachments/assets/86686536-4bbc-40b9-8bbe-a3f5e98be4cd" />


**4.4 Model Interpretation**
- Random Forest’s feature importance was used to determine top drivers of churn.
- Important features: Contract Type, Monthly Charges, Tenure, Tech Support, Internet Service.
- These features provide strategic levers for customer retention.
  
**5. Business Implications:**
- Customers on flexible contracts are more prone to churn.
- Bundling tech support and offering discounts on long-term contracts may reduce churn.
- Churn prediction enables marketing to proactively engage high-risk customers.
  
**6. Conclusion:**

This project successfully developed a churn prediction model using supervised learning techniques. With accurate predictions and interpretable features, the model empowers businesses to adopt targeted strategies that enhance customer retention. This approach is adaptable to any subscription-based industry, making it a critical asset for customer lifecycle management.
