# DS_Amazon-Music-Clustering  with K-Means (unsupervised Learning)
Discovering patterns in music through data!
This project applies unsupervised learning (K-Means) to group songs with similar audio characteristics and helps visualize how songs differ by their musical features.

# Objective
To explore similarities between songs using features such as:
Danceability 
Energy 
Valence 
Loudness 
Acousticness 
and to cluster them into meaningful musical groups using K-Means clustering.

# Dataset
Rows: 95837 songs
Columns: 23 features

# Data Preprocessing
Dropped unnecessary columns (IDs, release_date, etc.)
Handled missing values
Visualized outliers using boxplots
Fixed skewed features using log/sqrt transformations
Scaled features with StandardScaler

# Clustering
Performed K-Means clustering and DBSCAN
Determined optimal k using the Elbow Method
Evaluated performance with:
Silhouette Score: 0.2276


# Visualization
PCA (2D plot) – visualizing clusters in two dimensions
Feature comparison – showing average feature value per cluster
Elbow method for optimal K
Silhouette Method for Optimal k

# Interpretation 
Cluster 0: Calm/Acoustic Tracks
Cluster 1: Upbeat/Party Songs
Cluster 2: Live/Vocal Tracks

# Tech Stack
Language: Python
Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn,K_Means,Silhouette Score
Environment: Jupyter Notebook
