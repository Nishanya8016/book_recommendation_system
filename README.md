# 📚 Book Recommendation System
This is a simple and interactive Book Recommendation System built using Python, Flask, and HTML. It showcases two main features:

📈 Recommends Top 50 Most Popular Books

🤝 Suggests books based on Collaborative Filtering

## 🚀 Features

-View a curated list of the top 50 most popular books
-Get personalized book recommendations using collaborative filtering

Lightweight web interface using Flask and basic HTML templates

## 🗂️ Project Structure
```bash
├── app.py              # Main Flask application
├── index.html          # Home page - displays popular books
├── recommend.html      # Results page - shows recommended books
├── notebook.ipynb      # Jupyter notebook used for data analysis and model building
├── README.md           # Project documentation

```
Recommendation Logic
Popularity-Based: Books are ranked based on the number of ratings and average rating. The top 50 books are displayed to all users.

Collaborative Filtering: Personalized recommendations are generated based on user similarity and past ratings using a collaborative filtering model.
