E-commerce Delivery App – Customer Churn Analysis|Project Overview

Customer churn is a major challenge for food delivery platforms. Acquiring new users costs significantly more than retaining existing customers.
This project analyzes customer behavior data to identify key drivers of churn and provide data-driven recommendations to improve customer retention.
Using Python, Pandas, and Machine Learning, the analysis identifies patterns in customer engagement, order frequency, complaints, and cashback usage to predict churn risk.

Business Problem

Food delivery platforms face high churn due to:
Long delivery times
Low customer engagement
Poor customer service experience
Lack of loyalty incentives
The goal of this project is to:

✔ Identify high-risk churn segments
✔ Understand behavior patterns of churned customers
✔ Build a predictive churn model
✔ Recommend data-driven retention strategies

>>Dataset Overview
The dataset contains customer behavioral and transaction data, including:
->Feature	Description
CustomerID	Unique customer identifier
Tenure	Duration of customer relationship
OrderCount: Total orders placed
CashbackAmount	Cashback rewards received
Complain	Customer complaint history
HoursSpentOnApp	App usage engagement
CityTier	Customer location category
Churn	Target variable (1 = churned, 0 = retained)

>>Total records analyzed: 5000+ customer transactions

Tools & Technologies
Python
Pandas
NumPy
Scikit-Learn
Matplotlib
Seaborn
Jupyter Notebook

>>Analysis Workflow
1️. Data Cleaning
Handled missing values
Removed inconsistent records
Standardized categorical variables
Validated dataset integrity

2️. Exploratory Data Analysis (EDA)
Analyzed:
Customer engagement
Order behavior
Cashback usage
Complaint frequency

Key visualizations included:
Churn distribution
Order frequency vs churn
App engagement vs churn
Complaint impact on retention
Machine Learning Model

A classification model was built to predict churn probability.
Features used
CityTier
HoursSpentOnApp
Complain
Tenure
OrderCount
CashbackAmount

>>Model Pipeline
Train-Test Split (80/20)
Feature Scaling
Model Training
Model Evaluation

The model helps identify customers likely to churn before they leave.

 >>Key Business Insights
1️. Low Engagement Customers Show Highest Churn Risk
Customers placing fewer than 2 orders per month had approximately 2.3× higher churn probability compared to active users.
Business Impact:
Targeted engagement campaigns could potentially reduce churn by 10–15%.

2️. Complaints Strongly Increase Churn
Customers who filed complaints were 3× more likely to churn than customers without complaints.
Business Impact:
Improving complaint resolution time could increase customer retention by 12–18%.

3️.App Engagement Correlates with Retention
Customers spending more than 3 hours per week on the app showed 40% lower churn rates.
Business Impact:
Improving app engagement through personalized recommendations may increase repeat orders by 8–10%.

4️. Cashback Incentives Improve Retention
Customers receiving higher cashback rewards showed significantly higher retention rates.
Business Impact:
Optimized cashback campaigns could improve customer lifetime value by 15–20%.

>>Business Recommendations
1. Target Low-Engagement Customers

Implement personalized promotions for users with low order frequency.
Expected impact:
10–15% churn reduction

2. Improve Delivery Experience

Optimize logistics to reduce delivery delays.
Expected impact:
8–12% increase in repeat orders

3. Improve Complaint Resolution

Introduce faster customer support and issue resolution systems.
Expected impact:
12–18% higher retention

4. Smart Cashback Strategy

Target cashback offers to high-risk customers predicted by the churn model.
Expected impact:
15–20% improvement in customer lifetime value

>>Project Impact
If implemented, these strategies could help the business:

✔ Reduce churn by 10–20%
✔ Increase repeat order frequency
✔ Improve customer satisfaction
✔ Increase overall customer lifetime value
