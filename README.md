This README covers the exploration of the Wine Quality Dataset using advanced machine learning methodologies, focusing on K-Means and Hierarchical Clustering. The dataset consists of 10 numerical columns related to wine attributes. The exploration involves data analysis, outlier removal, visualization, and application of clustering techniques. The goal is to gain insights into wine characteristics and identify clusters with unique chemical compositions.

Dataset

Source: Kaggle

Columns: Fixed Acidity, Volatile Acidity, Citric Acid, Residual Sugar, Chlorides, Free Sulphur Dioxide, Total Sulphur Dioxide, Density, pH, Sulphates

Exploratory Data Analysis

Initial statistics: No missing values, 1599 entries
Boxplot analysis for outliers detection
Outlier removal using Inter Quartile Range (IQR)
Pairplot visualization to explore relationships between columns
Standardization and Principal Component Analysis (PCA) for dimensionality reduction

Clustering Methods

K-Means Clustering:
Optimal clusters determined using the Elbow Method
Visualization of clusters using scatterplot

Hierarchical Clustering:
Optimal clusters identified through dendrogram analysis
Visualization of clusters using scatterplot

Performance Metrics
Evaluation metrics: Silhouette Score, Davies-Bouldin Index, Calinski-Harabasz Index

Results:
K-Means Silhouette Score: 0.365, Davies-Bouldin Index: 0.870, Calinski-Harabasz Index: 880.29
Hierarchical Silhouette Score: 0.378, Davies-Bouldin Index: 0.886, Calinski-Harabasz Index: 735.03

Cluster Characteristics

K-Means Clusters (4):
Characteristics and potential use summarized for each cluster

Hierarchical Clusters (3):
Characteristics and potential use summarized for each cluster

Conclusion
K-Means outperformed Hierarchical Clustering based on evaluation metrics.
Identified clusters have practical applications in quality segmentation, control, and personalized recommendations in the wine industry.
Each cluster represents wines with specific characteristics, guiding producers in optimization, marketing, and diversification.
Clusters offer opportunities for creating red blends, crisp white wines, light fruity whites, and premium red wines.
Clustering provides a powerful tool for unraveling intricate patterns, aiding informed decision-making in winemaking and market strategies.
