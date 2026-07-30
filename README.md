# goodreads-sentiment-analysis
Predictive sentiment analysis of 900,000 Goodreads reviews using R, NLP, statistical analysis, and machine learning to examine the relationship between emotional tone and user ratings.

# Goodreads Sentiment Analysis

## Overview

This project analyzes over **900,000 Goodreads book reviews** to investigate the relationship between emotional tone and user ratings. Using natural language processing (NLP), statistical analysis, and machine learning, the project quantifies review sentiment and evaluates its predictive power for review ratings.

---

## Objectives

- Analyze emotional tone in Goodreads reviews
- Examine relationships between sentiment and ratings
- Build predictive machine learning models
- Visualize sentiment trends and model performance

---

## Dataset

- Source: Goodreads Reviews Dataset
- Size: 900,000 reviews

Variables include:

- Review text
- Rating
- Number of votes
- Number of comments

---

## Tools & Technologies

- R
- tidyverse
- tidytext
- ggplot2
- randomForest
- caret
- AFINN Lexicon

---

## Methods

### Data Cleaning

- Removed punctuation and numbers
- Converted text to lowercase
- Removed stop words
- Tokenized review text

### Sentiment Analysis

- Applied the AFINN sentiment lexicon
- Calculated sentiment scores
- Created an emotional tone index

### Statistical Analysis

- Correlation Analysis
- ANOVA
- Linear Regression

### Machine Learning

Random Forest classifier predicting review ratings from engineered sentiment features.

---

## Results

- Processed 900,000 Goodreads reviews
- Significant positive relationship between emotional tone and ratings
- Correlation coefficient:
  - **r = 0.212**
  - **p < 2.2 × 10⁻¹⁶**
- Random Forest outperformed the baseline model with **35.6% accuracy**

---
