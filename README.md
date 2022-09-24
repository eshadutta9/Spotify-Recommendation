# Spotify Recommendation System
This notebook uses a dataframe containing tracks from Spotify that contains features like artists, songs, danceability, loudness, acousticness etc.
After various preprocessing steps, one hot encoding, normalization of numerical features, a vector for a playlist is compared to individual song vectors using cosine similarity to generate recommendations. Scores are assigned to songs. 40 songs with the highest scores are displayed as recommended songs.
