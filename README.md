📊 Linear Regression Project – Customer Spending Analysis
📁 Project Overview

This project applies Linear Regression to analyze customer behavior and predict Yearly Amount Spent based on user activity data from an e-commerce platform.

The goal is to understand:

What drives customer spending
Which platform (App vs Website) performs better
How businesses can optimize revenue
📦 Dataset Description

The dataset contains the following features:

Avg. Session Length
Time on App
Time on Website
Length of Membership
Yearly Amount Spent (Target Variable)
🔍 Exploratory Data Analysis (EDA)
Key Visualizations Used:
Pairplots
Jointplots (Hexbin)
Distribution plots
4
Insights from EDA:
Strong correlation between Length of Membership and spending
Time on App shows positive impact
Website usage has weaker correlation
🤖 Model Building

We used:

Linear Regression (from sklearn)
Steps:
Train-test split
Model training
Predictions
Evaluation
📈 Model Evaluation

Metrics used:

MAE (Mean Absolute Error)
MSE (Mean Squared Error)
RMSE (Root Mean Squared Error)
4
Residual Analysis:
Residuals are approximately normally distributed
Indicates a good model fit
📊 Feature Importance (Coefficients)

Key interpretation:

Length of Membership → Strongest predictor
Time on App → High positive impact
Avg Session Length → Moderate impact
Time on Website → Low / negligible impact
💡 Business Insights
1. Mobile App is the Revenue Driver 📱

Customers who spend more time on the App tend to spend more money.

👉 Recommendation:

Invest more in app experience
Improve UI/UX and engagement features
2. Website Needs Improvement 🌐

Time on Website has very little impact on revenue.

👉 Recommendation:

Optimize website conversion funnel
Improve speed, navigation, and personalization
3. Customer Loyalty Matters 🔁

Length of Membership is the strongest predictor.

👉 Recommendation:

Focus on retention strategies
Loyalty programs, subscriptions, rewards
4. High Engagement = High Value 👥

Customers who spend more time interacting tend to spend more.

👉 Recommendation:

Use notifications, recommendations, and offers to increase engagement
🚀 Conclusion
The model successfully predicts customer spending
Business should prioritize:
App development
Customer retention
Engagement strategies
🛠️ Tech Stack
Python
Pandas
NumPy
Matplotlib / Seaborn
Scikit-learn
📌 Future Improvements
Try advanced models (Random Forest, XGBoost)
Feature engineering
Hyperparameter tuning
Add more behavioral data
