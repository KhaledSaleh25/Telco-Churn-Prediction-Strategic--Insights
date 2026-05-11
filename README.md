Telco Churn Analysis: Full-Stack Data Project
This project is an end-to-end analysis of customer churn in the telecom industry. I built this to demonstrate a complete data workflow: from querying raw data with SQL, to building a predictive model in Python, and finally designing a strategic dashboard in Power BI.

Data Source
The dataset used is the IBM Telco Customer Churn dataset. It contains information about 7,043 customers and 21 features, including demographics, account details, and services provided.
Dataset Link: https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset

Tools Used
SQL: For data profiling, validation, and answering core business questions.
Python: For Exploratory Data Analysis (EDA) and building a Random Forest predictive model.
Power BI: To design a professional, interactive dashboard for executive storytelling.

The Workflow
Data Exploration (SQL)
I started by querying the database to validate the numbers and understand the customer base:
Calculated the overall churn rate (approx. 26.5%).
Segmented customers by contract type and internet service to find high-risk zones.
Identified the top reasons for churn, highlighting Support Attitude as a major internal issue.

Machine Learning (Python)
Using Pandas and Scikit-Learn, I analyzed the drivers behind the data:
Correlation Analysis: Proved that features like Contract Type and Monthly Charges are the heaviest drivers, while Gender has zero impact.
Predictive Modeling: Built a Random Forest Classifier to predict at-risk customers.
Finding: Month-to-Month contracts increase churn probability by 6.3x.

Interactive Dashboard (Power BI)
I designed a 3-page dashboard focused on actionable insights:
Executive Overview: High-level KPIs, churn trends, and demographics.
Strategic Insights: Deep dive into payment methods and service vulnerabilities.
AI Page: Utilizing the Key Influencers visual to show the mathematical probability of churn.

Key Business Takeaways
Contract Risk: Month-to-Month plans are the biggest risk factor; migrating these users to annual plans is a priority.
Payment Impact: Customers using Electronic Checks churn significantly more than those on automatic payment methods.
Service Vulnerability: Fiber Optic users are more likely to leave due to high costs and aggressive competitor offers.

Project Screenshots
Executive Dashboard (Overview)

Strategic Insights and Recommendations

AI-Powered Churn Drivers (Key Influencers)

Repository Content
/Sql: SQL queries used for EDA and validation.
/Py.analysis: Jupyter Notebook containing the ML model.
/Power bi: The final .pbix dashboard file.

Contact
Khaled Saleh
Software Developer and Data Enthusiast
LinkedIn Profile: www.linkedin.com/in/khaled-saleh11
