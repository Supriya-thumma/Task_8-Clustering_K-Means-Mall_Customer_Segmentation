# 🧩 Task 8 – Customer Segmentation with K-Means - Mall Customer Segmentation Dataset

## 📌 Overview
This project is part of my AI & ML Internship Task 8 by Elevate Labs. This task focuses on **Customer Segmentation** using the **K-Means Clustering** algorithm on the **Mall Customers dataset**.  
The aim is to group customers based on **Age**, **Annual Income**, and **Spending Score** to help businesses identify distinct customer groups.

---

## 📂 Dataset
**File:** `Mall_Customers.csv`  
- **Rows:** 200  
- **Columns:**
  - `CustomerID` – Unique customer ID (not used for clustering)
  - `Gender` – Male/Female
  - `Age` – Customer age in years
  - `Annual Income (k$)` – Annual income in thousands of dollars
  - `Spending Score (1-100)` – Score assigned by the store

---

## ⚙️ Steps Performed
1. **Data Loading & Cleaning** – Uploaded dataset and removed unnecessary columns.
2. **Feature Selection** – Selected numerical columns for clustering.
3. **Feature Scaling** – Standardized values for fair comparison.
4. **Elbow Method** – Determined optimal clusters (**K = 5**).
5. **K-Means Clustering** – Assigned customers to clusters.
6. **Evaluation** – Calculated **Silhouette Score = 0.4166**.
7. **Visualization** – Created cluster plots using standardized features and PCA.

---

## 📊 Results
- **Optimal K:** 5  
- **Cluster Counts:**
  - Cluster 1 → 54 customers
  - Cluster 4 → 47 customers
  - Cluster 2 → 40 customers
  - Cluster 3 → 39 customers
  - Cluster 0 → 20 customers

- **Silhouette Score:** 0.4166 (moderate separation)

---

## 📷 Key Outputs
- Elbow Method Plot – Shows optimal number of clusters.
- K-Means Cluster Plot – Visualizes customer groups in feature space.
- PCA Cluster Plot – 2D visualization of clusters.

---

## 🛠 Requirements
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## 🚀 How to Run
- Upload Mall_Customers.csv when prompted.
- Open Task8-KMeansClustering.ipynb in Jupyter Notebook or Google Colab.
- Run all cells step-by-step to reproduce the results.

***💡 K-Means clustering helps businesses understand customer patterns and create targeted marketing strategies.***
