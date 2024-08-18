# Amazon Reviews Sentiment Analysis

This project performs sentiment analysis on Amazon product reviews using the VADER sentiment analyzer and NLTK.

## Project Overview

The project performs the following tasks:

- **Exploratory Data Analysis (EDA):** Visualizing the distribution of review ratings to understand the dataset's biases.
- **Text Processing using NLTK:** Tokenization, POS tagging, and named entity recognition (NER) to better understand the structure of the text.
- **VADER Sentiment Analysis:** Scoring the sentiment of reviews using VADER, which evaluates text polarity (positive, neutral, negative) based on the compound sentiment 
                                score.
- **Classification Analysis:** Identifying instances where reviews may be misclassified, for example, negative reviews categorized as positive.

### Features

- **Bar Plot Analysis:** Distribution of review ratings (1 to 5 stars).
- **Sentiment Scoring:** Analyzing the positive, neutral, and negative sentiments for different review scores.
- **Text Processing:** Tokenization and Named Entity Recognition (NER) using NLTK to examine the text structure.

## Dataset
The dataset used in this project is the Amazon Fine Food Reviews Dataset. It contains reviews of fine foods from Amazon, including product ratings, review text, and metadata.

You can download the dataset from Kaggle using the link below:
**Dataset URL:** https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews/data

## Requirements

The project requires the following libraries:

- pandas
- numpy
- matplotlib
- seaborn
- nltk
- tqdm

You can install them using:

pip install pandas numpy matplotlib seaborn nltk tqdm

