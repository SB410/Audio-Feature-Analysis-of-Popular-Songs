# Audio-Feature-Analysis-of-Popular-Songs
This repository contains an analysis of audio features to understand trends and listener preferences in popular songs from Spotify. Using a comprehensive dataset from Kaggle, this project explores the characteristics that contribute to the success of songs and the patterns that define musical trends.

Project Overview

Spotify is one of the world’s leading music streaming platforms, offering a vast library of songs, podcasts, and other audio content. By analyzing the audio features of the top-streamed songs of 2023, this project aims to unravel the elements that make a song popular and understand the trends that influence listener preferences.

Objective

	•	Explore patterns in audio features such as tempo (BPM), danceability, energy, valence, acousticness, and speechiness.
	•	Identify characteristics of the top 10 most streamed songs and artists.
	•	Understand the relationship between audio features and song success.
	•	Provide insights for artists, producers, and the music industry to make data-driven decisions.

Dataset

The dataset contains a catalog of the most influential songs of 2023, along with information on various audio features, artist details, and streaming statistics. It includes songs featured on multiple platforms, such as Spotify, Apple Music, Deezer, and Shazam.

Key Features

	•	Song Details: Track name, streams, BPM, key, mode, danceability, valence, energy, acousticness, instrumentalness, liveness, speechiness.
	•	Artist Details: Artist name, artist count.
	•	Release Details: Year, month, and day of release.
	•	Streaming Platforms: Indicators of presence in playlists and charts on Spotify, Apple Music, Deezer, and Shazam.

Methodology

Tools and Libraries

	•	Python: Primary programming language used.
	•	Pandas: For data manipulation and analysis.
	•	Matplotlib & Seaborn: For data visualization.
	•	Scikit-Learn: For potential machine learning modeling and clustering analysis.

Data Cleaning and Preprocessing

	•	Handling Missing Values: Replaced missing values in relevant columns or removed them as necessary.
	•	Data Wrangling: Used techniques like “explode()” and “groupby()” to organize and prepare the data for analysis.
	•	Exploratory Data Analysis (EDA): Visualized relationships and distributions of audio features.

Analysis Techniques

	•	Correlation Matrix: Examined relationships between audio features.
	•	Scatter Plots: Analyzed how features like speechiness and instrumentalness impact stream counts.
	•	Top Songs and Artists: Identified the most streamed songs and artists, exploring audio features that contributed to their success.
	•	Trends and Patterns: Analyzed features such as BPM and danceability to understand their role in song popularity.
