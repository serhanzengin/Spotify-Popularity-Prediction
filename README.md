SPOTIFY POPULARITY PREDICTION


Overview 

This repository contains a machine learning model that predicts the popularity of songs on Spotify. The model is trained using a dataset of features extracted from various songs and their corresponding popularity scores on the platform.

Introduction 

Music popularity prediction is a fascinating task that involves understanding the characteristics of songs that make them popular among listeners. This project focuses on leveraging machine learning techniques to build a predictive model for Spotify song popularity.

Features

The model utilizes a diverse set of features, including:

Acoustic Features: Features such as danceability, energy, and tempo.
Lyric Features: Analysis of lyrical content using natural language processing.
Artist Information: Information about the artist, such as popularity and followers.
Genre Information: Genre tags associated with each song.

Dataset

The dataset used for training and evaluation consists of a curated collection of songs with their corresponding popularity scores on Spotify. The dataset is preprocessed to handle missing values and normalize feature scales. This dataset contains songs by artists who have been in the Spotify Top 50 list in the last 3 years.

Model Architecture

The model is built using a combination of traditional machine learning algorithms. It is designed to learn relationships between song features and popularity scores. CatBoost has been chosen as the final model due to its state-of-the-art results and ease of use.
