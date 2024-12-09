# ML Clustering - K-means

## Description

This project explores the **K-means clustering algorithm**, an unsupervised method used to group data into similar clusters. The goal is to demonstrate the use and performance of K-means in a data analysis context using the famous **Iris dataset**.

The **Iris dataset** is a classic dataset in machine learning and statistics. It consists of 150 observations of iris flowers, with each observation including the following features:
- **Sepal length** (in cm)
- **Sepal width** (in cm)
- **Petal length** (in cm)
- **Petal width** (in cm)
- **Species**: One of three classes (Setosa, Versicolor, Virginica)

This project uses the features to group the flowers into clusters, aiming to match the original species classification.

The notebook includes the following steps:
- Data preparation and exploration.
- Implementation of the K-means algorithm.
- Visualization of the results.
- Evaluation of the clustering quality.

---

## Project Content

1. **Data Loading**: Importing the Iris dataset and inspecting its structure.
2. **Data Exploration**: Descriptive analysis of the features and visualization of data distributions.
3. **K-means Implementation**:
   - Preprocessing the data for clustering.
   - Choosing the number of clusters (k).
   - Using methods like the elbow method to find the optimal k.
4. **Evaluation**: Comparing clusters with actual species labels using metrics like accuracy and silhouette score.
5. **Visualization**: Graphical representation of clusters, including scatter plots and cluster centroids.

---

## Prerequisites

To run this project, you will need the following libraries:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Seaborn (optional for enhanced visualizations)

---

## Installation

Make sure Python and the required libraries are installed. You can install the dependencies with:

```bash
pip install numpy pandas matplotlib scikit-learn seaborn
