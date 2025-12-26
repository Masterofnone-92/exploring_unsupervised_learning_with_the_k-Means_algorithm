# 📊 Assignment 3: Exploring Unsupervised Learning with the k-Means Algorithm

## 📘 Course Assignment Overview
This assignment explores **unsupervised learning** using the **k-Means clustering algorithm** 🤖.  
The goal is to understand how k-means works, experiment with its parameters, and analyze clustering results on a real-world dataset.

The work is divided into **two parts**:
- **Part 1:** Dataset selection, basic k-means application, and use cases
- **Part 2:** In-depth experimentation using parameter tuning and the Elbow Method 📐

All experiments, visualizations, and results are documented in the accompanying Jupyter Notebook (`.ipynb`).

---

## 🔍 Part 1: Familiarization and Basic Testing with k-Means

### 📂 Dataset Selection
- **Dataset Source:** Kaggle
- **Dataset Type:** Customer Segmentation Dataset
- **Purpose:** Analyze customer behavior and group customers based on similarity 🧑‍🤝‍🧑

### 📝 Dataset Description
The dataset contains customer-related numerical features that describe purchasing behavior and demographics.  
Common features used for clustering include:
- Annual income 💰
- Spending score 🛒
- Age 🎂
- Other numeric behavioral indicators

This dataset is suitable for **unsupervised learning** since no labeled target variable is required.

> ✅ Note: This dataset is unique to our group and was reserved according to the assignment instructions.

---

### ⚙️ Algorithm Application
- **Algorithm Used:** k-Means Clustering
- **Library:** `scikit-learn (sklearn)`
- **Preprocessing Steps:**
  - Selection of relevant numerical features
  - Feature scaling using standardization 📏
- **Model Training:** k-means was applied using different values of `k`

The full implementation and step-by-step process can be found in the Jupyter Notebook 📓.

---

### 🌍 Real-World Use Cases of k-Means
1. **Customer Segmentation**
   - Businesses group customers based on purchasing behavior to improve marketing strategies 📢
2. **Market Basket Analysis**
   - Retailers identify purchasing patterns to optimize product placement and promotions 🛍️

---

## 🔬 Part 2: In-Depth Experimentation with k-Means

### 🎛️ Parameter Tuning
To determine the optimal number of clusters (`k`), multiple k-means models were trained using different values of `k`.

### 📈 Elbow Method
- The **Elbow Method** was used to evaluate cluster compactness.
- Inertia (Within-Cluster Sum of Squares) was plotted against varying values of `k`.
- The “elbow point” in the graph indicates diminishing returns for increasing `k`.

### 🧠 Findings and Observations
- A clear elbow was observed at an optimal value of `k`, indicating a good balance between simplicity and clustering accuracy.
- Clusters formed meaningful groupings of customers with similar behaviors.
- Increasing `k` beyond the optimal value resulted in minimal improvement while increasing model complexity ⚖️.

All plots, cluster visualizations, and numerical results are included and explained in the notebook.

---

## 🤝 Collaborative Discussion
This assignment was completed collaboratively.  
Group discussions focused on:
- Interpreting elbow plots 📊
- Comparing clustering results across different `k` values
- Evaluating the practical meaning of each cluster

---

## 📁 Files Included
- `Assignment3_KMeans_Customers.ipynb` – Complete implementation, analysis, and visualizations
- `README.md` – Project overview and summary of findings

---

## 🏁 Conclusion
This assignment provided hands-on experience with unsupervised learning and demonstrated how k-means can uncover meaningful patterns in unlabeled data ✨.  
The Elbow Method proved effective in selecting an appropriate number of clusters, and the results highlighted the practical value of clustering in real-world applications.

---

## 🛠️ Tools and Libraries Used
- Python 🐍
- NumPy
- Pandas
- Matplotlib / Seaborn
- Scikit-learn
