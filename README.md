# MSCS-634-Lab3

# Lab 3 – Clustering Analysis Using K-Means and K-Medoids
**Course:** Advanced Big Data and Data Mining  
**Student:** Sandesh Pokharel  

---

## 📌 Purpose

The goal of this lab was to explore clustering algorithms on a real-world dataset (Wine dataset from `sklearn`). We applied and compared both **K-Means** and **K-Medoids** algorithms, evaluated clustering performance using **Silhouette Score** and **Adjusted Rand Index (ARI)**, and visualized the cluster formations using PCA.

---

## 🔍 Key Insights

- **K-Means** performed better in both Silhouette Score and ARI, indicating tighter clusters and stronger alignment with actual wine classes.
- **K-Medoids**, while slightly less accurate, was more robust since it uses real data points as medoids.
- Visual analysis revealed that K-Means centroids were more symmetrically placed, while K-Medoids provided better stability in irregular distributions.
- Z-score normalization significantly improved clustering performance by ensuring all features were on the same scale.

---

## ⚠️ Challenges Faced

- The `sklearn_extra` package (for K-Medoids) had to be installed manually using `pip`.
- PCA introduced a warning when transforming cluster centers due to missing feature names, but this was not impactful.
- Ensuring visual clarity between cluster plots and centroids/medoids required careful tuning of colors and markers.
- Interpreting evaluation metrics needed attention to contextual meaning (e.g., high ARI but low silhouette).

---

## ⚙️ Technologies Used

- Python 3.13  
- Jupyter Notebook  
- Libraries: `sklearn`, `sklearn_extra`, `pandas`, `matplotlib`, `seaborn`

---

## ▶️ How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/sanspokharel26677/MSCS-634-Lab3.git
   ```
2. Activate virtual environment (optional, if set up)
3. Open the notebook:
   ```bash
   jupyter notebook Sandesh_Lab3_Clustering_Analysis.ipynb
   ```
4. Run each cell sequentially to reproduce results.

---

