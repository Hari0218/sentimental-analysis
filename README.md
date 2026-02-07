# YouTube Comment Sentiment Analysis

This project performs real-time sentiment analysis on YouTube video comments using Python. It fetches live comments via the YouTube Data API, cleans and preprocesses text, analyzes sentiment polarity, and visualizes results.

## Features
- Fetches real-time YouTube comments
- Cleans text using regex and NLTK stopwords
- Sentiment classification using TextBlob
- Categorizes comments as Positive, Negative, or Neutral
- Visualizes sentiment distribution using a pie chart
- Uses an RDD-style pipeline with a custom FakeRDD class

## Technologies Used
- Python
- YouTube Data API
- TextBlob
- NLTK
- Matplotlib

## How It Works
1. User enters a YouTube video URL or ID
2. Comments are fetched in real time
3. Text is cleaned and preprocessed
4. Sentiment polarity is analyzed
5. Final sentiment distribution is displayed graphically

## Installation
```bash
pip install google-api-python-client textblob nltk matplotlib
