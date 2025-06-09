# 📊 Mall Customer Segmentation using K-Means Clustering

This project applies **K-Means Clustering** to segment mall customers based on their **Annual Income** and **Spending Score**. The goal is to identify distinct customer groups to assist businesses in targeted marketing strategies.

---

## 📁 Dataset

- **Source**: `Mall_Customers.csv`
- **Attributes**:
  - `CustomerID` : Unique ID for each customer.
  - `Gender` : Customer's gender.
  - `Age` : Age of the customer.
  - `Annual Income (k$)` : Annual income of the customer in $1000s.
  - `Spending Score (1-100)` : Score assigned by the mall based on customer behavior and spending nature.

---

## 📌 Project Workflow

### 1️⃣ Importing Dependencies
Essential Python libraries for data manipulation, visualization, clustering, and analysis.

### 2️⃣ Data Collection & Analysis
- Loaded dataset using Pandas.
- Checked basic information, shape, null values.

### 3️⃣ Feature Selection
Selected **Annual Income (k$)** and **Spending Score (1-100)** for clustering.

### 4️⃣ Finding the Optimum Number of Clusters (Elbow Method)
- Calculated **Within-Cluster Sum of Squares (WCSS)** for cluster counts from 1 to 10.
- Plotted an **Elbow Graph** to determine the optimal number of clusters.

### 5️⃣ Training the K-Means Model
- Trained the K-Means clustering model with **5 clusters**.
- Predicted cluster labels for each customer.

### 6️⃣ Visualizing the Clusters
- Plotted a scatter plot of the customer segments.
- Visualized centroids of each cluster.

---

## 📈 Results

- **5 Customer Segments** identified based on income and spending behavior.
- Clusters visualized on a 2D scatter plot.

---

## 🛠️ Libraries Used

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn.cluster.KMeans`

---

## 📊 Example Visualization  

![Cluster Plot Example](https://user-images.githubusercontent.com/placeholder-cluster-plot.png) <!-- optional if you want to add your own saved cluster image -->

---

## 📌 How to Run

1. Install required libraries (if not already):

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
