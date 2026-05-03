# Customer Segmentation using K-Means Clustering

## 📌 Project Overview
This project focuses on grouping customers based on their purchasing behavior and demographic data. By applying the **K-Means Clustering Algorithm**, we segment a customer base into distinct groups to help businesses optimize their marketing strategies and increase customer satisfaction.

## 🎯 Objectives
* **Group customers** based on similar characteristics.
* **Identify high-value customers** to improve retention.
* **Personalize marketing** to reduce resource waste.
* **Increase sales** through data-driven insights.

## 🛠️ Technologies Used
* **Language:** Python
* **Libraries:** * `Pandas` (Data Manipulation)
    * `NumPy` (Numerical Operations)
    * `Matplotlib` & `Seaborn` (Data Visualization)
    * `Scikit-learn` (Machine Learning)
* **Tools:** Jupyter Notebook / Google Colab, Excel

## 📊 Dataset Description
The model typically uses the following features:
* **Customer_ID:** Unique identifier for each customer.
* **Age:** Customer's age.
* **Annual_Income:** Yearly earnings.
* **Spending_Score (1-100):** A score assigned based on customer behavior and purchasing nature.

## 🚀 System Architecture & Methodology
1.  **Data Collection:** Importing raw data from CSV/Excel.
2.  **Preprocessing:** Handling missing values, encoding categorical data, and scaling.
3.  **Elbow Method:** Determining the optimal number of clusters ($K$) by plotting WCSS.
4.  **K-Means Clustering:**
    * Initialize centroids.
    * Assign points to nearest centroid.
    * Update centroids until convergence.
5.  **Visualization:** Plotting results (Annual Income vs. Spending Score).

## 📈 Cluster Interpretation
Based on the analysis, customers are segmented into 5 types:
* **Cluster 1 (Standard):** Average income and average spending.
* **Cluster 2 (High Buyers):** High income and high spending (Target Segment).
* **Cluster 3 (Careless):** Low income but high spending.
* **Cluster 4 (Sensible):** High income but low spending.
* **Cluster 5 (Budget):** Low income and low spending.

## 🏁 Conclusion
The K-Means algorithm effectively identifies hidden patterns in customer data. By targeting **Cluster 2** for loyalty rewards and **Cluster 4** with special offers, businesses can significantly improve their ROI.
