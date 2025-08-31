# Market-Basket-Analysis
Market Basket Analysis 🛒

Author: Rituparna Das
Date: 2025-08-31

#Overview

Market Basket Analysis (MBA) is a data mining technique used to uncover associations or relationships between items that customers frequently purchase together. This project demonstrates the process of performing MBA on a retail dataset to derive actionable insights for cross-selling, bundling, and recommendation systems.

#Dataset

Source: Online Retail Dataset https://archive.ics.uci.edu/dataset/352/online+retail

#Description:

Columns include: InvoiceNo, StockCode, Description, Quantity, InvoiceDate, UnitPrice, CustomerID, Country

Example transaction: customers buying multiple items in a single invoice.

#Tools & Technologies

Python 3.x

Pandas & NumPy for data manipulation

mlxtend for Apriori and Association Rules

 Google Colab

Matplotlib / Seaborn for visualizations

#Steps Performed

Data Preprocessing

Filtered data for specific country or period

Removed missing or invalid entries

Converted data to one-hot encoding (transaction × item matrix)

Frequent Itemset Mining

Used the Apriori algorithm to find frequently purchased itemsets

Configured minimum support to identify meaningful combinations

Association Rule Mining

Generated rules using confidence, lift, and other metrics

Filtered rules to remove irrelevant items (e.g., POSTAGE)

#Insights & Analysis

Identified strong product-to-product associations

Suggested bundling, cross-sell, and recommendation opportunities



