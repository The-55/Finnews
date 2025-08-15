## PROJECT : REAL-TIME FINANCIAL NEWS SENTIMENT ANALYSIS AND IMPACT FORECASTING

## 1. Context
Financial markets react rapidly to news — earnings reports, mergers, geopolitical events, or product launches can trigger sudden price movements.
In algorithmic trading and investment decision-making, being able to interpret news instantly and estimate its impact on stock prices is a competitive advantage.

While sentiment analysis in finance exists, many current solutions focus only on classifying sentiment (positive, negative, neutral) without quantifying the probable impact on stock prices, and rarely work in real-time with live data streams.

## 2. Problem Statement

Investors and traders are overwhelmed by a constant flow of financial news from multiple sources.
Key challenges include:

- Understanding whether a news item is good or bad for a given company or sector.

- Estimating the magnitude of the expected price change.

- Doing this in real-time so the information can be actionable in trading strategies.

Existing tools often:

- Lack real-time integration with live news feeds.

- Provide only qualitative sentiment (e.g., "positive") without numerical price impact forecasts.

- Are limited to English or a single data source.


## 3. Objectives

The main goal is to develop an AI-powered system that:

1. Collects financial news in real-time from APIs.

2. Analyzes the sentiment of each news headline/body using NLP models specialized for finance (e.g., FinBERT).

3. Predicts a numerical estimate of the short-term price impact (e.g., +2.5% or -1.3% within the next day).

4. Displays results in an interactive dashboard for easy interpretation.
