
# Customer Segmentation with K-Means Clustering

## 📌 Overview

This project performs **customer segmentation** using **K-Means clustering** on customer data.
It standardizes features, determines the optimal number of clusters using the **Elbow Method** and **Silhouette Score**, applies clustering, visualizes results, and provides actionable marketing recommendations.

---

## 🚀 Features

* **Data Preprocessing**

  * Handles missing values using median imputation
  * Standardizes features for clustering
* **Clustering**

  * Optimal `k` determined via Elbow Method & Silhouette Score
  * K-Means applied to segment customers
* **Visualizations**

  * Elbow Method plot
  * PCA scatter plot with centroids
  * Heatmap of cluster centroids
  * Pair plots for top-variance features
* **Insights & Recommendations**

  * Identifies high spenders, low spenders, and target customer groups
  * Suggests promotional, loyalty, and premium product strategies

---

## 📂 Output Files

All results are saved in the `clustering_outputs` folder:

* `customers_clustered.csv` → Original dataset with assigned cluster labels
* `elbow_wcss.png` → Elbow Method visualization
* `pca_scatter.png` → PCA-based cluster visualization
* `centroids_heatmap.png` → Heatmap of cluster centroids (original scale)
* `pair_plots.png` → Pair plots of selected features
* `cluster_centroids_original_scale.csv` → Centroid values in original scale

---

## 🛠 Requirements

Install required libraries:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## 📜 Usage

1. Place your dataset (e.g., `Customers.csv`) in the project folder.
2. Update the `INPUT_CSV` variable in the script with your dataset name.
3. Run:

```bash
python customer_clustering_with_recommendations.py
```

4. Check the `clustering_outputs` folder for results.

---

## 📊 Example Insights

* High spenders → Loyalty programs & premium product offers
* Low spenders with high income → Exclusive promotions to boost spending
* Young high spenders → Trendy product marketing
* Older moderate spenders → Value deals & memberships

---

## 📄 License

This project is licensed under the MIT License.

