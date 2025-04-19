

##  Clustering Algorithm Comparison with Preprocessing

This project compares the performance of different clustering algorithms using multiple preprocessing techniques and standard clustering evaluation metrics.

---

###  Dataset
- *Iris Dataset* from [UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/iris)

---

###  Preprocessing Techniques
- *No Processing*  
- *Normalization* (MinMax)  
- *Transform* (Square Root)  
- *PCA*  
- *Transform + Normalize (T+N)*  
- *Transform + Normalize + PCA (T+N+PCA)*

---

###  Clustering Algorithms
- *K-Means* (3 to 5 clusters)
- *Hierarchical (Agglomerative)* (3 to 5 clusters)
- *Mean Shift* (auto-detects clusters)

---

###  Evaluation Metrics
- *Silhouette Score*  
- *Calinski-Harabasz Index*  
- *Davies-Bouldin Score*

---

###  Example Result Table

| Algorithm     | Method     | Clusters | Silhouette | CH Index | DB Score |
|---------------|------------|----------|------------|----------|----------|
| KMeans        | T+N+PCA    | 3        | 0.73       | 5601     | 0.58     |
| Hierarchical  | Normalize  | 4        | 0.67       | 4103     | 0.63     |
| MeanShift     | T+N        | 3        | 0.72       | 4982     | 0.59     |

(Scores are sample values – see notebook for full results)

---

###  Key Takeaways
- Combining preprocessing techniques improves clustering performance.
- PCA aids visualization and sometimes boosts separation.
- MeanShift is adaptive but slower; works well when the number of clusters is unknown.

