#Project Overview
This project focuses on identifying "at-risk" customers before they leave a service. By leveraging machine learning, we analyze historical customer behavior, demographics, and transaction patterns to predict the probability of churn. This allows businesses to implement proactive retention strategies, such as targeted discounts or personalized outreach.

Why It Matters
Cost Efficiency: It is significantly cheaper to retain an existing customer than to acquire a new one.

Revenue Stability: Predicting churn helps maintain a predictable Monthly Recurring Revenue (MRR).

Customer Insights: Identifies the "pain points" in the customer journey that lead to dissatisfaction.

#Technical Workflow
Exploratory Data Analysis (EDA): Visualizing correlations between features (e.g., contract type, monthly charges) and churn rates.

#Data Preprocessing: Handling missing values, encoding categorical variables (One-Hot Encoding), and feature scaling.

#Handling Imbalance: Using techniques like SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset, as churners are typically the minority class.

Modeling: Benchmarking multiple algorithms:

Logistic Regression (Baseline)

Random Forest
knn

Evaluation: Prioritizing Recall and F1-Score over accuracy to ensure we catch as many potential churners as possible.

#Key Insights
Top Predictors: Customers on month-to-month contracts and those with high monthly charges without tech support showed the highest churn probability.
Model Performance: The final of [logistic regression,knn,decision tree] achieved an AUC-ROC score of [81,77,71]
#Tools & Tech
Language: Python

Libraries: Pandas, Scikit-learn, Matplotlib, Seaborn, numpy
