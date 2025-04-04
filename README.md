# spotifyMPD

# Spotify Million Playlist Dataset Challenge - Playlist Continuation 🎧

This repository is dedicated to the **Spotify Million Playlist Dataset Challenge**, where the objective is to develop a system for **automatic playlist continuation**. The challenge requires generating a list of recommended tracks that can be added to an existing user-created playlist, effectively "continuing" it.

## 📌 Project Overview

The goal of this project is to create a recommendation system that can predict additional tracks to add to a playlist based on the playlist's features and a set of seed tracks. The system should be able to:
- Accept playlist metadata and a variable number of seed tracks (ranging from 0 to 100).
- Output a list of **500 recommended tracks**, ordered by relevance in decreasing order.
- Handle playlists with no seed tracks as input.
- Compare the recommended tracks to the ground truth tracks in the original playlist to assess performance.

This repository contains the code and methodology used to implement this system and evaluate its performance.

## 📊 Dataset

- **Name:** Spotify Million Playlist Dataset (MPD)
- **Source:** [AIcrowd Challenge](https://www.aicrowd.com/challenges/spotify-million-playlist-dataset-challenge)
- **Format:** JSON files
- **Content:** 1 million user-created playlists, including metadata and track lists for each playlist.

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn, SciPy, Scikit-learn, TensorFlow/PyTorch)
- Jupyter Notebooks
- Git / GitHub for version control and collaboration

## 📁 Repository Structure

