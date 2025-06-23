# 🎬 Movie Recommendation System

This project implements a **Content-Based Movie Recommendation System** that suggests the top 5 movies similar to a user-selected movie. It analyzes movie features such as genre, keywords, cast, and more to find and recommend similar content.

## 🚀 Features

- 🔍 Content-based filtering using cosine similarity
- 🏆 Top 5 similar movie recommendations
- 🗃️ Uses a dataset of movies with metadata
- 📊 Built using Python, Pandas, Scikit-learn

## 🧠 How It Works

Content-based filtering recommends movies by comparing features (like genres, descriptions, keywords) of a movie with others in the dataset. It uses **cosine similarity** to measure how similar two movies are.

### Example:
If you like **"The Dark Knight"**, the system might recommend:
1. Batman Begins  
2. The Dark Knight Rises  
3. Man of Steel  
4. Iron Man  
5. Avengers: Infinity War

## 📁 Dataset

The system uses a movie metadata containing:
- Title
- Overview
- Genre
- Cast
- Keywords etc

Link: https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata
