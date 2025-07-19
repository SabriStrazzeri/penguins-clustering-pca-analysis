# 🐧 Penguin Clustering and PCA Analysis

## 📌 Objective
Perform unsupervised clustering and PCA on a modified version of the Palmer Penguins dataset to explore species segmentation.

## 📂 Dataset
Used a customized dataset from [Kaggle: Penguin Data Visualization with Seaborn](https://www.kaggle.com/code/tirendazacademy/penguin-dataset-data-visualization-with-seaborn)

## 🛠️ Tools Used
`Python`, `Pandas`, `Seaborn`, `Matplotlib`, `Scikit-learn`, `KMeans`, `PCA`, `Numpy`, `SciPy`.

## 🧪 Approach
1. Data preprocessing and exploratory data analysis:
   - Removed categorical variables for clustering and PCA.
   - Standardized the numerical features to ensure equal contribution to distance-based methods.
   - Performed descriptive statistics and correlation analysis  to understand relationships between variables.

2. Clustering analysis (`notebooks/clustering.ipynb`):
   - Hierarchical Clustering: used Euclidean distance and Ward's method. Evaluated dendrogram and made decisions based on silhouette analysis.
   - K-Means Clustering: applied K-means with a k selected based on the elbow and silhouette methods. Visualized the distribution of clusters in a PCA space.
   - Compared cluster centroids to identify distinguishing features. 

3. PCA (`notebooks/pca.ipynb`):
   - Applied PCA to reduce dimensionality and visualize the data in 2D.
   - Interpreted the components. 

## 📈 Results
- PCA effectively reduced the dataset to two dimensions while preserving most of the variance.
- K-Means clustering (k=2) produced meaningful groupings that aligned well with species distinctions. Silhouette scores confirmed the quality of clustering.
- Hierarchical clustering provided an intuitive visualization of data structure and supported the selection of k.
- Supplementary analysis showed that clusters corresponded closely with species and island groupings, validating the clustering approach. 

## 🤓 What I Learned
- PCA is a powerful tool for dimensionality reduction and visualization, especially when variables are correlated.
- Clustering methods like K-Means and hierarchical clustering can reveal natural groupings in data.
- The combination of PCA and clustering provided an easier approach to understand datasets.
- Visual tools, such as dendrograms, silhouette plots, and PCA scatter plots are essential for interpreting and communicating findings. 

## 📁 Repo Contents
- `notebooks/` – PCA and Clustering notebook.
- `data/` – Includes cleaned version of the dataset.
