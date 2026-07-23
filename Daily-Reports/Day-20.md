# Day 20 - Summer Training Report

# Introduction to Clustering and K-Means Algorithm

**Training Domain:** Artificial Intelligence & Machine Learning (AI & ML) using Python

---

## Objective

The objective of today's session was to understand the fundamentals of Unsupervised Machine Learning and learn how the K-Means Clustering algorithm groups similar data points without predefined labels. The session focused on dataset exploration, feature scaling, building a K-Means model, and visualizing customer clusters using the Mall Customers dataset.

---

## Topics Covered

### 1. Introduction to Unsupervised Learning

- Understanding Unsupervised Machine Learning.
- Difference between Supervised and Unsupervised Learning.
- Introduction to Clustering.
- Real-world applications of clustering.

### 2. Mall Customers Dataset

- Introduction to the Mall Customers dataset.
- Understanding dataset features:
  - Customer ID
  - Gender
  - Age
  - Annual Income (k$)
  - Spending Score (1–100)
- Loading the dataset using Pandas.

### 3. Exploratory Data Analysis (EDA)

- Displaying dataset records using `head()`.
- Checking dataset dimensions.
- Viewing dataset information using `info()`.
- Generating summary statistics using `describe()`.
- Checking missing values using `isnull().sum()`.

### 4. Visualizing Customer Distribution

- Creating a Scatter Plot of Annual Income vs. Spending Score.
- Observing natural customer groups.
- Understanding why clustering is useful for customer segmentation.

### 5. Feature Selection and Scaling

- Selecting relevant features for clustering.
- Importance of Feature Scaling.
- Applying `StandardScaler` to normalize feature values.
- Preparing scaled data for K-Means.

### 6. K-Means Clustering

- Working principle of the K-Means algorithm.
- Steps involved in K-Means:
  - Selecting the number of clusters (K).
  - Initializing centroids.
  - Assigning data points to the nearest centroid.
  - Updating centroid positions.
  - Repeating the process until convergence.
- Training the K-Means model using Scikit-learn.

### 7. Cluster Visualization

- Assigning cluster labels to customers.
- Converting centroids back to their original scale.
- Visualizing customer clusters using Scatter Plot.
- Displaying cluster centroids.

---

## Practical Activities Performed

During the practical session, I performed the following activities:

- Loaded the Mall Customers dataset using Pandas.
- Explored the dataset structure and summary statistics.
- Verified that the dataset contained no missing values.
- Created a Scatter Plot to observe customer distribution.
- Selected Annual Income and Spending Score as clustering features.
- Applied StandardScaler for feature normalization.
- Built a K-Means Clustering model with five clusters.
- Generated cluster labels for each customer.
- Visualized customer segments along with cluster centroids.
- Interpreted the clustering output based on the generated visualization.

---

## Key Learning Outcomes

By the end of today's session, I was able to:

- Understand the concept of Unsupervised Learning.
- Differentiate between Supervised and Unsupervised Learning.
- Explain the working principle of the K-Means algorithm.
- Perform feature scaling before clustering.
- Build and train a K-Means Clustering model.
- Visualize customer clusters and cluster centroids.
- Understand how clustering helps identify similar groups within a dataset.

---

## Conclusion

Today's session introduced K-Means Clustering as a fundamental Unsupervised Machine Learning algorithm for grouping similar data points. Through practical implementation on the Mall Customers dataset, I learned how to preprocess data, build clustering models, and visualize customer segments. This session established a strong foundation for customer segmentation and clustering-based Machine Learning applications.
