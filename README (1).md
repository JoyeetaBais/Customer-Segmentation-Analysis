# Customer Segmentation Analysis
OVERVIEW:
This project involves analyzing customer data to perform segmentation based on income and spending patterns. The insights are visualized in a Power BI dashboard, and clustering is implemented using an ML model in Google Colab.

TOOLS AND TECHNOLOGIES-
* Google Colab: Building and training the machine learning model
* Python: Used for data cleaning, processing and clustering
* Power BI: Interactive data visualization

PROJECT WORKFLOW-
This project involves multiple stages, from data cleaning to machine learning and visualization. Below is the complete workflow:
1. Data Cleaning and Preprocessing:
* The original dataset was cleaned and processed to handle missing values, remove duplicates, and ensure data consistency.
* Features like Annual Income, Spending Score, and Gender were prepared for analysis.
2. Clustering with K-Means:
* K-Means clustering was applied in Google Colab to segment customers into distinct groups based on income and spending patterns.
* The optimal number of clusters was determined using the Elbow Method.
3. Clustered Data Export:
* The processed dataset, enriched with cluster labels, was exported as a CSV file for further visualization.
4. Dashboard Creation in Power BI:
* The processed dataset was imported into Power BI.
* Interactive visualizations, such as cluster descriptions, spending patterns, gender distribution, and age group analysis, were created to extract key insights.
  
       Dashboard-

![Screenshot 2025-01-10 194240](https://github.com/user-attachments/assets/2348b4bf-23ce-48d6-a614-ed51eb3863f0)


* Enhanced visuals with filters, slicers, and drill-down options to make the insights actionable.

HOW TO RUN THIS PROJECT-
1. MACHINE LEARNING MODEL-
  * Open the python script in Jupyter Notebook or open the Colab file directly.
  * Install required libraries.
  * Run the notebook to train the K-means clustering model.
  * Save the output data with cluster labels.
3. POWER BI-
  * Import the processed dataset into Power BI.
  * Use the .pbix file to open the pre-built dashboard or recreate the visuals using imported data.
  * Review interactive dashboard for insights.

KEY INSIGHTS- 
1. Customer Distribution-
 * The majority of customers (81) belong to the "Average" cluster, indicating balanced income and spending patterns.
 * High-income and high-spending customers account for 39 individuals, showcasing a key segment for premium products or services.
 * The "Low Income, High Spend" cluster (23 customers) could signify customers who prioritize discretionary spending despite limited income.
2. Spending Behavior:
 * The top-performing cluster by spending score is "High Income, High Spend," with an average score of 82.13, representing the most valuable customer group.
 * The "Low Income, High Spend" cluster has a notable spending score of 79.36, which could indicate potential financial strain or a preference for high-value purchases.
3. Income-to-Spending Ratio:
 * The overall income-to-spending ratio is 1.21, reflecting a moderate balance between income and spending across all clusters.
 * Clusters with lower ratios may represent overspending or high-value-focused customer behaviors.
4. Gender Distribution:
 * Males constitute a slightly higher proportion (56%) compared to females (44%), indicating potential for gender-focused marketing strategies.
5. Age Group Analysis:
 * Customers aged 30-40 form the largest group (60 customers), followed by the 20-30 age group (45 customers). These age groups might be the primary target audience for marketing campaigns.
 * The youngest (<20) and oldest (50-70) groups are the smallest segments, with only 17 customers each, suggesting minimal engagement from these demographics.
6. Income and Spending Correlation:
 * The scatter plot demonstrates a clear pattern where higher income often correlates with higher spending scores. However, outliers (e.g., low-income, high-spend customers) highlight unique opportunities or risks.


  
