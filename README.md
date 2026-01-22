# Spotify Data Visualization & Analysis
This project is a comprehensive data analysis and visualization of a dataset containing approximately 30,000 Spotify songs. It uses Python libraries to explore trends in music genres, song attributes, and artist popularity over time.

## 📌 Project Overview
The goal of this notebook is to uncover insights into the evolution of music on Spotify which is my favorite topic. The analysis focuses on correlating audio features (like tempo, energy, and danceability) with popularity and visualizing how different genres have shifted over the years.

## Tools Used
Python

Pandas 

NumPy 

Matplotlib & Seaborn (Static data visualization)

Plotly 

## Dataset
The project utilizes the *spotify_songs.csv* dataset, which includes the following key features:

### Metadata:
track_name, track_artist, track_album_release_date, playlist_genre.

### Metrics:
track_popularity (0-100), duration_ms.

### Audio Features:
danceability, energy, loudness, acousticness, instrumentalness, liveness, valence, tempo.

---
## 📊 Key Analysis & Visualizations
The notebook covers the following specific analytical tasks:

### Temporal Trends:

Line charts showing the number of songs released per year, broken down by playlist genre.

Analysis of the evolution of average song length (duration) throughout the years.

### Genre Analysis:

Evolution of playlist genre percentages over time relative to the total.

Deep dive into Rock music: Visualizing percentages of different subgenres across specific eras (<1970, 1970s, 1980s, 1990s, 2000s, >2010).

Comparing the distribution of average track popularity across different genres.

### Feature Correlation:

Statistical analysis and charts displaying correlations between track_popularity and audio features like danceability, energy, loudness, and valence.

Histograms showing the distribution of song lengths with optimal binning.

### Artist Insights:

A scatter plot visualization of Average Tempo vs. Average Popularity for artists with more than 5 tracks in the dataset.

This visualization uses color to distinguish genres and pre-attentive attributes (marks) to highlight specific artists of interest.

---

