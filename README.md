AI/ML Internship task 8: 🧬 K-Means Clustering on Gene Expression Data

📌 Description
This project applies unsupervised learning using K-Means clustering on a gene expression dataset to identify potential cancer subtypes. It includes preprocessing, PCA visualization, Elbow Method for optimal cluster selection, and evaluation using Silhouette Score.

📊 Dataset
- Source: [OpenML Gene Expression Dataset](https://www.openml.org/d/151)
- Features: Gene expression levels across multiple samples
- Goal: Discover hidden patterns in patient profiles

🧠 Workflow
1. Load and preprocess the dataset
2. Apply PCA for 2D visualization
3. Use Elbow Method to find optimal `k`
4. Fit K-Means and assign cluster labels
5. Visualize clusters
6. Evaluate using Silhouette Score

📦 Requirements
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
