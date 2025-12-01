# 📊 Customer Shopping Behavior Analytics
This project focuses on analyzing customer shopping patterns to help a retail business understand its consumers and make data-driven strategic decisions. The goal is to uncover purchase trends across demographics, product categories, spending habits, and customer segments to support better marketing, improved customer engagement, and increased revenue.
 Using real-world customer shopping behavior data, this project demonstrates how raw data can be transformed into meaningful business insights through data processing, database querying, and interactive visualization.
# The workflow includes:
* Data preparation and transformation using Python
* Structured querying and analysis using SQL
* Interactive dashboard development using Power BI <br>

![Workflow](https://github.com/sayalipatil1929/Consumer-Shopping-Behavior-Analytics/blob/main/Workflow.png)
### The final deliverables provide a comprehensive understanding of customer preferences, loyalty behavior, and sales drivers — enabling businesses to optimize promotions, personalize engagement, and improve decision-making.
---
# 📌 1.Business Problem Statement
* A leading retail company wants to better understand its customers' shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty. The management team has noticed changes in purchasing patterns across demographics, product categories, and sales channels (online vs. offline). They are particularly interested in uncovering which factors, such as discounts, reviews, seasons, or payment preferences, drive consumer decisions and repeat purchases.
  
--- 
# 🛠️ 2.Data Preparation & Transformation
* Loaded and inspected the dataset to understand data types, missing values, and structure before processing.
* Cleaned and standardized categorical fields (such as Gender, Category, Payment Method, Size, and Location) to ensure consistency in analysis.
* Handled missing and duplicate records to improve data quality and ensure accurate insights.
* Converted relevant columns to correct data types (numeric formatting for purchase amount and categorical encoding where needed).
* Created additional derived fields to support analysis, such as customer segmentation and grouping for Power BI visuals.<br>
🔗 You can view the complete data cleaning and transformation steps here:
👉 **[Open Notebook](https://github.com/sayalipatil1929/Consumer-Shopping-Behavior-Analytics/blob/main/customer_shopping_behavior_data_prep.ipynb)**

---
# 🧠 3.Data Analysis in SQL
* Identified key business insights such as revenue distribution by customer demographics, spending behavior, and subscription impact.
* Analyzed the effect of discounts, reviews, and shipping types on purchase amounts using aggregation and conditional filtering.
* Used window functions and ranking to find top-performing products across different categories.
* Applied customer segmentation logic to classify users into New, Returning, and Loyal groups.
* Generated insights to support visualization and decision-making by summarizing trends such as product demand and revenue contribution by age groups.<br>
🔗 View Full SQL Script:
👉 **[Open SQL script](https://github.com/sayalipatil1929/Consumer-Shopping-Behavior-Analytics/blob/main/customer_behavior_an.sql)**

--- 
# 📊 4.Power BI Interactive Dashboard Insights
* The dashboard provides a high-level overview of customer activity, including total customers, orders, average rating and total revenue.
* A donut chart highlights the comparison between subscribed and non-subscribed customers, showing clear engagement patterns.
* Visuals such as seasonal and category revenue charts help identify high-performing product groups and peak purchasing periods.
* Demographic insights like age-wise spending and gender filters allow users to explore how different customer segments contribute to revenue.
* Filters for category, payment method, location, and gender enable stakeholders to interact with the data and uncover customized insights for decision-making.
  
 ![Dashboard](https://github.com/sayalipatil1929/Consumer-Shopping-Behavior-Analytics/blob/main/dashboard.png)
