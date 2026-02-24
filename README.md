# 🛍️ K-Means Clustering – Mall Customer Segmentation

## 📌 Step 1: Load and Visualize Dataset
The Mall Customers dataset was loaded and key numerical features were selected:
- Annual Income (k$)
- Spending Score (1-100)

Feature scaling was applied using StandardScaler to ensure equal contribution of both features.

Optional PCA was used for 2D visualization when working with multiple features.

**Observation:**
Scaling is important in K-Means because clustering is distance-based.

---

## 📌 Step 2: Fit K-Means and Assign Cluster Labels
K-Means algorithm was applied with a chosen number of clusters (K).

Each data point was assigned a cluster label based on the nearest centroid.

**Observation:**
Customers were grouped into segments based on income and spending behavior.

---

## 📌 Step 3: Elbow Method to Find Optimal K
The Elbow Method was used to determine the optimal number of clusters.

- Inertia (Within-Cluster Sum of Squares) was calculated for different K values.
- The "elbow point" indicates the optimal K.

**Observation:**
The optimal K is where inertia starts decreasing slowly.

---

## 📌 Step 4: Visualize Clusters with Color-Coding
Clusters were visualized using scatter plots.

- Each color represents a cluster.
- Red 'X' markers represent cluster centroids.

**Observation:**
Clusters clearly show different customer segments such as:
- High income, high spending
- High income, low spending
- Low income, high spending
- Low income, low spending

---

## 📌 Step 5: Evaluate Clustering using Silhouette Score
Silhouette Score was calculated to evaluate clustering quality.

Interpretation:
- Close to 1 → Well-separated clusters
- Around 0 → Overlapping clusters
- Negative → Incorrect clustering

**Observation:**
A higher silhouette score indicates better cluster separation.

---

## ✅ Final Conclusion

- K-Means is an unsupervised learning algorithm.
- It groups data based on similarity using distance metrics.
- Elbow Method helps determine optimal number of clusters.
- Silhouette Score evaluates cluster quality.
- Customer segmentation helps businesses target specific customer groups effectively.

K-Means is simple, efficient, and widely used for clustering problems.
