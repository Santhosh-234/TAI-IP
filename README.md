# Spotify Song Attributes Analysis

This repository contains analyses performed on a dataset containing Spotify song attributes. The dataset has undergone preprocessing steps to handle missing values and was used to explore various aspects of the music data.

## Data Preprocessing

- Removed entries with missing values.
- Selected relevant columns for analysis: 'trackName', 'artistName', 'msPlayed', 'genre', 'danceability', 'energy', 'key', 'loudness', 'mode', 'speechiness', 'acousticness', 'instrumentalness', 'liveness', 'valence', 'tempo', 'type', 'id', 'uri', 'track_href', 'analysis_url', 'duration_ms', 'time_signature'.
- Cleaned and prepared the dataset for analysis.

## Analyses Conducted

### 1. Top 10 Genres with Most Songs
- Identified the top 10 genres with the highest number of songs.
- Visualized the distribution of songs across these genres using a countplot.

### 2. Top 50 Artists with Most Songs
- Explored the top 50 artists with the highest number of songs.
- Visualized the song count for each artist using a bar plot.

### 3. Danceability across Top 10 Artists
- Analyzed the danceability attribute among the top 10 artists.
- Presented danceability scores for these artists using a box plot.

### 4. Key Distribution in Top 10 Genres
- Investigated the distribution of musical keys within the top 10 most prevalent genres.
- Visualized key distribution across these genres using a countplot.

### 5. Tempo Distribution across Top 10 Genres
- Explored the distribution of tempo across the top 10 most prevalent genres.
- Visualized the tempo distribution using box plots for these genres.

### 6. Speechiness among Top 10 Artists
- Analyzed the speechiness attribute among the top 10 artists with the most songs.
- Presented speechiness scores for these artists using box plots.

### 7. Acousticness vs. Energy in Top 10 Genres
- Explored the relationship between acousticness and energy levels in songs within the top 10 most prevalent genres.
- Visualized this relationship using a scatter plot.
