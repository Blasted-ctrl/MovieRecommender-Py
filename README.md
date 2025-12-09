A simple machine-learning based movie recommender built using Python, pandas, scikit-learn, cosine similarity, and user rating data.
This project combines text-based similarity (TF-IDF on movie titles) with a collaborative filtering–style recommendation (users who liked similar movies).
It is fully interactive using Jupyter widgets, allowing you to type a movie title and instantly receive recommendations.

✅Features
Title-Based Search (Content Filtering)

Cleans and vectorizes movie titles using TF-IDF

Computes cosine similarity to find the closest matching titles

Real-time search as you type using ipywidgets

✅User-Rating Based Recommendations (Collaborative Filtering)

Given a selected movie:

Finds users who highly rated that movie

Looks at which other movies those users also loved

Computes a recommendation score = similar / all

Returns the top recommended movies with titles and genres

✅ Interactive UI

Built with Jupyter Notebook widgets:

Text input box

Auto-update recommendations

Clean output display

📦 Dataset Requirements

Python
pandas
NumPy
scikit-learn
Cosine Similarity
TF-IDF
ipywidgets / Jupyter Notebook

Your project expects two CSV files:

File	Description
movies.csv	Contains movieId, title, genres
ratings.csv	Contains userId, movieId, rating

<img width="1067" height="605" alt="Screenshot 2025-12-09 021613" src="https://github.com/user-attachments/assets/152ae314-10dc-4287-a40e-0cf4369bb15c" />
