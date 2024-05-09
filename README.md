# Python-ML-Clustering-Project-Cancer-Data-Analysis

## Project Description
This project aims to perform clustering analysis on a health-related dataset. The dataset includes features like radius_mean, texture_mean, perimeter_mean, area_mean, smoothness_mean, compactness_mean, and concavity_mean. The objective is to preprocess the data to remove irregularities and noise and then apply clustering techniques to make accurate predictions.

## Part 1: Data Exploration and Pre-processing

### Steps:
1. **Load Dataset**: Import the dataset into the working environment.
2. **Dataset Shape**: Determine the shape of the dataset to understand its structure.
3. **Data Information**: Display basic information about the data.
4. **Null Value Check**: Identify and handle any null values in the dataset.
5. **Drop Unnecessary Columns**: Remove 'Unnamed' and 'ID' columns that are not needed for analysis.
6. **Diagnosis Value Counts**: Show the distribution of values in the 'Diagnosis' column.
7. **Remove Label Column**: Exclude the 'Diagnosis' column before clustering.
8. **Pair Plot**: Create a pair plot for 'radius_mean' against 'texture_mean' categorized by 'Diagnosis'.
9. **Feature Selection**: Select 'radius_mean' and 'texture_mean' for clustering.
10. **Scaling**: Apply feature scaling to the selected features.

## Part 2: Working with Models

### Clustering Techniques:
1. **Hierarchical Clustering Dendrogram**: Visualize the data using a dendrogram to determine the number of clusters.
2. **Agglomerative Clustering**: Implement Agglomerative Clustering with 2 clusters.
3. **Cluster Prediction**: Predict the clusters and create a new column for cluster labels.
4. **Label Count**: Verify the count of each label.
5. **Label Plotting**: Visualize the distribution of cluster labels.
6. **Silhouette Score**: Calculate the silhouette score to assess the clustering performance.
7. **K-Means Clustering**: Apply K-Means clustering with 2 clusters.
8. **WCSS Score**: Compute the within-cluster sum of squares score.
9. **Elbow Method**: Use the elbow method to find the optimal number of clusters by plotting WCSS scores for 1 to 10 clusters.
10. **Optimal K-Means**: Reapply K-Means clustering with the optimal number of clusters found.
11. **Cluster Label Column**: Add a column for the K-Means cluster labels.

## Authors
- Viraj Panchal

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.

## Acknowledgments
- Data provided by www.fingertips.co.in
