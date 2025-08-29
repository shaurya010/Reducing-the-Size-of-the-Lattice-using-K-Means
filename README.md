# 🔐 Lattice Reduction Using K-Means Algorithm  

This repository contains the implementation and experimental results of **Lattice Reduction using K-Means Clustering**, a novel approach to enhance **lattice-based cryptography** in the **post-quantum era**.  

📄 Based on the paper: *“Lattice Reduction Using K-Means Algorithm” by Shaurya Pratap Singh and Brijesh Kumar Chaurasia*  

---

## 📌 Overview  

Lattice-based cryptography is one of the strongest candidates for **post-quantum cryptography (PQC)**.  
It relies on hard mathematical problems such as the **Shortest Vector Problem (SVP)** and **Closest Vector Problem (CVP)**.  

Traditional cryptographic systems (RSA, DSA) are at risk due to the power of **quantum computing**.  
This work explores **K-Means clustering**, an unsupervised ML algorithm, as a method for **lattice reduction** – enabling more efficient solutions to lattice problems.  

---

## 🚀 Motivation  

- Classical cryptosystems (RSA, DSA) are vulnerable to **Shor’s algorithm** on quantum computers.  
- Lattice problems (SVP, CVP) are **NP-hard**, but provide strong security foundations.  
- Reducing the size of lattices makes cryptographic computations more efficient.  
- K-Means clustering can **classify lattice vectors** into groups, reducing complexity.  

---

## 🛡️ Contributions  

✔️ Proposed the **first K-Means based approach** to target lattice problems (SVP).  
✔️ Applied K-Means clustering to **2D and 4D lattices** to reduce size and extract patterns.  
✔️ Achieved **~60% accuracy** in clustering-based lattice reduction.  
✔️ Introduced **heat maps** and visualization techniques for lattice datasets.  
✔️ Paved the way for **hybrid ML-cryptanalysis approaches** in post-quantum security.  

---

## ⚙️ Methodology  

The proposed methodology applies **K-Means clustering** to lattice datasets:  

1. **Input lattice dataset** (2D or 4D coordinates).  
2. **Choose K clusters** (e.g., K=3,4,6,8).  
3. **Initialize centroids** (random or heuristic).  
4. **Assign vectors to nearest centroid** using Euclidean distance:  
5. **Update cluster centroids** iteratively.  
6. **Generate clusters & heat-maps** to visualize reduction.  
7. **Evaluate performance** using silhouette score & accuracy.  

---

## 📊 Results & Analysis  

- **Dataset**: 350+ self-generated lattice points  
- **Dimensions tested**: 2D and 4D lattices  

### 2D Results
- Accuracy improves as K increases (best at **K=6**).  
- Achieved **~60.7% clustering accuracy**.  
- Heatmaps show clear separation of vectors into clusters.  

### 4D Results
- Accuracy is higher for certain cluster sizes.  
- As dimensions increase, clustering becomes harder but still feasible.  

📈 **Observation**: Larger lattice dimensions reduce accuracy, but K-Means still shows promise as a **lattice reduction tool**.  

---

## 📂 Repository Structure  

