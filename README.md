# Spotify Songs' Genre Segmentation

## Project Overview

This project analyzes Spotify songs and groups them into meaningful clusters based on their audio features.

## Objective

The main objective is to analyze Spotify songs, identify similar groups of songs, and build a clustering-based recommendation approach.

## Project Workflow

1. Data Preprocessing
2. Exploratory Data Analysis
3. Data Visualization
4. Correlation Analysis
5. Feature Scaling
6. K-Means Clustering
7. Playlist Genre Analysis
8. Playlist Name Analysis
9. Cluster Evaluation
10. Song Recommendation

## Machine Learning Model

K-Means Clustering is used to group songs with similar audio characteristics.

The Elbow Method and Silhouette Score are used to determine the suitable number of clusters.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

## Dataset

The dataset contains Spotify song information, playlist details, genres, and audio features such as:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo
- Track Popularity

## Recommendation System

Songs belonging to the same cluster are considered similar based on their audio features. These similar songs can be used to generate music recommendations.

## Project Files

- Spotify_Songs_Genre_Segmentation.ipynb
- spotify dataset.csv
- spotify_clustered_results.csv

## Final Outcome

The project identifies groups of similar Spotify songs using K-Means clustering and provides a basic approach for building a music recommendation system.
