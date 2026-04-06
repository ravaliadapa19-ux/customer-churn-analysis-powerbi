# customer-churn-analysis-powerbi

Project Overview

This project focuses on analyzing customer churn using Microsoft Power BI.
The goal is to identify why customers are leaving and provide actionable insights to improve customer retention.

Problem Statement

Many customers are leaving the service, leading to high churn rates.
It is difficult to understand the reasons by just looking at raw data.

👉 This project helps to:

Identify high-risk customers
Understand key factors affecting churn
Provide insights to reduce churn
📂 Dataset Description

The dataset includes:

Customer ID (unique identifier)
Demographics (Gender, Senior Citizen, Partner, Dependents)
Services (Phone, Internet, Online Security, Backup, etc.)
Billing Information (Monthly Charges, Total Charges, Payment Method)
Contract Type
Churn Status (Yes/No)

🧹 Data Cleaning:
Handled missing values in TotalCharges
Converted data types (text, numeric)
Replaced values (0/1 → No/Yes)
Standardized column values
Verified data quality

🔗 Data Modeling:
Single table model used
Created calculated columns
Built DAX measures like:
Churn Rate
Customer Count
Average Charges

📈 Dashboard Features:
👥 Customer Demographics:
Equal distribution of male and female customers
Higher churn in low tenure (new customers)

📡 Service Analysis:
Fiber optic users show higher churn
Customers with fewer services are more likely to leave

💳 Contract & Billing Insights:
Month-to-month contracts have highest churn
Paperless billing shows slightly higher churn
Long-term customers stay longer

🔍 Key Insights
Customers with month-to-month contracts churn more
New customers (low tenure) are at high risk
Fiber internet users have higher churn
Customers with fewer services tend to leave
Churn leads to revenue loss

✅ Recommendations
Offer discounts for long-term contracts
Improve fiber internet service quality
Provide offers for new customers
Promote add-on services
Focus on high-risk customer support

🎯 Conclusion

Customer churn is mainly influenced by:

Contract type
Tenure
Services used

By improving services and offering better plans, businesses can reduce churn and increase customer retention.

🛠 Tools Used
Microsoft Power BI
DAX (Data Analysis Expressions)
