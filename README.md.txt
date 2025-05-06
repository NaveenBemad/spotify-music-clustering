# Spotify Music Clustering Project

This project uses audio features from Spotify tracks to group similar songs using machine learning. We applied K-Means clustering to find hidden patterns based on features like danceability, energy, and tempo.

## Objectives
- Cluster songs based on sound properties, not genres.
- Visualize musical similarities using PCA.
- Demonstrate unsupervised learning in an interesting way.

## Tools & Techniques
- Python (pandas, numpy, matplotlib, seaborn)
- K-Means Clustering (from scikit-learn)
- Principal Component Analysis (PCA) for visualization
- Google Colab for implementation

## Files in This Repo
- music_clustering.ipynb — the full notebook with code and output
- clustered_spotify_songs.csv — final dataset with assigned clusters
- cluster_plot.png — image showing song clusters in 2D
- requirements.txt — list of Python packages used

## How to Run
1. Open music_clustering.ipynb in Google Colab
2. Upload the original spotify_songs.csv if needed
3. Run all cells to see clustering and plots