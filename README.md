# YouTube Sentiment Analyzer

A Machine Learning project that analyzes YouTube comments and predicts sentiment using NLP, TF-IDF Vectorization, and Logistic Regression.

## Features

- Fetches live YouTube comments using YouTube Data API v3
- Performs text preprocessing using NLTK
- Converts text into numerical features using TF-IDF
- Predicts Positive and Negative sentiment
- Visualizes audience sentiment using pie charts
- Uses IMDb 50K Movie Reviews Dataset for model training

## Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- YouTube Data API v3

## Workflow

1. Fetch comments from YouTube
2. Clean and preprocess text
3. Apply TF-IDF Vectorization
4. Train Logistic Regression model
5. Predict sentiment of comments
6. Visualize results

## Dataset

IMDb Dataset of 50K Movie Reviews

## Installation

```bash
pip install -r requirements.txt
```

## Setup

Replace:

```python
api_key = "YOUR_YOUTUBE_API_KEY"
```

with your own YouTube API key.

## Future Improvements

- Neutral sentiment detection
- Emotion analysis
- Spam comment detection
- Word cloud generation

## Author

Yash Kumar Choudhary
