# Customer Segmentation

This repository contain the code for my portfolio projects I did:

## 1. Data Summary
Provide an overview and summary of the data used for analysis.

## 2. Canceled Data
   ### 2.1 Identify and Match Canceled Orders
   - Identify canceled orders and match them with their original orders.

   ### 2.2 Filter and Refine Data
   - Filter out unnecessary data and refine the dataset.

   ### 2.3 Clean Up Data
   - Remove or correct any remaining issues in the dataset.

## 3. Exploring Data
   ### 3.1 Countries
   - **3.1.1 Top 10 Most Popular and Least Popular Countries by Invoice**
     - Analyze and list the top and bottom 10 countries based on invoice counts.
   - **3.1.2 Top 10 Most Popular and Least Popular Countries by Quantity**
     - Analyze and list the top and bottom 10 countries based on quantity sold.
   - **3.1.3 Distribution of Sales Density and Shape**
     - Explore the distribution of sales density and its shape across regions.
   - **3.1.4 Distribution of Order Price**
     - Analyze the distribution of order prices.
   - **3.1.5 Sales Density by Country**
     - Create a geographical heatmap to show sales density by country.

   ### 3.2 Time Series Analysis
   - **3.2.1 Year**
     - **3.2.1.1 Distribution of Quantity per Year**
       - Analyze the distribution of quantity sold by year.
     - **3.2.1.2 Distribution of Total Customers per Year**
       - Analyze the distribution of total customers by year.
   - **3.2.2 Month**
     - **3.2.2.1 Total Quantity per Month**
       - Analyze the total quantity sold per month.
     - **3.2.2.2 Total Customers per Month**
       - Analyze the total number of customers per month.
     - **3.2.2.3 Total Invoices per Month**
       - Analyze the total number of invoices per month.
   - **3.2.3 Week**
     - **3.2.3.1 Total Transactions by Weekday**
       - Analyze the total number of transactions by weekday.
   - **3.2.4 Day**
     - **3.2.4.1 Total Transactions per Day**
       - Analyze the total number of transactions per day.
   - **3.2.5 Season**
     - **3.2.5.1 Total Quantity by Season**
       - Analyze the total quantity sold by season.
     - **3.2.5.2 Top 3 Products by Sales for Each Season**
       - Identify the top 3 products by sales for each season.
     - **3.2.5.3 Total Orders and Total Sales by Season**
       - Analyze the total number of orders and total sales by season.

## 4. Cohort Analysis
   ### 4.1 Define Cohorts
   - Define the cohorts for analysis.
   ### 4.2 Data Collection and Preparation
   - Collect and prepare data for cohort analysis.
   ### 4.3 Calculate Cohort Metrics
   - Calculate relevant metrics for each cohort.
   ### 4.4 Analyze and Visualize
   - Analyze and visualize cohort metrics.
   ### 4.5 Interpret Results
   - Interpret the results of the cohort analysis.

## 5. RFM Analysis
   ### 5.1 Data Preparation
   - Prepare data for RFM analysis.
   ### 5.2 Calculate RFM Metrics
   - Calculate Recency, Frequency, and Monetary (RFM) metrics.
   ### 5.3 Customer Segmentation - KMeans
   - **5.3.1 Exploring the Data**
     - Explore the data used for segmentation.
   - **5.3.2 Pre-processing the Data**
     - Prepare the data for clustering.
   - **5.3.3 Choosing the Number of Clusters**
     - Determine the optimal number of clusters.
   - **5.3.4 Clustering the Data**
     - **5.3.4.1 Cluster with k=2**
       - Perform clustering with 2 clusters.
     - **5.3.4.2 Cluster with k=3**
       - Perform clustering with 3 clusters and compare results.
   - **5.3.5 Inspecting the Clusters**
     - **5.3.5.a. Visualizing the Raw Values by Cluster**
       - Visualize the raw values for each cluster.
     - **5.3.5.b. Create a Snake Plot of the Clusters**
       - Create a snake plot to show cluster trends.
     - **5.3.5.c. Create a Heatmap of Relative Importances**
       - Create a heatmap to display relative importances within clusters.
   ### 5.4 Develop Marketing Strategies
   - **5.4.1 Cluster 0: High-Value Customers**
     - **5.4.1.1 Characteristics**
     - **5.4.1.2 Marketing Strategies**
   - **5.4.2 Cluster 1: Low-Value or Potentially At-Risk Customers**
     - **5.4.2.1 Characteristics**
     - **5.4.2.2 Marketing Strategies**
   - **5.4.3 Cluster 2: Medium-Value Customers**
     - **5.4.3.1 Characteristics**
     - **5.4.3.2 Marketing Strategies**
   - **5.4.4 Additional Recommendations**