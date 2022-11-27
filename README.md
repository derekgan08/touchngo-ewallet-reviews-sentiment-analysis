# Natural Language Processing Assignment 1: Touch 'n Go eWallet Reviews Sentiment Analysis

## Problem Statements
Understanding user sentiment from online reviews is crucial for businesses to improve their products or services. Google Play Store app reviews, which are abundant, contain valuable feedback, but analyzing these reviews manually is time-consuming and impractical. This project applies sentiment analysis to Touch 'n Go eWallet mobile app on Google Play Store reviews, enabling businesses or developers to quickly gain insights into user sentiment.

## Project Overview
This project leverages Natural Language Processing (NLP) techniques to analyze user reviews from the Google Play Store. It utilizes the `google-play-scraper` package to scrape the reviews of a particular app, preprocesses the data by cleaning and removing noise (such as special characters and stopwords), and then classifies the sentiment of each review (positive, negative, or neutral). The sentiment classification is done using the VADER sentiment analyzer from the `nltk` library. The goal of this project is to automate the process of sentiment analysis on app reviews to help app developers and businesses make data-driven decisions.

The process begins by extracting and cleaning user reviews. Afterward, the reviews are classified based on their sentiment score, and results are visualized to provide insights into overall user sentiment.

## Key Features
- **Google Play Reviews Scraping:** Automatically fetch reviews of an app using the `google-play-scraper` library.
- **Text Preprocessing:** Cleans and normalizes review content by removing unwanted characters, stopwords, and irrelevant text.
- **Sentiment Analysis:** Classifies reviews as positive, negative, or neutral using the VADER sentiment analyzer.
- **Visualization:** Displays a pie chart summarizing the distribution of sentiments in the reviews.
- **Corpus Export:** Allows for the export of positive and negative reviews into separate text files for further analysis.

## Technologies Used
- **Python 3.x**
- **google-play-scraper:** to scrape Google Play Store reviews
- **nltk:** for natural language processing and sentiment analysis
- **matplotlib:** for data visualization
- **Other Tools:** `pandas`, `numpy`, `re`