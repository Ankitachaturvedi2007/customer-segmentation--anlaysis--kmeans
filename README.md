# Customer Segmentation using K-Means Clustering

## Project Overview

Customer segmentation is the process of dividing customers into distinct groups based on their characteristics and purchasing behavior.

This project uses **K-Means Clustering** to segment customers based on their **Annual Income** and **Spending Score**. The objective is to identify meaningful customer groups that can help businesses develop targeted marketing and customer engagement strategies.

## Objective

The main objectives of this project are:

* Analyze customer income and spending behavior.
* Identify meaningful customer segments using K-Means clustering.
* Determine the optimal number of clusters using the Elbow Method.
* Visualize the resulting customer segments.
* Generate actionable business insights from the clusters.

## Dataset

The project uses the **Mall Customers Dataset**, which contains information about customers including:

* Customer ID
* Gender
* Age
* Annual Income (k$)
* Spending Score (1-100)

For clustering, the primary features used were:

* **Annual Income (k$)**
* **Spending Score (1-100)**

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Jupyter Notebook

## Methodology

The project follows these steps:

1. Import and inspect the dataset.
2. Perform basic data analysis.
3. Select relevant features for clustering.
4. Scale the selected features.
5. Determine the optimal number of clusters using the Elbow Method.
6. Apply the K-Means clustering algorithm.
7. Visualize the customer clusters and cluster centroids.
8. Calculate cluster-wise average income and spending score.
9. Assign meaningful names to each customer segment.
10. Analyze the distribution and business significance of each segment.

## Optimal Number of Clusters

The **Elbow Method** was used to determine the appropriate number of clusters.

Based on the analysis, **5 clusters** were selected for the final K-Means model.

## Customer Segments

The final model divided 200 customers into five segments:

| Customer Segment          | Customers | Avg. Annual Income (k$) | Avg. Spending Score |
| ------------------------- | --------: | ----------------------: | ------------------: |
| Average Customers         |        81 |                   55.30 |               49.52 |
| High-Value Customers      |        39 |                   86.54 |               82.13 |
| High-Income, Low-Spending |        35 |                   88.20 |               17.11 |
| Low-Value Customers       |        23 |                   26.30 |               20.91 |
| High-Spending, Low-Income |        22 |                   25.73 |               79.36 |

## Key Insights

### 1. Average Customers

This is the largest customer segment with **81 customers**. These customers have moderate income and spending behavior and represent a significant portion of the overall customer base.

### 2. High-Value Customers

There are **39 High-Value Customers** with both high income and high spending scores. This group represents the most valuable customer segment and should be prioritized for retention and loyalty initiatives.

### 3. High-Income, Low-Spending Customers

This segment contains **35 customers** with high average income but relatively low spending. These customers represent a potential growth opportunity because their purchasing behavior does not currently match their financial capacity.

### 4. Low-Value Customers

There are **23 customers** with both low income and low spending scores. They can be targeted with cost-effective promotional strategies rather than high-cost marketing campaigns.

### 5. High-Spending, Low-Income Customers

This group contains **22 customers** with relatively low income but high spending scores. Their strong spending behavior makes customer retention and loyalty strategies particularly important.

## Business Recommendations

* Develop **loyalty and premium programs** for High-Value Customers.
* Use **personalized offers and targeted promotions** to encourage High-Income, Low-Spending customers to increase their spending.
* Focus on **retention strategies and loyalty rewards** for High-Spending, Low-Income customers.
* Use **cost-effective marketing campaigns** for Low-Value Customers.
* Continue engaging Average Customers and create opportunities to move them toward higher-value segments.

## Conclusion

The K-Means clustering model successfully segmented **200 customers into five distinct groups** based on annual income and spending behavior.

The segmentation provides a clearer understanding of different customer profiles and can help businesses make more informed decisions regarding marketing, customer retention, promotions, and resource allocation.

## Project Structure

```text
customer-segmentation-kmeans/
│
├── Customer_Segmentation.ipynb
├── Mall_Customers.csv
└── README.md
```

## Skills Demonstrated

* Data Analysis
* Exploratory Data Analysis
* Data Preprocessing
* Feature Scaling
* K-Means Clustering
* Elbow Method
* Data Visualization
* Customer Segmentation
* Business Insights
* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
