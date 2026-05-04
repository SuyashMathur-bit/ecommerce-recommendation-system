This project builds a Customer Segmentation and Recommendation System using real-world e-commerce transaction data.

It uses unsupervised learning to:

Segment customers based on behavior
ecommend products based on similar users

Tech Stack

Python 
Numpy
Pandas
Scikit-learn


Features Implemented

1️) Data Preprocessing
Removed missing Customer IDs
Removed negative transactions (returns)
Created TotalPrice feature
Converted date into datetime format

2️) RFM Feature Engineering
Recency → Days since last purchase
Frequency → Number of purchases
Monetary → Total spending

3️) Customer Segmentation
Used K-Means Clustering to group customers:
High-value customers 
Frequent buyers 
Inactive customers 

4️) Product Recommendation System
Merged cluster info with transaction data
Found top products per cluster
Recommended products based on customer cluster


