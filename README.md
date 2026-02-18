🎧 Predicting Spotify Track Popularity with Data Science

This project explores what drives song success on Spotify using artist, album, and track metadata.
The goal is to identify key popularity drivers and build a machine learning model that predicts track success.

📊 Problem Statement

Music success is difficult to predict.
This project investigates whether artist reputation, audience size, and track metadata can explain Spotify popularity and builds a predictive model to test it.

🗂 Dataset

Source: Kaggle

Contains metadata for tracks, artists, and albums

Includes popularity scores, artist followers, genres, release info, and track duration

⚙️ Tools & Technologies

Python

Pandas / NumPy

Matplotlib / Seaborn

Scikit-learn

Jupyter Notebook

🔎 Exploratory Analysis Highlights

Key observations from the dataset:

Track popularity is moderately correlated with artist popularity

Audience size (followers) amplifies track success

Track duration has weak influence on popularity

Mid-length songs (≈3–6 minutes) show slightly more consistent performance

🤖 Machine Learning Model

Model used: Random Forest Regressor

Performance

RMSE ≈ 19

R² ≈ 0.38

Interpretation

Metadata explains part of track popularity, but a large portion is likely driven by external exposure such as marketing, playlists, and trends.

📌 Key Takeaways

Artist reputation is the strongest predictor of track success

Track-level features alone cannot fully explain popularity

Popularity is only partially predictable from structural metadata

External factors likely play a major role in music virality
