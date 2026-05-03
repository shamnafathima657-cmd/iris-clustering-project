# iris-clustering-project
KMeans and Hierarchical Clustering on Iris Dataset with visualization and analysis
#  Iris Clustering Project

##  Overview

This project applies **unsupervised learning techniques** to the Iris dataset to identify natural groupings within the data. The clustering is performed without using the target labels (species), allowing the algorithms to discover hidden patterns based on feature similarity.

---

##  Objective

The objective of this project is to:

* Apply **KMeans Clustering** and **Hierarchical Clustering**
* Identify natural clusters in the dataset
* Visualize clustering results for better understanding

---

## Dataset

* Dataset: Iris Dataset (from Scikit-learn)
* Total Samples: 150
* Features:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width
  * Species

---

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

##  Project Workflow

### 1. Data Loading

* Loaded dataset using sklearn
* Converted into pandas DataFrame

### 2. Data Preprocessing

* Dropped the species column (unsupervised learning)
* Applied **StandardScaler** for feature scaling

### 3. Exploratory Data Analysis

* Generated **correlation heatmap**
* Identified important features (petal length & petal width)

### 4. Elbow Method

* Determined optimal number of clusters (K = 3)

### 5. KMeans Clustering

* Applied KMeans with K=3
* Visualized clusters using scatter plots
*  Visualized centroids

### 6. Hierarchical Clustering

* Generated dendrogram
* Applied Agglomerative Clustering
* Visualized cluster formation

---

## Results

* Both algorithms successfully grouped the dataset into **3 clusters**
* Clusters closely match the natural grouping of Iris species
* Petal features provided the best separation

---

##  Conclusion

KMeans and Hierarchical clustering effectively identified patterns in the dataset.
The results show that unsupervised learning can successfully uncover hidden structures in well-defined datasets like Iris.





