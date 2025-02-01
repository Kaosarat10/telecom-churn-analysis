# **Customer Churn Analysis**

## **Introduction**
This project focuses on customer churn analysis, identifying factors influencing customer retention and churn. The analysis was performed using **Excel** for data preparation and **Power BI** for dashboard creation, incorporating **calculated columns** and **DAX measures** to extract meaningful insights.

---

## **Project Aim**
This project analyzes customer churn and retention trends within a **telecom company**. It aims to:
- Identify key factors influencing churn.
- Understand customer retention patterns.
- Provide **strategic recommendations** to improve retention and reduce churn.

The findings will help engagement partners make **data-driven decisions** to enhance customer satisfaction and business performance.

---

## **Project Description**
The **Telecom Churn and Retention Analysis** focuses on understanding the characteristics of churned customers and retention trends. Using **Power BI dashboards**, the project explores:
- **Customer demographics** and their relationship with churn.
- Churn trends based on **contract type, payment method, and internet service**.
- Retention rates across different customer segments.
- **Revenue contribution** from retained customers.

Using interactive visualizations, the analysis uncovers insights that will help improve **retention strategies, customer engagement, and long-term revenue growth**.

---

## **Key Insights Derived**
The analysis aims to answer the following questions:
- **What are the key customer demographics influencing churn?**
- **What is the overall churn rate?**
- **What factors contribute to customer churn?**
- **How does customer retention vary across different segments?**
- **What strategies can improve customer retention?**

---

## **Data Acquisition and Preparation**
The dataset analyzed was part of a **Power BI job simulation project**, containing customer attributes such as **demographics, service usage, tenure, and churn status**.

### **Data Cleaning**
The following steps ensured data accuracy and consistency:
- **Filtering Data:** Removed irrelevant or inconsistent records.
- **Ensuring Data Consistency:** Assigned correct data types to each column.
- **Handling Missing Values:**
  - Removed blank values that were not relevant.
  - Replaced blanks with zero where necessary (**for numerical columns**).
- **Data Transformation in Power BI:**
  - Created additional **calculated columns** for improved readability.
  - Developed **DAX measures** to analyze customer churn and retention trends.

### **Data Transformations**
#### **Calculated Columns**
- **Citizen Status** – Transformed the `SeniorCitizen` column (**1/0**) into **"Senior Citizen"** and **"Non-Senior Citizen"** for better clarity.
- **Tenure Ranges** – Grouped customer tenure into meaningful time-based categories for improved dashboard readability.

#### **DAX Measures**
- **Total Customers** – Counts the total number of customers.
- **Total Tech Support Tickets** – Calculates the total number of technical support tickets logged.
- **Senior Citizen Count** – Counts the number of senior citizens.
- **Customer Lifetime Value (CLV)** – Computes the average total revenue from retained customers.
- **Churn Rate** – Calculates the percentage of customers who have churned.
- **Total Churned Customers** – Counts the total number of churned customers.
- **Percentage of Senior Citizens** – Determines the proportion of senior citizens among all customers.
- **Percentage of Non-Senior Citizens** – Determines the proportion of non-senior citizens among all customers.

---

## **Data Analysis and Visualization**
In **Power BI**, I used various visualizations to create insightful dashboards for customer demographics, churn analysis, and customer retention. 

#### **Visualization Tools Used:**
- **Doughnut Charts**
- **Clustered Column Charts**
- **Clustered Bar Charts**
- **Area Charts**
- **Cards**

To enhance interactivity, I utilized **Slicers**, allowing users to dynamically filter and analyze specific segments of the data.

---

## **Dashboards and Insights**

### **1️⃣ Customer Demographics Dashboard**
This dashboard provides an overview of the customer base, highlighting key demographic distributions and revenue insights.

**Visuals Included:**
- **Doughnut Chart:** Gender distribution.
- **Column Chart:** Customers by payment method.
- **Doughnut Chart:** Paperless billing adoption.
- **Column Chart:** Senior citizen vs. non-senior citizen distribution.
- **Doughnut Chart:** Revenue by citizen status.
- **Cards:** Total Customers, Total Revenue, Average Monthly Charges, Admin & Tech Ticket Counts.

📌 **Dashboard Screenshots:**

### 📊 Customer Demographics  
![Customer Demographics](Customers%20demographics.png)

---

### **2️⃣ Churn Analysis Dashboard**
This dashboard analyzes customer churn trends, helping to identify high-risk groups and retention opportunities.

**Visuals Included:**
- **Column Chart:** Churn by internet service type.
- **Clustered Bar Chart:** Churn by payment method.
- **Area Chart:** Churn trends by tenure.
- **Doughnut Chart:** Churn by gender.
- **Cards:** Customers at Risk, Total Revenue, Churn Rate, Average Monthly Charges.

📌 **Dashboard Screenshot:** 

### 📉 Churn Analysis  
![Customers Churn Dashboard](Customers%20Churn%20Dashboard.png)



---

### **3️⃣ Customer Retention Dashboard**
This dashboard focuses on retention patterns and factors influencing long-term customer engagement.

**Visuals Included:**
- **Doughnut Chart:** Retention by partner status.
- **Doughnut Chart:** Retention by citizen status.
- **Column Chart:** Retention by phone service.
- **Column Chart:** Retention by internet service.
- **Bar Chart:** Retention by tenure range.
- **Cards:** Retention Rate, Active Customers, Average CLV, Total Revenue, Average Monthly Charges.

📌 **Dashboard Screenshot:** 

### 🔄 Retention Analysis  
![Customers Retention Dashboard](Customers%20Retention%20Dashboard.png)
---

## **Interpretation of Data**
### **Churn Insights – Who is Leaving and Why?**
- **Churn Rate:** 27% (1,869 customers lost).
- **Internet Service Impact:** Fiber Optic users have the highest churn.
- **Demographics:** Non-Senior Citizens account for 75% of churned customers.
- **Contract Type:** Month-to-month contracts have the highest churn rate (43%).
- **Payment Method Influence:** Electronic Check users have the highest churn.

### **Retention Insights – Who is Staying and Why?**
- **Retention Rate:** 73% (Generating $13.19M in revenue from retained customers).
- **Service Type Influence:** DSL and Phone Services have the highest retention.
- **Contract Stability Matters:** 1-year and 2-year contracts improve retention.

---

## **Strategic Recommendations – How to Reduce Churn?**
✅ **Encourage Month-to-Month Customers to Switch to Longer-Term Contracts**
- Offer **loyalty discounts** for long-term plans.
- Educate customers on cost savings and benefits.

✅ **Address Fiber Optic Churn with Targeted Interventions**
- Conduct **customer feedback surveys** to identify pain points.
- Offer exclusive service enhancements.

✅ **Reduce Churn Among Electronic Check Users**
- Investigate **payment issues** or delays.
- Promote alternative payment methods (Credit Card, Bank Transfer).

✅ **Enhance Engagement with Non-Senior Citizens**
- Introduce tailored **marketing campaigns** for younger customers.
- Offer bundled services and retention-focused discounts.

By aligning these insights with strategic actions, engagement partners can **reduce churn, boost customer loyalty, and drive long-term revenue growth**.


