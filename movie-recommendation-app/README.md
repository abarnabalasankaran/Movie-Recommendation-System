# 🎬 Movie Recommendation System

A machine learning-based Movie Recommendation System that suggests movies to users based on their preferences using content-based filtering and collaborative filtering techniques.

## 🚀 Project Overview

This project aims to help users discover movies they may like, using various recommendation approaches. It includes:

- Content-Based Filtering (using movie metadata such as genre, director, cast)
- Collaborative Filtering (using user ratings – if available)
- Hybrid Recommendation System (if both datasets are available)
- Web application interface for users to search and get movie suggestions


## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas & NumPy** – data manipulation
- **Scikit-learn** – TF-IDF vectorizer, cosine similarity
- **NLTK** – natural language processing
- **Flask/Streamlit** – to deploy the app
- **Jupyter Notebook** – for development and testing

## 📊 Features

- Movie title-based recommendations
- Similarity-based filtering using TF-IDF and cosine similarity
- Web interface to input movie names
- Displays top recommended movies with metadata (poster, rating, etc.)

## 📌 How It Works

1. Preprocess the movie dataset.
2. Create a new feature by combining important metadata (e.g., title, overview, genres, cast).
3. Use TF-IDF Vectorizer to convert text data into vectors.
4. Compute cosine similarity between vectors.
5. Recommend top N movies similar to the input movie.



