- This notebook basically contains how I analyzed the ROI for both solar and wind power generation dataset given in this this (https://www.kaggle.com/datasets/rasulmah/sri-lanka-weather-dataset). 

My task was Return on Investment (ROI) Modeling:
 - Construct a robust model to calculate the potential return on investment for wind and solar
energy projects in each city. This model should factor in installation expenses, maintenance
costs, energy production estimates, and local energy market dynamics.

- Here I basically follow an unsupervised approach.

        - first I did some preporcessing and EDA part
        - next scalled features using standarad scalar
        - Passing scaled data to autoencoder to dimensionality reduction and feature learning.
        - Train the autoencoder and encoder predicts data
        - finding the optimal number of clusters for apply K-means algorithm
            -Elbow Method
            -Silhouette Analysis
        - Cluster analysis and visualize clusters using PCA
        - Use domain knowledge on clusters (unfortunatelty I coudn't find any domain knwowledge, so I made insights using same dataset)
        - Analyze ROI Across Clusters
        - Consider Sensitivity Analysis
        - Document and Communicate Findings


This is the unsupervised method I followed, for this. If you have better methods please mention them here. Thank you. Cheer unsupervised learning ;)

