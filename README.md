# Clustering_Akshita_102203527

Sure! Here's a concise version of your README.md:

---

## 🧠 Clustering Algorithm Comparison with Preprocessing

This project compares different clustering algorithms using various preprocessing techniques and evaluates them using standard clustering metrics.

### 📌 Dataset
- *Iris Dataset* from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/iris)

### ⚙ Preprocessing Techniques
- No Processing  
- Normalization (MinMax)  
- Transformation (sqrt)  
- PCA  
- Transform + Normalize (T+N)  
- Transform + Normalize + PCA (T+N+PCA)

### 📈 Clustering Algorithms
- K-Means  
- Hierarchical  
- Mean Shift

### 📏 Evaluation Metrics
- Silhouette Score  
- Calinski-Harabasz Index  
- Davies-Bouldin Score

### 🧪 Sample K-Means Results (Example)

| Method       | Clusters | Silhouette | CH Index | DB Score |
|--------------|----------|------------|----------|----------|
| Normalization| 3        | 0.75       | 6653     | 0.59     |
| T+N+PCA      | 4        | 0.62       | 1290     | 0.75     |

### ✅ Key Takeaways
- Preprocessing can significantly improve clustering results.
- PCA helps with dimensionality reduction and visualization.
- Best results often come from combining transformation + normalization + PCA.

---

Let me know if you want this in a downloadable format or want to include plots later!
