📊 Market Sentiment & Trader Performance Analysis
🧠 Project Overview

This project explores the relationship between trader performance and market sentiment using two key datasets:

Historical Trading Data

Fear & Greed Index (Market Sentiment)

The goal is to uncover hidden patterns, analyze how market sentiment impacts trading outcomes, and generate insights that can drive smarter trading strategies.

📁 Datasets Used

historical_data.csv

Contains detailed trader performance records.

Typical columns: date, trader_id, entry_price, exit_price, trade_size, pnl, etc.

Used to compute trader-level metrics such as daily profit/loss, win rate, and volatility.

fear_greed_index.csv

Represents market sentiment indicators over time.

Columns typically include date, fear_greed_value, sentiment_label (e.g., Fear, Neutral, Greed).

Used to study how trader outcomes shift with changes in sentiment.

🔍 Key Objectives

Clean, merge, and preprocess both datasets for time-aligned analysis.

Conduct exploratory data analysis (EDA) to reveal:

How sentiment correlates with trader performance.

Whether extreme fear or greed affects profitability or risk-taking.

Temporal and cross-trader performance trends.

Perform correlation, lag, and clustering analysis to detect patterns.

Build a foundation for future predictive modeling (e.g., using sentiment to forecast PnL).

⚙️ Technical Workflow

Data Cleaning

Standardized column names, parsed dates, handled missing data.

Calculated new metrics: PnL, daily aggregates, rolling averages.

Feature Engineering

Extracted sentiment levels, lagged sentiment values, and volatility measures.

Exploratory Data Analysis (EDA)

Visualized trader returns vs. sentiment.

Distribution and correlation analysis.

Boxplots and time-series insights.

Advanced Insights

Lag correlation between sentiment and performance.

Clustering traders using KMeans + PCA visualization.

Regression analysis linking PnL to sentiment scores.

📈 Visualizations Included

Sentiment trends over time

Trader performance distribution

Boxplots comparing PnL under different sentiment regimes

Correlation heatmaps

Clustering visualization (Trader groups based on behavior)


🧰 Tech Stack

Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn)

Google colab

Project link-
https://colab.research.google.com/drive/1BmQQQ8BZON2Lpbm4ieo4qRKtZpyA91TP?usp=sharing

📊 Future Enhancements

Integrate real-time sentiment feeds (e.g., Twitter or Reddit data).

Build predictive models to forecast trading outcomes.

Deploy insights into a dashboard (e.g., Streamlit or Power BI).



