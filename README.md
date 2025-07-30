# 📦 Customer Segmentation with RFM and Clustering Algorithms

This project is my final undergraduate thesis titled:  
**"Penerapan Metode Recency, Frequency, Monetary dan Algoritma Clustering untuk Segmentasi Pelanggan E-Commerce pada Toko Beramal Intan"**

---

## 🎯 Project Objectives

This study aims to determine the most effective clustering algorithm to be applied to the RFM (Recency, Frequency, Monetary) method for customer segmentation. By identifying the best-performing model, the project hopes to group customers based on their transactional behaviors and derive customer profiles from each segment.

---

## 🧪 Methodology

1. **RFM Analysis** – to quantify customer value and behavior.
2. **Clustering Algorithms** used:
   - K-Means
   - DBSCAN
   - Agglomerative Clustering
   - K-Medoids
   - Gaussian Mixture Models
3. **Evaluation Metrics**:
   - Silhouette Score
   - Calinski-Harabasz Index
   - Davies-Bouldin Index
4. **Preprocessing**:
   - Handling missing values
   - Data scaling
   - Outlier treatment

Exploratory Data Analysis (EDA) was also conducted to understand the overall customer patterns before segmentation.

---

## 📈 Dataset

- **Source**: Private transaction data from *Toko Beramal Intan*, collected via Shopee e-commerce platform.
- **Type**: Transactional data (orders, payments, etc.)
- **Note**: Dataset is confidential and not publicly shared in this repository.

---

## 📊 Results

Based on the clustering evaluation, three distinct customer segments were identified:

- **Cluster 0** – High-Value Infrequent Buyers  
- **Cluster 1** – Low-Value Infrequent Buyers  
- **Cluster 2** – High-Value Frequent Buyers  

Each cluster reflects unique customer characteristics that can be further utilized for personalized marketing strategies, loyalty programs, and retention efforts.

---

## ⚙️ Tools & Libraries

- **Platform**: Google Colab
- **Libraries**:  
  `pandas`, `numpy`, `matplotlib`, `seaborn`,  
  `scikit-learn`, `scipy`, `yellowbrick`, `kmodes`, and more.


---

## 🚧 Challenges

- Determining the best algorithm across three evaluation metrics required additional logic and experimentation.
- Handling outliers and preprocessing sensitive transaction data.

---

## ✨ Future Improvements

- Further analysis on how to use the segmentation results for business strategies and decision-making.
- Automating the evaluation scoring across all clustering models.

---

Arifah Wahyu Hidayat
Tugas Akhir – D3 Statistika Terapan dan Komputasi
Universitas Negeri Semarang
Tahun: 2025


