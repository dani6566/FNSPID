# Financial News and Stock Price Integration Data Analysis
## overview
FNSPID (Financial News and Stock Price Integration Dataset) is a comprehensive dataset designed to bridge the gap between financial news and stock market predictions. By integrating both quantitative (stock price data) and qualitative (financial news headlines and articles) information, this dataset aims to provide a holistic view of market dynamics, enabling more accurate and robust predictions in financial modeling.
# Core Objectives:
<strong>Enhance Stock Market Predictions:</strong><br>
Integrate financial news data with stock price data to improve predictive models, capturing the impact of market sentiment on stock performance.
## Key Features
<strong> News Data:</strong> Contains financial news articles, headlines, and publication metadata from various sources. Each entry includes information such as the headline, publisher, publication date, and associated stock ticker.<br>
<strong>Stock Price Data:</strong> Includes historical stock price data, with information on open, high, low, close prices, and trading volume. The data is synchronized with the news data to allow for temporal analysis.<br>
<strong> Integrated Analysis:</strong> Designed to support complex analysis by combining news sentiment and stock price movements, helping to uncover relationships between market sentiment and stock performance.
# Installation
### To install the required dependencies, run:<br>
      pip install -r requirements.txt
# Data Analysis Techniques:
<strong>Descriptive Statistics:</strong> Analyzed headline lengths, article counts per publisher, and publication trends over time using pandas and matplotlib.<br>
<strong>Sentiment Analysis:</strong> Applied sentiment analysis using tools like TextBlob and VADER to classify the sentiment of news headlines as positive, negative, or neutral.
# Usage
## Exploratory Data Analysis (EDA)
<strong>Descriptive Statistics:</strong> Analyze the distribution of headline lengths, article counts per publisher, and trends in publication dates to understand the dataset's structure.<br>
<strong> Text Analysis:</strong> Perform sentiment analysis on the news headlines to categorize them as positive, negative, or neutral. Additionally, extract common keywords and topics to identify significant market events or trends.<br>
<strong>Time Series Analysis:</strong> Examine the temporal relationship between news publication frequency and stock price movements. Identify spikes in news activity that may correlate with market events.
# Project Structure
FNSPID/<br>
├── .vscode/<br>
│   ├── settings.json<br>
├── Notebooks/<br>
│   ├── sentiment_analysis.ipynb<br>
├── Test/<br>
│   ├── __init__.py<br>
│   ├── features/<br>
├── script/<br>
│   ├── __init__.py<br>
│   ├── financial_analyzer.py<br>
│   ├── README.md<br>
├── .gitignore<br>
├── requirements.txt<br>
├── README.md<br>
└── LICENSE
