# Iris Dataset — Clustering Assignment

This project applies unsupervised learning techniques to the Iris dataset to discover natural groupings within the data using **K-Means Clustering** and **Hierarchical Clustering**.

---

## 📂 Repository Contents
- `Iris_Clustering.ipynb` — Jupyter / Colab notebook  
- `visuals/` — Folder containing clustering visualizations  
- `README.md` — Project documentation  

*(Dataset is loaded directly from sklearn — no upload required)*

---

## 🎯 Objective
To evaluate the understanding and application of clustering algorithms on a real-world dataset using unsupervised machine learning.

---

## 🧪 Clustering Methods Implemented

### ⭐ K-Means Clustering
- Partitions data into *k* clusters by minimizing within-cluster variance  
- Suitable for Iris dataset because it is well-structured, numeric, and naturally separable

### ⭐ Hierarchical Clustering
- Builds a tree-structured hierarchy of clusters  
- Useful for visually interpreting relationships between observations

---

## ⚙️ Preprocessing
- Loaded dataset from scikit-learn  
- Removed the target label (`species`) since clustering is unsupervised  
- Standardized numerical features  

---

## 🖼️ Visuals Included (`visuals/` folder)
The repository contains saved images including:

- K-Means cluster visualization  
- Hierarchical clustering dendrogram  
- Agglomerative clustering scatter plot  

These plots help visually interpret and compare clustering performance.

---

## 🛠 Tools & Libraries
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- SciPy  
- Matplotlib  
- Seaborn  

---

## 🚀 How to Run
1. Open the notebook in Jupyter Notebook or Google Colab  
2. Run all cells in order  
3. View clustering results and saved visuals  

---

## 📌 Learning Outcome
This project demonstrates:
- Applying unsupervised learning techniques  
- Understanding cluster structures  
- Visual interpretation of clustering results  

---
