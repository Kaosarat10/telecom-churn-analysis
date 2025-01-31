Introduction
This project focuses on customer churn analysis, identifying factors influencing customer retention and churn. The analysis was performed using Excel for data preparation and Power BI for dashboard creation, incorporating calculated columns and DAX measures to extract meaningful insights.
Project Aim
This project analyzes customer churn and retention trends within a telecom company. It aims to identify key factors influencing churn, understand customer retention patterns, and provide strategic recommendations to improve customer retention and reduce churn. The findings will help engagement partners make data-driven decisions to enhance customer satisfaction and business performance
Project Description
The Telecom Churn and Retention Analysis focuses on understanding the characteristics of churned customers and retention trends in a telecom company. By leveraging Power BI dashboards, the project explores:
•	Customer demographics and their relationship with churn
•	Churn trends based on contract type, payment method, and internet service
•	Retention rates across different customer segments
•	Revenue contribution from retained customers
Using interactive visualizations, the analysis uncovers insights that will help improve retention strategies, customer engagement, and long-term revenue growth.
Key Insights Derived
The analysis aims to answer the following questions:
•	What are the key customer demographics influencing churn?
•	What is the overall churn rate?
•	What factors contribute to customer churn?
•	How does customer retention vary across different segments?
•	What strategies can improve customer retention?
Data Acquisition and Preparation
The dataset was analyzed as part of a Power BI job simulation project and contained customer attributes such as demographics, service usage, tenure, and churn status.
Data Cleaning 
The following steps were taken to ensure data accuracy and consistency:
•	Filtering Data: Removed irrelevant or inconsistent records.
•	Ensuring Data Consistency: Assigned the correct data types to each column.
•	Handling Missing Values:
o	Removed blank values that were not relevant.
o	Replaced blanks with zero where necessary (for numerical columns).
•	Data Transformation in Power BI:
o	Created additional calculated columns for improved readability.
o	Developed DAX measures to analyze customer churn and retention trends.
Data Transformations
Calculated Columns
1.	Citizen Status – Transformed the SeniorCitizen column (1/0) into "Senior Citizen" and "Non-Senior Citizen" for better clarity in analysis.
2.	Tenure Ranges – Grouped customer tenure into meaningful time-based categories to improve readability in the dashboard.
DAX Measures
To gain deeper insights, several DAX measures were created:
1.	Total Customers – Counts the total number of customers.
2.	Total Tech Support Tickets – Calculates the total number of technical support tickets logged.
3.	Senior Citizen Count – Counts the number of customers who are senior citizens.
4.	Customer Lifetime Value (CLV) – Computes the average total revenue from retained customers.
5.	Churn Rate – Calculates the percentage of customers who have churned.
6.	Total Churned Customers – Counts the total number of churned customers.
7.	Percentage of Senior Citizens – Determines the proportion of senior citizens among all customers.
8.	Percentage of Non-Senior Citizens – Determines the proportion of non-senior citizens among all customers.

Data Analysis and Visualization
In Power BI, I used various visualizations to create insightful dashboards for customer demographics, churn analysis, and customer retention. I incorporated Doughnut Charts, Clustered Column Charts, Clustered Bar Charts, Area Charts, and Cards to present key business insights effectively.
To enhance interactivity, I utilized Slicers, which allow users to dynamically filter and analyze specific segments of the data. This makes the dashboards more flexible, enabling team members to explore insights from different perspectives and make data-driven decisions collaboratively.
The figures below display the dashboards built based on the analysis of the dataset:
1. Customer Demographics Dashboard
This dashboard provides an overview of the customer base, highlighting key demographic distributions and revenue insights.
•	Doughnut Chart: Gender distribution.
•	Column Chart: Customers by payment method.
•	Doughnut Chart: Paperless billing adoption.
•	Column Chart: Senior citizen vs. non-senior citizen distribution.
•	Doughnut Chart: Revenue by citizen status.
•	Cards: Total Customers, Total Revenue, Average Monthly Charges, Admin & Tech Ticket Counts.
2. Churn Analysis Dashboard
This dashboard analyzes customer churn trends, helping to identify high-risk groups and retention opportunities.
•	Column Chart: Churn by internet service type.
•	Clustered Bar Chart: Churn by payment method.
•	Area Chart: Churn trends by tenure.
•	Doughnut Chart: Churn by gender.
•	Cards: Customers at Risk, Total Revenue, Churn Rate, Average Monthly Charges.
3. Customer Retention Dashboard
This dashboard focuses on retention patterns and factors influencing long-term customer engagement.
•	Doughnut Chart: Retention by partner status.
•	Doughnut Chart: Retention by citizen status.
•	Column Chart: Retention by phone service.
•	Column Chart: Retention by internet service.
•	Bar Chart: Retention by tenure range.
•	Cards: Retention Rate, Active Customers, Average Customer Lifetime Value (CLV), Total Revenue, Average Monthly Charges.
Each dashboard was designed to provide actionable insights, making it easier for stakeholders to track trends, understand customer behavior, and develop effective business strategies.

Interpretation of Data
As an engagement partner, understanding customer churn and retention patterns is critical for sustaining long-term profitability. This analysis provides actionable insights to help shape strategic decisions.
1. Churn Insights – Who is Leaving and Why?
The overall churn rate is 27%, meaning 1,869 customers have been lost. The key factors driving churn include:
•	Internet Service Impact: Customers using Fiber Optic services have the highest churn, with 1,297 lost customers. This could indicate issues related to service quality, pricing, or competition.
•	Demographics: Non-Senior Citizens account for 75% of churned customers, suggesting younger users may have higher expectations or different service preferences.
•	Contract Type: Month-to-month customers have the highest churn rate (43%), compared to 11% for 1-year contracts and 3% for 2-year contracts. This indicates that customers with short-term commitments are more likely to leave.
•	Payment Method Influence: Customers using Electronic Check have the highest churn rate. This suggests that those relying on this method may face payment issues or dissatisfaction.
2. Retention Insights – Who is Staying and Why?
The good news is that 73% of customers remain loyal, generating $13.19M in revenue from retained customers. Key patterns include:
•	Service Type Influence: Customers using DSL and Phone Services show the highest retention, suggesting these services meet their expectations.
•	Contract Stability Matters: Customers with longer-term contracts (1-year and 2-year) are more likely to stay, reinforcing the importance of commitment-based plans.

Strategic Recommendations – How to Reduce Churn and Strengthen Retention?
To minimize churn and maximize retention, the following strategies should be prioritized:
🔹 Encourage Month-to-Month Customers to Switch to Longer-Term Contracts
•	Offer loyalty discounts or added benefits for customers who commit to 1-year or 2-year plans.
•	Educate customers on the cost savings and benefits of longer-term subscriptions.
🔹 Address Fiber Optic Churn with Targeted Interventions
•	Conduct customer feedback surveys to understand why Fiber Optic users churn the most and address pain points.
•	Provide exclusive offers or service enhancements to improve satisfaction and encourage retention.
🔹 Reduce Churn Among Customers Using Electronic Check Payment
•	Investigate why customers paying via Electronic Check churn at higher rates (e.g., transaction issues, delays, or preference for digital options).
•	Promote alternative payment methods like Credit Card, Bank Transfer, or Mailed Check, which may offer more convenience.
🔹 Enhance Engagement with Non-Senior Citizens
•	Introduce tailored marketing campaigns that cater to younger customers’ preferences.
•	Offer bundled services or discounts designed to retain this high-churn demographic.
By aligning these insights with strategic actions, engagement partners can reduce churn, boost customer loyalty, and drive long-term revenue growth.

