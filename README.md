# Customer Segmentation with RFM and KMeans

## Overview

This project aims to assist businesses in creating targeted marketing strategies by segmenting their customer base. By analyzing customer behavior through RFM (Recency, Frequency, Monetary) metrics and applying the KMeans clustering algorithm, this project identifies distinct customer segments that can help in personalized marketing and strategic decision-making.

## Project Components

1. **Database Management:**
   - **Data Import:** Customer, order, and product data are imported into an SQLite database.
   - **Data Export:** Processed data, including the RFM metrics and customer segments, are stored in the database.

2. **RFM Analysis:**
   - **Recency:** Measures the number of days since the customer's last purchase.
   - **Frequency:** Counts the number of purchases made by the customer.
   - **Monetary:** Calculates the total spending of the customer.

3. **KMeans Clustering:**
   - **Data Scaling:** Normalizes the RFM data to ensure uniform scaling.
   - **Elbow Method:** Determines the optimal number of clusters for KMeans.
   - **Segmentation:** Applies KMeans to classify customers into distinct segments.

4. **Visualization:**
   - **Scatter Plots:** Visualize customer segments based on Recency, Frequency, and Monetary metrics.
   - **Box Plots:** Display the distribution of RFM metrics within each segment.
   - **Segment Distribution:** Shows the count of customers in each value segment.

## Requirements

To run this project, you will need the following Python packages:

- `pandas`
- `scikit-learn`
- `yellowbrick`
- `matplotlib`
- `seaborn`
- `plotly`
- `sqlite3`
