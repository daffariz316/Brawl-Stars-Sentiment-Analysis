# Brawl Stars Review Analysis Project

This project analyzes user review data for **Brawl Stars** using Python. The goal is to understand rating distributions, perform sentiment analysis, discover common themes, and visualize trends over time.

## Project Structure

- `brawlstars_reviews_sample.csv`: The dataset containing user reviews, scores, and timestamps.
- Analysis scripts and visualization codes are implemented in this Jupyter Notebook.

## Features & Analysis Performed

1. **Data Loading & Exploration**: Loaded dataset containing fields such as `reviewId`, `userName`, `content`, `score`, and `at`.
2. **Rating Distribution**: Plotted a bar chart showing the balance of 1-star to 5-star ratings.
3. **Word Cloud Generation**: Created a main word cloud and split-category word clouds (Positive vs. Negative reviews based on polarity).
4. **Sentiment Analysis**: Calculated polarity metrics using `TextBlob` to separate positive sentiment from negative sentiment.
5. **Trend Analysis**: Grouped average scores by month to visualize quality trends and identify potential anomalies over time.

## Getting Started

### Prerequisites
Make sure you have the following packages installed:
```bash
pip install pandas matplotlib wordcloud textblob scikit-learn seaborn
```

### Running the Analysis
Simply run the cells sequentially in the Jupyter Notebook to load the Google Drive dataset, process sentiment, and produce the plots.
"""

with open('README.md', 'w', encoding='utf-8') as f:
    f.write(readme_content)

print("README.md file successfully created in your current directory!")
