# 📚 Book Recommender System

A collaborative-based recommender system built using Flask and machine learning that suggests similar books based on your input.

## 🚀 Features

- Recommend books by title
- Simple and clean UI
- Powered by Flask + Scikit-Learn
- Responsive layout with Bootstrap

## 🧠 How it works

The app uses cosine similarity over TF-IDF vectors of book metadata to suggest similar books. It's lightweight, fast, and customizable.

## ⚙️ Installation

```bash
git clone https://github.com/YOUR_USERNAME/book-recommender.git
cd book-recommender
python -m venv venv
source venv/bin/activate  
pip install -r requirements.txt
python app.py
