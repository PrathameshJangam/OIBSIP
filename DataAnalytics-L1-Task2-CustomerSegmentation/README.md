# Customer Segmentation Analysis Using RFM and K-Means

## Project Overview

This project analyzes e-commerce customer purchasing behaviour and segments customers into distinct groups using **RFM Analysis and K-Means Clustering**.

The objective is to identify different customer segments and develop targeted marketing strategies for each group.

The analysis focuses on:

- Customer purchasing behaviour
- Recency, Frequency, and Monetary value
- Average purchase value and purchase frequency
- Customer lifetime value approximation
- Customer segmentation using K-Means
- Optimal cluster selection using the Elbow Method
- Cluster profiling and visualization
- Marketing recommendations for each segment

---

## Dataset

The project uses the **Online Retail Dataset**, which contains transaction-level information from an e-commerce retailer.

---

### Main Features

- `InvoiceNo` – Invoice number
- `StockCode` – Product code
- `Description` – Product description
- `Quantity` – Quantity purchased
- `InvoiceDate` – Date and time of purchase
- `UnitPrice` – Price per unit
- `CustomerID` – Unique customer identifier
- `Country` – Customer's country

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Methodology

The project follows these steps:

1. Load and inspect the dataset
2. Clean missing and inconsistent data
3. Perform exploratory data analysis
4. Calculate total purchase amount
5. Perform RFM analysis
6. Transform and standardize RFM features
7. Use the Elbow Method to determine the optimal number of clusters
8. Apply K-Means clustering
9. Profile and visualize customer segments
10. Develop marketing recommendations

---

## Data Cleaning

The following preprocessing steps were performed:

- Removed transactions with missing `CustomerID`
- Removed duplicate records
- Removed cancelled transactions
- Removed transactions with non-positive quantities
- Removed transactions with non-positive unit prices
- Converted `InvoiceDate` into datetime format

---

## RFM Analysis

RFM analysis was used to understand customer purchasing behaviour.

### Recency

Measures how recently a customer made a purchase.

**Lower Recency indicates more recent activity.**

### Frequency

Measures how frequently a customer makes purchases.

**Higher Frequency indicates more frequent purchases.**

### Monetary

Measures the total amount spent by a customer.

**Higher Monetary value indicates higher customer spending.**

---

## Customer Segmentation

K-Means clustering was applied to the standardized RFM features.

The **Elbow Method** was used to determine the appropriate number of clusters.

The final analysis identified **4 customer segments**.

---

## Cluster Profile

| Cluster | Customers | Avg. Recency | Avg. Frequency | Avg. Monetary | Customer % |
|---|---:|---:|---:|---:|---:|
| Cluster 0 | 713 | 12.17 | 13.75 | 8088.02 | 16.44% |
| Cluster 1 | 1622 | 181.51 | 1.32 | 341.00 | 37.39% |
| Cluster 2 | 837 | 17.70 | 2.19 | 557.32 | 19.29% |
| Cluster 3 | 1166 | 71.64 | 4.08 | 1801.78 | 26.88% |

---

## Customer Segments

### Cluster 0 — High-Value Loyal Customers

These customers purchase frequently, have purchased recently, and have the highest spending.

**Marketing Action:**

- VIP rewards
- Exclusive offers
- Early access to products
- Personalized recommendations
- Loyalty benefits

### Cluster 1 — At-Risk / Inactive Customers

These customers have not purchased recently and have low purchase frequency and spending.

**Marketing Action:**

- Win-back campaigns
- Personalized discounts
- Re-engagement emails
- Limited-time offers

### Cluster 2 — Recent Low-Engagement Customers

These customers have purchased recently but have relatively low purchase frequency and spending.

**Marketing Action:**

- Welcome offers
- Second-purchase incentives
- Product recommendations
- Loyalty program invitations

### Cluster 3 — Regular / Potential Loyal Customers

These customers have moderate purchase frequency and relatively high spending.

**Marketing Action:**

- Loyalty rewards
- Personalized offers
- Cross-selling
- Product bundles
- Repeat-purchase incentives

---

## Key Insights

- Cluster 0 represents the most valuable customer group.
- Cluster 1 is the largest segment and represents an important opportunity for re-engagement.
- Cluster 2 contains recent customers who can be encouraged to make repeat purchases.
- Cluster 3 contains customers with good spending potential who could become high-value customers.
- Different customer segments require different marketing strategies.

---

## Visualizations

The project includes the following visualizations:

- RFM feature distributions
- Elbow Method plot
- Recency vs Frequency scatter plot
- Frequency vs Monetary scatter plot
- Recency vs Monetary scatter plot
- Number of customers per cluster
- Average RFM values by cluster

---

## Business Recommendations

| Customer Segment | Marketing Action |
|---|---|
| High-Value Loyal | VIP rewards and retention campaigns |
| At-Risk / Inactive | Win-back campaigns and personalized discounts |
| Recent Low-Engagement | Welcome offers and second-purchase incentives |
| Regular / Potential Loyal | Loyalty programs and cross-selling |

---

## Conclusion

This project demonstrates how e-commerce transaction data can be transformed into meaningful customer segments using RFM Analysis and K-Means Clustering.
The analysis identified four distinct customer groups with different purchasing behaviours. These segments can help an e-commerce business create targeted marketing campaigns, improve customer retention, encourage repeat purchases, and focus resources on high-value customers.

---

## 👤 Author

**Prathamesh Jangam**

**Track:** Data Analytics

**Task:** Customer Segmentation Analysis Using RFM and K-Means

---

## ⭐ Acknowledgement

This project was completed as part of the **Oasis Infobyte Internship Program**.

**Oasis Infobyte — Data Analytics Internship**

