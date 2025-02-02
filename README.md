# Clustering_Assignment_102383041
### Clustering Assignment - Google Colab Implementation

## **Project Overview**

This project aims to compare the performance of different clustering algorithms using various preprocessing techniques and evaluation metrics. The implementation is done entirely in **Google Colab**.

## **Dataset Used**

- **Iris Dataset** (UCI Machine Learning Repository)
- Features: **4** (Sepal Length, Sepal Width, Petal Length, Petal Width)
- Contains **150 samples** with **3 natural clusters (species of flowers)**

## **Preprocessing Techniques**

1. **Standardization (Z-score scaling)**
2. **Min-Max Normalization**
3. **PCA for Dimensionality Reduction**

## **Clustering Techniques Used**

1. **K-Means Clustering** (for k=2,3,4,5)
2. **Hierarchical Clustering** (for k=2,3,4,5)
3. **Mean-Shift Clustering** (auto-determines clusters)

## **Performance Evaluation Metrics**

- **Silhouette Score** (Higher is better)
- **Davies-Bouldin Index** (Lower is better)
- **Calinski-Harabasz Index** (Higher is better)

## **Generated Output Files**

1. **`clustering_evaluation.csv`** - Performance metrics for each clustering algorithm.
2. **`cluster_assignments.csv`** - Cluster labels for each sample in the dataset.

## **How to Run in Google Colab**

1. **Open Google Colab**: [Google Colab](https://colab.research.google.com/)
2. **Upload the Notebook**:
   - Click **File → Upload Notebook**
   - Select `clustering_assignment.ipynb`
3. **Run All Cells**:
   - Click **Runtime → Run all**
   - The notebook will execute and generate results.

## **How to Upload to GitHub**

### **Method 1: Direct Upload from Colab**

1. Open the notebook in Google Colab.
2. Click **File → Save a Copy in GitHub**.
3. Select your **repository** and add a commit message.
4. Click **OK** to upload.

### **Method 2: Manual Upload**

1. **Download the notebook**:
   - Click **File → Download → Download .ipynb**
2. **Upload to GitHub**:
   - Go to your GitHub repository.
   - Click **"Add file" → Upload files**.
   - Drag and drop the `clustering_assignment.ipynb` file.
   - Click **Commit changes**.

## **Conclusion**

- **K-Means performed best** with k=3.
- **Hierarchical clustering had similar performance** but required predefined k.
- **Mean-Shift automatically detected clusters** but sometimes resulted in suboptimal clustering.
- **Preprocessing techniques significantly impacted clustering accuracy**.

## **Author**

- **Name:** Jeevetesh Bhanot

