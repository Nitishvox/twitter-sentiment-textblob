![Sentiment Analysis](https://exemplary.ai/img/blog/sentiment-analysis/sentiment-analysis.svg)
# Twitter Sentiment Analysis Using TextBlob

This project performs sentiment analysis on a dataset of tweets using the TextBlob library. It classifies each tweet as positive, negative, or neutral based on its polarity score and provides visualizations to explore the overall sentiment distribution and topic-specific sentiment.

## Project Objective

The goal of this project is to:

- Load and explore labeled Twitter data
- Analyze the sentiment polarity of each tweet using TextBlob
- Categorize tweets into positive, negative, or neutral
- Visualize sentiment distributions across the dataset
- Perform topic-based sentiment filtering and analysis

## Dataset

The dataset used is `twitter_training.csv`, which contains tweets along with sentiment labels. The structure includes:

- `tweet_id`: Unique identifier
- `topic`: Subject of the tweet
- `label`: Original sentiment label (positive, negative, neutral)
- `text`: Content of the tweet

## Features

- Load a subset of tweets for fast analysis
- Calculate sentiment polarity using TextBlob
- Categorize polarity into sentiment classes
- Visualize overall sentiment distribution using histograms and count plots
- Filter and analyze sentiment by topic keywords

## Requirements

Install the following Python packages before running the notebook:

```bash
pip install pandas matplotlib seaborn textblob

