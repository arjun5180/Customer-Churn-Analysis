📉 Customer Churn Analysis – Telecom Dataset
🔍 Analyzing why customers leave and identifying patterns using Python EDA

🗂️ Project Overview
This project focuses on performing exploratory data analysis (EDA) on a telecom customer churn dataset to understand the factors that influence customer attrition. The goal is to derive actionable insights that can help telecom companies predict churn and retain valuable customers.

📌 Dataset Description
Total Records: 7,043 customer entries

Columns: 21 features including tenure, MonthlyCharges, Contract, PaymentMethod, InternetService, gender, and Churn

Target Variable: Churn (Yes/No)

🛠️ Tools & Libraries Used
Python

Pandas, NumPy – data cleaning and manipulation

Matplotlib, Seaborn – visual analysis

Plotly – interactive plots

Jupyter Notebook – exploratory workflow

📊 Key EDA Steps
Handled missing values in TotalCharges

Converted categorical features using label encoding

Visualized churn rate across:

Contract Types (Month-to-month users churn more)

Tenure Groups (New users are more likely to churn)

Internet Service Type (Fiber Optic has high churn)

Payment Method (Electronic check users churn the most)

Created custom buckets for tenure and charges to improve interpretability

Plotted correlation heatmaps and churn distributions by multiple features

🔍 Key Insights
Customers on monthly contracts churn at a much higher rate

Senior citizens are slightly more likely to churn

Users with high monthly charges tend to leave

Customers using electronic check are risk-prone

Fiber optic service customers show higher dissatisfaction

✅ Outcome
This EDA serves as a foundation for churn prediction modeling and offers business intelligence teams the insights needed to design targeted retention strategies.



