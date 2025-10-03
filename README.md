# Task 8: Customer Segmentation using K-Means Clustering

[cite_start]This repository contains the solution for Task 8 of the AI & ML Internship at Elevate Labs[cite: 2]. The project focuses on performing unsupervised machine learning to segment customers based on their shopping behavior.

## Objective
[cite_start]The main objective is to apply K-Means clustering to the "Mall Customer Segmentation Dataset" to identify distinct customer groups[cite: 4, 13].

## Methodology

The project follows these key steps:

1.  [cite_start]**Data Loading**: The dataset is loaded using the Pandas library[cite: 5].
2.  **Data Preprocessing**: Relevant features ('Annual Income' and 'Spending Score') were selected and scaled for optimal performance.
3.  [cite_start]**Finding Optimal K**: The Elbow Method was used to determine the ideal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) against the number of clusters[cite: 9].
4.  [cite_start]**Model Training**: A K-Means model was trained with the optimal number of clusters found in the previous step[cite: 8].
5.  [cite_start]**Visualization**: The final customer segments and their centroids were visualized using Matplotlib for clear interpretation[cite: 10].
6.  [cite_start]**Evaluation**: The quality of the clustering was formally evaluated using the Silhouette Score[cite: 11].

## Tools Used
- Python
- [cite_start]Scikit-learn [cite: 5]
- [cite_start]Pandas [cite: 5]
- [cite_start]Matplotlib [cite: 5]
- Google Colab

## Results
The analysis successfully segmented customers into 5 distinct clusters, which can help in targeted marketing strategies. The optimal number of clusters was identified as 5 using the Elbow Method.
