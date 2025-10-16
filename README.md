# Movie Recommender System

A movie recommendation system built with Python and Streamlit that uses collaborative filtering to suggest movies based on user preferences.

## Features

- Movie recommendation based on user input
- Interactive Streamlit web interface
- Collaborative filtering algorithm
- Movie similarity calculations

## Setup

1. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

2. **Download Data Files**
   - Download `movie_list.pkl` and `similarity.pkl` files
   - Place them in the project root directory
   
   **Note**: These data files are too large for GitHub. You can:
   - Create your own movie dataset and similarity matrix
   - Use a smaller sample dataset
   - Download from a cloud storage service

3. **Run the Application**
   ```bash
   streamlit run app.py
   ```

## How It Works

1. The system loads pre-computed movie data and similarity matrix
2. When a user selects a movie, it finds similar movies based on the similarity matrix
3. Recommendations are displayed with movie posters and ratings

## File Structure

```
Movie-R-System/
├── app.py              # Main Streamlit application
├── requirements.txt    # Python dependencies
├── README.md          # This file
├── .gitignore         # Git ignore rules
└── data/              # Data files (not included in repo)
    ├── movie_list.pkl
    └── similarity.pkl
```

## Requirements

- Python 3.7+
- Streamlit
- Pandas
- Pickle
- Requests

## Usage

1. Open the application in your browser
2. Select a movie from the dropdown
3. View recommended movies with ratings and posters

## Note

The large pickle files (`movie_list.pkl` and `similarity.pkl`) are not included in this repository due to GitHub's file size limits. You'll need to provide these files separately to run the application.
