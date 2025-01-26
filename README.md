# Data Science Intern Assignment: eCommerce Transactions Dataset

This repository contains the solution for the **Data Science Intern Assignment**, which involves analyzing an eCommerce Transactions dataset. The tasks include exploratory data analysis (EDA), building predictive models, and deriving actionable insights.

---

## 📝 Overview
You are provided with an eCommerce Transactions dataset consisting of three files:

1. [**Customers.csv**](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)  
   Contains customer-related information:
   - `CustomerID`: Unique identifier for each customer.  
   - `CustomerName`: Name of the customer.  
   - `Region`: Continent where the customer resides.  
   - `SignupDate`: Date when the customer signed up.

2. [**Products.csv**](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)  
   Contains product-related information:
   - `ProductID`: Unique identifier for each product.  
   - `ProductName`: Name of the product.  
   - `Category`: Product category.  
   - `Price`: Product price in USD.

3. [**Transactions.csv**](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)  
   Contains transaction-related information:
   - `TransactionID`: Unique identifier for each transaction.  
   - `CustomerID`: ID of the customer who made the transaction.  
   - `ProductID`: ID of the product sold.  
   - `TransactionDate`: Date of the transaction.  
   - `Quantity`: Quantity of the product purchased.  
   - `TotalValue`: Total value of the transaction.  
   - `Price`: Price of the product sold.
---

## 🎯 Assignment Tasks

### Task 1: Exploratory Data Analysis (EDA) and Business Insights
1. Perform EDA on the dataset to uncover trends, patterns, and anomalies.
2. Derive **at least 5 actionable business insights**.
---

### Task 2: Lookalike Model
Build a Lookalike Model that:
- Takes a user's information as input.
- Recommends **3 similar customers** based on their profile and transaction history.
- Uses both customer and product information.
- Assigns a **similarity score** to each recommended customer.
---

### Task 3: Customer Segmentation / Clustering
1. Perform customer segmentation using clustering techniques.
2. Use customer profile information (from `Customers.csv`) and transaction data (from `Transactions.csv`).
3. Choose any clustering algorithm and number of clusters (2–10).
4. Evaluate using clustering metrics, including the **Davies-Bouldin (DB) Index**.
5. Visualize the clusters using relevant plots.


## 🔗 Resources

- [Python for Data Analysis](https://pandas.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

---
