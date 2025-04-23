# Customer-Segmentation-Using-K-Means-Clustering

The python project analyzes mall customer data to identify distinct customer segments using K-Means clustering. It includes data preprocessing, exploratory data analysis, and model evaluation using silhouette scores, with visual insights to guide marketing strategies.
------
# Project Overview

This project focuses on segmenting mall customers into distinct groups using unsupervised learning, specifically K-Means clustering. The goal is to help businesses better understand their customers’ behavior and tailor marketing strategies accordingly.
-----

# Dataset

The dataset used is the Mall Customers dataset, which contains the following features:

-CustomerID
-Gender
-Age
-Annual Income (k$)
-Spending Score (1-100)

----

# Technologies & Libraries
-Python
-Pandas
-NumPy
-Matplotlib
-Seaborn
-Scikit-learn

-----

Exploratory Data Analysis (EDA)
The EDA includes:

Distribution plots for Age, Annual Income, and Spending Score

Pairplots and correlation analysis

Visualizations to identify trends and patterns
------

# Clustering Approach
StandardScaler was used to normalize the data

K-Means clustering algorithm was applied

The Elbow Method and Silhouette Score were used to determine the optimal number of clusters

------

# Results
Customer data was successfully segmented into meaningful groups

Visualizations such as cluster scatter plots were used to interpret the segments

Each cluster represents a unique customer persona based on income and spending habits

----

# Folder Structure

├── Mall_Customers.csv
├── customer_segmentation.ipynb
└── README.md
----

# Conclusion
Customer segmentation helps businesses target specific groups with tailored offerings. This project demonstrates how unsupervised learning can reveal patterns in customer data and support strategic decisions.
