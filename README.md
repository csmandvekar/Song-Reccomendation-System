# Song Recommendation System

## Project Overview:

This project implements a song recommendation system utilizing machine learning techniques to provide personalized song suggestions based on user preferences. The system analyzes various features of songs, including genre, tempo, mood, and lyrical content, to ensure that the recommendations are tailored to each user's tastes.

## Data Source:

The dataset used in this project was obtained from Kaggle. You can find the dataset [here]([https://www.kaggle.com/your_dataset_link](https://www.kaggle.com/datasets/vatsalmavani/spotify-dataset/data)). This dataset contains a comprehensive collection of songs along with their attributes, which serve as the basis for recommendation generation.

## Exploratory Data Analysis (EDA):

Prior to model building, exploratory data analysis (EDA) was conducted to gain insights into the dataset. This involved analyzing the distribution of various features, identifying correlations between attributes, and understanding the overall structure of the data. EDA helped in preparing the data for clustering and recommendation purposes.

## Clustering:

The dataset, comprising songs with multiple features, was clustered using KMeans clustering. With over 15 features considered, including genre, tempo, and mood, the clustering algorithm separated songs into distinct clusters based on their similarity. This clustering process facilitated efficient recommendation generation by grouping similar songs together.

## Recommendation Process:

Upon receiving user input consisting of the names and release years of five songs, the system employs the clustered data to recommend five additional songs that are similar to the input. Leveraging the KNN (K-Nearest Neighbors) algorithm, the system identifies the nearest neighbors of the input songs within their respective clusters, ensuring that the recommended songs align closely with the user's preferences.

This project offers a user-friendly interface for exploring personalized song recommendations, enhancing the music discovery experience for users.

## Happy Listening! 🎵
