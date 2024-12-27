# Churn-Analysis
![Could Snowflake Be a Millionaire-Maker Stock_ _ The Motley Fool](https://github.com/user-attachments/assets/2ddbd7b3-4163-4ff3-b57a-1cb42a8c81d2)

This is the official repository for the Churn Dataset.
# Business Problem
The financial services industry's ecosystem is dynamic and multidimensional, characterized by a complex interplay of factors that influence consumer behaviors. In this complex environment, the ability to retain customers is more than a strategic advantage; it is a requirement for long-term growth and sustainability. The inherent challenges of customer attrition for financial institutions include substantial revenue loss and the erosion of brand loyalty. As a result, a Canadian bank facing challenges in retaining its customer base reached out to Datafied Technologies. The bank is experiencing customer churn, impacting overall customer satisfaction and revenue, as well as they lack insights into the factors influencing customer decisions to leave or stay with the bank. There is a need to identify and address factors contributing to customer churn proactively and to do that, they provided a churn database containing information on 10,000 bank customers over six months. 
#   Dataset Information
The churn dataset contains customer information for a bank. Below is the dataset's structure and details:

- Number of Records: 10,000
- Number of Attributes (Columns): 14
  
## Column Descriptions:

- CustomerId: Unique identifier for each customer (numeric).
- Surname: Last name of the customer (text).
- CreditScore: Customer's credit score (numeric).
- Geography: Country where the customer is located (text: e.g., France, Spain).
- Gender: Customer's gender (text: e.g., Male, Female).
- Age: Age of the customer (numeric).
- Tenure: Number of years the customer has been with the bank (numeric).
- Balance: Bank account balance (numeric).
- NumOfProducts: Number of bank products the customer is using (numeric).
- HasCrCard: Whether the customer owns a credit card (binary: 1 = Yes, 0 = No).
- IsActiveMember: Whether the customer is an active bank member (binary: 1 = Yes, 0 = No).
- EstimatedSalary: Estimated annual salary of the customer (numeric).
- Churned: Whether the customer churned (binary: 1 = Yes, 0 = No).
- Male: Column appears to be unused, with all null values.
# Project Objective 
The primary goal of analyzing the churn dataset is to identify patterns and key factors contributing to customer attrition in a banking context. By leveraging this data, the analysis aims to:
- Understand Customer Behavior: Explore attributes like credit score, tenure, balance, and activity status to understand how they influence customer retention.
- Predict Churn: Develop a predictive model to identify customers at high risk of leaving the bank.
- Inform Decision-Making: Provide actionable insights to help the bank improve customer satisfaction, loyalty, and retention strategies.
- Define Business Questions and Metrics: We defined specific business questions that the dashboard should answer. Example questions include:
- How does number of products and salary affect Churn rate?
- What age group and gender has the most churn rate?
- What are the primary factors driving customer churn?
- What products or incentives could reduce churn rates?
  #   Create visualizations and charts:
 Appropriate chart types (e.g., bar charts, line charts, pie charts) were used to represent the metrics and insights. Interactive features such as filters were used for detailed information.
![Screenshot 2024-12-27 174516](https://github.com/user-attachments/assets/efdcd731-848e-4fb5-8d23-1a756419d3bd)
 #   Dashboard Testing and Refinement:
To ensure the dashboard meets the project's requirements, I had the opportunity to schedule one-on-one sessions with my instructor. These sessions provided valuable feedback on my progress and highlighted areas for improvement. Based on the feedback, I made necessary adjustments to the dashboard layout, refined the visualizations, and enhanced the insights to better align with the project's objectives.
 #   Insights:
- Total customers: 10,000, with 20.37% churned (2,037) and 79.63% retained (7,963). The average credit score is 651.
- In France, male churn (350) is lower than female churn (460). In Germany, female churn (448) exceeds male churn (366), while in Spain, female churn (231) slightly exceeds male churn (182).
- The 30-39 age group has the highest number of customers, followed by the 40-49 age group, while the 70 and above age group has the lowest customer count.
- Most customers (50.84%) use 1 product, followed by 2 products (45.9%), with only 2.66% using 3 or 4 products.
- Customers using 4 products have the highest average estimated salary, with salary increasing consistently as the number of products increases.
- The churn rate is highest among customers aged 40-49, while younger customers (18-29) and older customers (70 and above) have lower churn rates.
- Retention efforts should focus on the 40-49 age group, as they exhibit the highest churn rate. Customers using only 1 product should be encouraged to adopt more products to reduce churn.
- Geographic strategies should target female customers in Germany and male customers in France to address their higher churn rates.
-Upselling additional products to high-salary customers can enhance retention, as higher product usage correlates with loyalty.
 #   Recommendations:
- Focus retention efforts on customers aged 40-49, as they have the highest churn rate.
- Encourage single-product customers (50.84%) to adopt more products through discounts, bundles, or loyalty rewards.
- Address female customer churn in Germany and male customer churn in France with tailored retention campaigns.
- Upsell additional products to high-salary customers, as they are more likely to stay loyal with increased engagement.
- Monitor and engage inactive customers with personalized offers or incentives to reduce their likelihood of churn.
- Use predictive analytics to identify at-risk customers early and deploy targeted retention strategies.
- Educate customers about the benefits of multiple products and how to maximize their account value.
- Continuously track churn trends by geography, age group, and product usage to refine strategies.
 #   Documentation
 The project process and deliverables are documented here on GitHub.









