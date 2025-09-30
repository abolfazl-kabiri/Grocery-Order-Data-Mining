# Data Mining Project: Online Grocery Order Analysis

## Project Overview

This project applies key Data Mining techniques to a large dataset of online grocery orders to discover customer purchasing patterns, predict behavior, and derive actionable business strategies. 
## Techniques Implemented

The analysis is structured around three core data mining methodologies, as required by the project:

1.  **Association Rule Mining (Apriori):** Discovering frequent itemsets and generating association rules (e.g., "If a customer buys product A, they are likely to buy product B").
2.  **Regression Analysis (Linear and Ridge):** Predicting continuous numerical outcomes, specifically the time (days) elapsed until a customer places their next order.
3.  **Naive Bayes Classification (GaussianNB):** Classifying customers into segments (e.g., by their favorite shopping department) based on historical order features.

## Dataset

The project utilizes data from the **Instacart Market Basket Analysis**. (not included in this repository due to size)

### File Descriptions
- aisles.csv → Contains aisle IDs and names.
- departments.csv → Contains department IDs and names.
- products.csv → List of products with product name, product ID, aisle ID, and department ID.
- orders.csv → Information about customer orders (order ID, user ID, order time, etc.).
- order_products_prior.csv → Products from users’ prior orders.
- order_products_train.csv → Products from the training set of orders.

