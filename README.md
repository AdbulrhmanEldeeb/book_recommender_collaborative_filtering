# Book Recommender System

## Overview

This project implements a book recommender system using Collaborative Filtering techniques. It is built with Python and Flask for the backend, and HTML/CSS for the frontend. The recommender system leverages data from the [Book Recommendation Dataset](https://www.kaggle.com/datasets/arashnic/book-recommendation-dataset) available on Kaggle.

## Project Structure

- `app.py`: The main Flask application file that handles routing and recommendation logic.
- `templates/index.html`: The main HTML page displaying popular books and a form for book recommendations.
- `templates/recommend.html`: The HTML page displaying the recommended books based on user input.
- `static/images/recommender_image.ico`: The favicon for the application.
- `popular.pkl`: A pickle file containing the popular books data.
- `pt.pkl`: A pickle file containing the pivot table for the book recommendations.
- `books.pkl`: A pickle file containing detailed book information.
- `similarity_scores.pkl`: A pickle file containing precomputed similarity scores for collaborative filtering.

## All code in data are in remote_repo.zip please unzip it 