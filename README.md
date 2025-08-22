Customer Segmentation & Analysis using RFM & K-Means Clustering
Project Overview
This project analyzes a transactional dataset from a UK-based online retail store to identify major customer segments. By leveraging RFM (Recency, Frequency, Monetary) analysis and the K-Means clustering algorithm, this project segments customers into distinct groups based on their purchasing behavior. The final output is an interactive Power BI dashboard that provides actionable insights for targeted marketing and business strategy.

Key Objectives
Data Cleaning & EDA: To process and clean the raw transactional data, handling missing values and preparing it for analysis.

Feature Engineering: To calculate Recency, Frequency, and Monetary (RFM) metrics for each customer.

Machine Learning: To apply K-Means clustering to the RFM data to identify distinct and meaningful customer segments.

Data Visualization: To create a comprehensive and interactive dashboard in Power BI to visualize the findings.

Strategic Recommendations: To derive actionable, data-driven recommendations to help the business improve customer retention and marketing effectiveness.

Tech Stack & Tools
Data Analysis: 🐍 Python (Pandas, NumPy, Scikit-learn)

Data Visualization: 📊 Power BI, Matplotlib, Seaborn

Environment: 📓 Jupyter Notebook

Dataset
The project utilizes the Online Retail II UCI dataset, which contains transactional data for a UK-based online retailer from 2009 to 2011.

Source: Kaggle

Size: Over 1,000,000 transactions.

Methodology
Data Cleaning: The initial dataset was cleaned by removing canceled orders, handling null CustomerID values, and correcting data types. A TotalPrice column was created by multiplying Quantity and Price.

RFM Analysis: For each unique customer, the following metrics were calculated:

Recency: Days since the customer's last purchase.

Frequency: Total number of unique invoices (transactions).

Monetary: Total revenue generated from the customer.

K-Means Clustering:

The RFM values were pre-processed by applying a log transformation to handle skewness and then scaling the data.

The Elbow Method was used to determine the optimal number of clusters (K=4).

The K-Means algorithm was applied to group customers into four distinct segments.

Segment Profiling: Each cluster was analyzed based on its average RFM scores and given a descriptive name:

Champions: Bought recently, buy often, and are high spenders.

At-Risk Loyalists: Were frequent, high-value customers but have not purchased in a while.

New/Promising: Recent customers with low frequency and spend.

Lost Customers: Have not purchased for a long time and have low transaction frequency.

Dashboard Visualization
An interactive dashboard was created in Power BI to present the findings. It provides a high-level summary and allows for deeper exploration of customer segments, geographical data, and revenue trends.

You will need to upload your dashboard image to your GitHub repository and update the image link above.

Key Findings & Recommendations
Segment Distribution: The "Champions" segment is the largest and most valuable group of customers, driving a significant portion of the revenue.

Geographical Concentration: The United Kingdom is the dominant market, accounting for over 80% of total revenue and orders.

Sales Seasonality: The business experiences strong seasonality, with sales peaking in November ahead of the holiday season.

Actionable Insights:

Champions: Nurture this group with loyalty programs and exclusive offers to maintain their high engagement.

At-Risk Loyalists: Launch targeted win-back campaigns with personalized promotions to re-engage them before they are lost.

New/Promising: Develop an onboarding email series to encourage repeat purchases and build loyalty.
