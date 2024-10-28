# Telecom_churn_analysis
Project Overview:
The goal of this project is to predict customer churn for a telecom company and identify key factors contributing to churn. By identifying high-risk customers early, the company can take preemptive actions to reduce churn rates.

Business Objective:
High-value customers were analyzed to predict their likelihood of churning, using data from the first three months (June, July, August) to predict churn in the fourth month (September). Our analysis helps the company create strategies to retain customers by understanding key churn predictors.

Data Preparation:
The dataset contained customer-level information across four months. We filtered high-value customers based on their recharge behavior in the first t (Good Phase).o months.
Churn was defined based on customer behavior in the fourth month (e.g., no outgoing/incoming calls or data usage).
We handled missing values by imputing them and performed necessary feature engineering to prepare the dataset for modeling.

Modeling:
We built several models to predict churn, including:

Logistic Regression with class-weight adjustment to handle class imbalance.
Cross-validation and hyperparameter tuning were performed to ensure robust model performance.
ROC-AUC was used as the primary evaluation metric.

Model Evaluation:
The final logistic regression model achieved0.91C-AUC score of X.
Precision, recall, and F1-score metrics were calculated to assess model performance, focusing on predicting churners accurately.
Cross-validation was used to assess model consistency across different subsets of the data.

Feature Importance:
Key factors influencing customer churn include:

Recharge amount in the first two months.
Outgoing call usage and data consumption.
Roaming patterns and the last recharge date.

Recommendations:
Based on the analysis, the following strategies are recommended to reduce churn:

Offer personalized recharge incentives and loyalty programs to customers with declining recharge amounts.
Provide special roaming packages and free data boosts for customers with high roaming usage.
Use predictive models to target at-risk customers with specialized retention offers.

Conclusion:
This project provides actionable insights into customer behavior and presents strategies for reducing churn by addressing thneeds of high-risk customers early.
