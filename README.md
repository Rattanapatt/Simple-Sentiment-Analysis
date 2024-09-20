# Sentiment Analysis on Narrative Chapters

This project performs sentiment analysis on a series of narrative chapters using Python. It evaluates each chapter's sentiment score and determines which chapters are the most positive and negative based on sentiment scores.

## Project Overview

The notebook uses the following approach:
1. **Data Input**: The text for each chapter is passed into the sentiment analysis pipeline.
2. **Sentiment Analysis**: For each chapter, the sentiment is calculated in terms of positive, neutral, and negative scores, as well as an overall compound score.
3. **Chapter Comparison**: The chapters are compared based on their sentiment scores to determine which chapters are the most positive and most negative.

### Results
- The chapter with the highest positive sentiment is **Chapter 10**.
- The chapter with the highest negative sentiment is **Chapter 7**.

## Files

- `main.ipynb`: This Jupyter notebook contains the code for reading the chapters and performing the sentiment analysis.

## Requirements

To run the notebook, you will need the following dependencies:

- `Python 3.12.4`
- `nltk` for Natural Language Toolkit (used for sentiment analysis)
- `vaderSentiment` for sentiment scoring