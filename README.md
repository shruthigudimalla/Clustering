#Clustering
In this part, you will use Python to create clusters in the heart disease dataset. The goal is to apply clustering techniques to group similar patients based on their features.

#Instructions
Implement the following using a Python notebook and submit your source code with results.

#Tasks
Using the Python "sklearn" library, create and visualize the k-means clusters (with k=5) for the given heart disease dataset. For visualization, draw the scatter plot using the age and cholesterol features on each group of clusters.

Apply k-means clusters on the heart disease dataset with varying numbers of clusters from 1 to 10 and compute their corresponding Sum of Squared Error (SSE) value. Plot the graph using Python "matplotlib" library and estimate the right "k" value.

Create and visualize the k-means clustering with the "k" value obtained in Q2. Draw the scatter plot using the age and cholesterol features on each cluster group and label them as "Group-A", "Group-B", etc.

Plot a dendrogram using Python scipy.cluster.hierarchy method.

Create the agglomerative clustering with the number of clusters equal to the "k" value obtained in Question-2. Visualize the clusters similar to Question-2.

Compute the silhouette score for both K-means and agglomerative clustering and determine which clustering is better for the given dataset.

How to Run
Open the Python notebook.
Run each cell to see the output for each task.
