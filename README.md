# Mall Customer Segmentation Using K-Means Clustering

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-K--Means-green.svg)

## 📌 Project Overview
This project focuses on segmenting a mall's customer base into distinct groups based on their demographic and behavioral data (specifically **Annual Income** and **Spending Score**). By leveraging unsupervised machine learning, businesses can better understand their target audience and design data-driven, specific marketing strategies to maximize revenue.

## 📊 Dataset Insights
The dataset contains information on 200 mall customers with the following features:
* **CustomerID:** Unique ID assigned to each customer
* **Age:** Age of the customer
* **Annual Income (k$):** Self-reported annual income of the customer
* **Spending Score (1-100):** Score assigned by the mall based on customer behavior and spending history

## 🚀 Key Steps & Methodology
1. **Data Exploration (EDA):** Analyzed feature distributions (Age, Income, Spending Score) using histograms and identified natural visual groupings using scatter plots.
2. **Data Preprocessing:** Handled features and prepared the data structure for clustering algorithms.
3. **Clustering:** Applied the **K-Means Clustering** algorithm to automatically categorize customers.
4. **Analysis & Observations:** Identified 5 distinct customer personas:
   * *High Income, High Spending* (Target/Premium Customers)
   * *High Income, Low Spending* (Untapped Potential)
   * *Low Income, High Spending* (Impulsive/Loyal)
   * *Low Income, Low Spending* (Budget-Conscious)
   * *Average Income, Average Spending* (Standard)

## 🛠️ Installation & Setup

To run this notebook locally, follow these steps:

1. **Clone the repository:**
```bash
   git clone [https://github.com/fariqnizami-ui/Mall-Customer-Segmentation]
