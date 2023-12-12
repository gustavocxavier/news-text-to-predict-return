# News Text to Predict Return

## Introduction

This repository hosts the code for "news-text-to-predict-return", a project initially conceived as a research endeavor to explore the potential of Natural Language Processing (NLP) methods and Machine Learning (ML) models for predicting Brazilian stock returns based on news articles.

## Motivation

Financial markets are notoriously complex and influenced by various factors, including economic indicators, political events, and, to some extent, news sentiment. This project aims to explore the feasibility of using news text as a non-traditional data source to predict stock returns, potentially providing valuable insights for investors and analysts.

## Data and Methodology

- Data Source: G1, the most prominent news portal in Brazil.
- Data Acquisition: Utilizing the `beatfulsoup` library, we scrape relevant news articles related to Brazilian stocks.
- Text Preprocessing: The raw text undergoes cleaning and feature engineering to prepare it for ML models. This includes steps like tokenization, stop word removal, stemming/lemmatization, and TF-IDF vectorization.
- Time Series Splitting: To prevent data leakage and ensure robust model evaluation, we implement time series splitting for training, validation, and testing sets.
- AutoML: We leverage AutoML libraries like `Pycaret` or to automate the search for the optimal ML model and hyperparameters for return prediction.

## Key Features

- Focus on NLP and ML for financial forecasting: This project delves into the intersection of NLP and ML, applying them to a real-world financial problem.
- Data acquisition from a relevant source: Utilizing G1 news articles ensures the data reflects real-world news impacting the Brazilian market.
- Leakage avoidance: Time series splitting guarantees model training and evaluation on non-overlapping data, preventing biased results.
- AutoML for efficient model selection: AutoML simplifies the process of finding the best-performing model for the specific task.

## Current Progress

The project is currently under development. The initial stages of data acquisition, preprocessing, and feature engineering have been completed. The next steps involve implementing AutoML and evaluating the performance of various models for return prediction.

## Future Directions

- Model comparison and selection: Analyze and compare the performance of various ML models identified by AutoML.
- Feature engineering exploration: Investigate the effectiveness of different text-based features for improving prediction accuracy.
- Explainability and interpretability: Implement techniques to understand how the models make their predictions and identify the key news elements influencing return.
- Real-time prediction capabilities: Develop a system that ingests real-time news data and provides near-instantaneous return predictions.
- Include Large Language Models (LLM) like ChatGPT.
- Contributions and Collaborations

We welcome contributions and collaborations from the community. Feel free to fork the repository, suggest improvements, or share your own insights and experiences related to NLP and financial forecasting.

## Disclaimer:

This project is for educational and research purposes only and should not be interpreted as financial advice.

Enjoy exploring the code and contributing to the project!
