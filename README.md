# Six Senses Laamu Sentiment Analysis

This project involves detecting the emotion of people who visited the Six Senses Laamu resort in the Maldives and flagging sentiment using scraped data from TripAdvisor. The project includes steps for data preprocessing, tokenizing, POS-tagging, lemmatizing, and finally detecting the sentiment of each review of the place. 

![Image](https://github.com/saikatdas3478/sixsenseslaamusentiment/blob/main/Screenshot%202024-07-02%20230521.png)

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Dependencies](#dependencies)
- [Usage](#usage)
- [Results](#results)
  - [Sentiment Analysis](#sentiment-analysis)
  - [Word Cloud](#word-cloud)

## Introduction

Six Senses Laamu is a luxury Maldives resort featuring a combination of on-land and over-water villas constructed of sustainable materials. This project aims to analyze the sentiment of customer reviews about the resort, which are mostly positive, as suggested by the company's website.

## Methodology

1. **Data Collection**: 
    - Scraped 2913 reviews from TripAdvisor using the BeautifulSoup library.
2. **Data Preprocessing**:
    - Cleaned text by removing digits, extra spaces, and punctuation.
    - Tokenized sentences and words.
    - Performed POS tagging and lemmatization.
3. **Sentiment Analysis**:
    - Used VaderSentiment library to analyze the sentiment of each review.
4. **Visualization**:
    - Generated a pie chart showing the sentiment distribution.
    - Created a word cloud of the most frequently used words in the reviews.

## Dependencies

- pandas
- re
- requests
- BeautifulSoup (bs4)
- nltk
- vaderSentiment
- plotly
- wordcloud
- matplotlib

## Usage

1. **Clone the repository**:
    ```sh
    git clone https://github.com/saikatdas3478/sixsenseslaamusentiment.git
    cd SixSensesLaamuSentimentAnalysis
    ```

2. **Install the required packages**:
    ```sh
    pip install pandas requests beautifulsoup4 nltk vaderSentiment plotly wordcloud matplotlib
    ```

3. **Run the script**:
    - The script fetches reviews from TripAdvisor, processes the text, performs sentiment analysis, and generates visualizations.

4. **View Results**:
    - The results include a pie chart of sentiment distribution and a word cloud of the most frequently used words in the reviews.

## Results

### Sentiment Analysis

The analysis showed that:
- 99.3% of the reviews are positive.
- 0.5% of the reviews are negative.
- 0.2% of the reviews are neutral.

A pie chart visualizes this sentiment distribution.

### Word Cloud

A word cloud of the most frequently used words in the reviews highlights terms like "amazing", "honeymoon", "best", "recently", and "perfect".

---

**Note**: For the detailed implementation, please refer to the `script.py` file in the repository.


