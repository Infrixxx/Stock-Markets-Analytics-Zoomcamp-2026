\# Homework 5: Automation \& New Ideas



\## Question 1: \[Exploratory] Research Idea Number One (2 points)

Integrating Alternative Data (Sentiment Analysis) as a Model Feature. Traditional models rely solely on price and volume history. This research idea explores setting up an automated daily pipeline to fetch financial news headlines or social media mentions and process them through a pre-trained sentiment analysis model (like FinBERT) to generate a daily Sentiment Score. The goal is to test whether adding this score as a feature alongside technical indicators improves the predictive accuracy of the machine learning model during backtesting.



\## Question 2: \[Exploratory] Research Idea Number Two (2 points)

Cloud-Native Serverless Automation with Real-Time Alerting. This idea focuses on moving beyond local scripts to build a highly scalable, serverless prediction pipeline using GitHub Actions or AWS Lambda. The system would automatically trigger at market close, pull the day's data, run inference through the trained ML model, save predictions to a cloud database, and push daily trading signals directly to a phone via a Telegram bot or Slack webhook, demonstrating full end-to-end automation without manual intervention.



\## Question 3: \[Exploratory] Research Idea Number Three (2 points)

Macroeconomic-Driven Sector Rotation Strategy. Instead of predicting individual stock prices, this research explores predicting the broader flow of capital between different economic sectors. It involves automating the ingestion of macroeconomic data (interest rates, inflation, VIX) alongside sector ETF prices to train a classification model. The goal is to build an automated portfolio that ranks and systematically rebalances itself weekly into the top predicted sectors, comparing its risk-adjusted returns against a simple buy-and-hold benchmark.

