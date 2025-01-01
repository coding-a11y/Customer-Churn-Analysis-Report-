# Customer-Churn-Analysis-Report-
### Dashboard Link  - https://app.powerbi.com/links/7_Myoy_5Rn?ctid=a1a4ee51-99fa-437d-8ba7-d05192f6c077&pbi_source=linkShare

![image](https://github.com/user-attachments/assets/5680b7c5-a905-424a-8132-0c7a2e7e9322)

![image](https://github.com/user-attachments/assets/b4c4b9af-39bc-41a2-a0ad-df363b013137)


## Problem Statement and Objective

Customer Churn Analysis Report: Power BI Project Overview
The Customer Churn Analysis project aims to uncover insights into customer behavior, identify churn drivers, and provide actionable metrics to reduce customer attrition. The entire process involves extracting data, preparing it for analysis, and creating intuitive visualizations in Power BI. Below is a comprehensive breakdown of the project steps:

1. Data Extraction
The first step in this project involved importing raw data from multiple sources into Power Query. The data included customer demographics, transaction history, service usage details, and customer support interactions.

Sources of Data: CSV files, SQL databases, and CRM tools.
Power Query Use: Connected to these sources, combining them into a unified dataset for analysis.
2. Data Preprocessing and Cleaning
Raw data is rarely analysis-ready, so extensive preprocessing was performed in Power Query. This phase included:

Removing Duplicates and Inconsistent Records: Identifying and removing duplicate rows to ensure data integrity.
Handling Missing Values: Using techniques such as imputation (mean/median) or exclusion for missing values in numerical and categorical columns.
Formatting Data Types: Correcting column formats like dates, numerical fields, and text to ensure seamless transformations.
Data Transformation:
Splitting complex fields into multiple columns (e.g., separating "Full Name" into "First Name" and "Last Name").
Aggregating customer transaction data to calculate metrics such as average revenue per user (ARPU).
3. Data Analysis and Feature Engineering
This phase involved creating calculated columns and measures to support churn analysis, including:

Churn Indicator: A binary column (Churn = Yes/No) based on predefined conditions like service cancellations.
Customer Lifetime Value (CLV): A calculated metric derived from revenue, tenure, and transaction frequency.
Categorical Segmentation: Grouping customers into cohorts based on usage patterns, geography, and demographics.
4. Data Visualization
The cleaned and enriched data was loaded into Power BI for visualization. Key steps included:

Dashboard Layout Design: Structuring the report with logical sections for KPIs, trend analysis, and churn predictions.
Visuals Used:
Bar Charts and Pie Charts: For demographic and churn percentage breakdowns.
Line Charts: To show churn rates and revenue trends over time.
Heatmaps: To highlight service usage patterns correlated with churn.
Slicers and Filters: To allow stakeholders to analyze data by region, tenure, and other dimensions.
5. KPIs and Strategic Insights
Key Performance Indicators (KPIs) were created to enable quick, actionable insights:

Overall Churn Rate: The percentage of customers lost over a specified period.
Retention Rate: Calculated as 1 - Churn Rate, indicating the percentage of customers retained.
Revenue Impact: Quantifying the financial effect of churn using revenue lost from churned customers.
Tenure Analysis: Visualizing the average tenure of churned vs. retained customers.
Interactive visuals were created to showcase KPIs with dynamic updates based on user-selected filters.

6. Insights and Recommendations
The analysis revealed critical insights such as:

High churn rates in specific customer cohorts (e.g., first-year users).
Correlation between low product usage and high churn probability.
The need for targeted loyalty programs to improve retention in high-risk segments.
7. Presentation and Sharing
The Power BI report was published to the Power BI Service for easy access and collaboration. Role-based access was configured to ensure data security.

This Customer Churn Analysis Report is a comprehensive tool that combines advanced analytics and visualization to empower decision-makers with actionable insights to reduce customer churn effectively.
