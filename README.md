# Customer Segmentation Project

This repository contains the code and analysis for customer segmentation using an online retail dataset. The project involves data cleaning, exploratory data analysis (EDA), feature engineering, and customer segmentation using machine learning techniques such as K-Means Clustering.

## Project Structure

### Data Cleaning:
Initial processing steps to remove duplicates, handle missing values, and ensure data consistency.
### Exploratory Data Analysis (EDA): 
Visualizing customer purchase patterns, seasonality, and demographics.
### Feature Engineering: 
Creating RFM (Recency, Frequency, Monetary) metrics to quantify customer behavior.
### Customer Segmentation: 
Applying K-Means Clustering to segment customers based on their purchasing habits.
### Model Evaluation: 
Evaluating the clustering performance using the Silhouette Score.

## Data Cleaning
Removed rows with missing CustomerID.
Dropped duplicates and ensured valid data in Quantity and UnitPrice.
Created a new feature TotalPrice, which is the product of Quantity and UnitPrice.

## Exploratory Data Analysis
Visualized total sales by month to identify seasonality.
Analyzed customer purchase frequency and sales by country (Top 10 countries).
Calculated average basket size and revenue per customer.

## Feature Engineering
### Created RFM metrics:
Recency: How recently a customer made a purchase.
Frequency: How often a customer made purchases.
Monetary: How much a customer spent in total.

## Customer Segmentation
Used K-Means Clustering to segment customers into distinct groups based on their RFM scores.
Identified optimal clusters using the Elbow Method and evaluated the model with a Silhouette Score of 0.616.

## Technologies Used
Python for data analysis and machine learning.
Pandas for data cleaning and manipulation.
Matplotlib and Seaborn for data visualization.
Scikit-learn for machine learning and clustering.

## Usage
Load the dataset and follow the steps for data cleaning and EDA.
Apply the K-Means Clustering algorithm to segment the customers.
Evaluate the model performance using the Silhouette Score.

## Results
The segmentation successfully identified 4 key customer segments based on their purchase behavior. These segments can be used for targeted marketing and improving customer retention strategies.

## Conclusion:

The analysis of the online retail dataset provided several insights into customer behavior, purchasing patterns, and potential segmentation opportunities. By applying various data cleaning, feature engineering, and clustering techniques, we were able to gain an understanding of key customer characteristics and patterns.

### Customer Purchase Patterns:

The analysis of total sales by month revealed seasonal trends, helping to identify peak purchasing periods.
An exploration of customer purchase frequency showed that most customers make a limited number of purchases, but a few highly engaged customers contribute disproportionately to sales.

### Customer Demographics:

Sales by country analysis highlighted that certain regions contribute significantly more to revenue. Understanding these top-performing regions can guide marketing efforts and resource allocation.

### Key Metrics:

The average basket size and revenue per customer were computed, providing valuable insights into the buying behavior of customers. This information can help optimize marketing campaigns and product offerings.

### Customer Segmentation:

RFM (Recency, Frequency, Monetary) analysis was performed, followed by K-Means clustering, which segmented customers into four distinct clusters based on their purchasing behavior. This segmentation provides actionable insights for tailoring marketing strategies to different customer groups.

### Model Evaluation:

The K-Means model's performance was evaluated using the Silhouette Score, indicating good clustering results with a score of 0.616, suggesting well-defined clusters.

## Summary of Findings:
### Customer Segmentation: 
Using RFM (Recency, Frequency, Monetary) analysis, customers have been divided into four key segments:

#### Cluster 0:
Customers with moderate recency, frequency, and monetary values. These may represent steady and mid-value customers.
#### Cluster 1:
Customers with high recency, low frequency, and low monetary values. These are likely at-risk customers.
#### Cluster 2:
Very recent, highly frequent buyers with high monetary value. These are high-value customers.
#### Cluster 3:
Customers with relatively recent purchases and above-average frequency and monetary values.

### Business Implications:

#### Retention of High-Value Customers (Cluster 2): 
These customers contribute the most in terms of revenue. Focus on loyalty programs, special offers, and personalized services to maintain their engagement.
#### Win-Back Campaigns for At-Risk Customers (Cluster 1):
Customers in this group haven't purchased recently and spend less. Send re-engagement campaigns with discounts or exclusive deals to encourage repeat purchases.

### Actionable Insights:
#### Targeted Marketing Campaigns:
Use RFM analysis to create personalized marketing campaigns. For example:
#### High Recency and Low Frequency (Cluster 1): 
Send them reminders about new products or special offers to drive more frequent purchases.
#### High Frequency and High Monetary (Cluster 2): 
Create a VIP loyalty program to keep them engaged and reward them for their loyalty.
#### Loyalty Programs:
Use the RFM segments to design tiered loyalty programs based on spending habits, encouraging repeat purchases and increased basket size.

## Behavioral Improvements:

For at-risk customers (Cluster 1), create urgency through time-limited offers.
For steady buyers (Cluster 0), provide upsell or cross-sell recommendations based on their past purchase history.

## Recommendations:

Targeted Marketing Strategies
Optimize Inventory Based on Seasonality
Focus on High-Value Regions
Customer Engagement




