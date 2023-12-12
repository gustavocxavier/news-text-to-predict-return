# News Text to Predict Return


## Overview

The "news-text-to-predict-return" project is a research initiative aimed at exploring Natural Language Processing (NLP) methods and Machine Learning (ML) models for predicting the stock returns of the Brazilian stock market. The project utilizes data from G1, the leading news portal in Brazil, to extract relevant textual information. The primary goal is to leverage NLP and ML techniques to analyze news content and forecast stock returns.

## Motivation

Financial markets are notoriously complex and influenced by various factors, including economic indicators, political events, and, to some extent, news sentiment. This project aims to explore the feasibility of using news text as a non-traditional data source to predict stock returns, potentially providing valuable insights for investors and analysts.

## Key Features

- Focus on NLP and ML for financial forecasting: This project delves into the intersection of NLP and ML, applying them to a real-world financial problem.
- Data acquisition from a relevant source: Utilizing G1 news articles ensures the data reflects real-world news impacting the Brazilian market.
- Leakage avoidance: Time series splitting guarantees model training and evaluation on non-overlapping data, preventing biased results.
- AutoML for efficient model selection: AutoML simplifies the process of finding the best-performing model for the specific task.

## Learn more

### Data Collection

To gather raw text data, the project employs the BeautifulSoup library to scrape news articles from the news portal. This ensures a diverse and comprehensive dataset for training and evaluation.

### Text Pre-processing

The raw text undergoes cleaning and feature engineering to prepare it for ML models. Text pre-processing is a crucial step in preparing the data for modeling. Various techniques are applied to clean and structure the text data, making it suitable for input into ML models. This includes steps like tokenization, stop word removal, stemming/lemmatization, and TF-IDF vectorization.

### AutoML for Model Selection

The project employs AutoML (Automated Machine Learning) techniques to automate the process of model selection. This involves exploring different ML models and hyperparameter configurations to identify the most effective combination for predicting stock returns based on the news text. In this project, we leverage AutoML libraries like `Pycaret` to automate the search for the optimal ML model and hyperparameters for return prediction.

### Leakage Data Prevention

To maintain the integrity of the predictive models, the project takes special care to prevent data leakage. Time series splitting is utilized to ensure that training and testing data do not overlap chronologically. This approach is essential for realistic evaluation and accurate representation of model performance.

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

## Getting Started

Clone the repository:

   ```bash
   git clone https://github.com/your-username/news-text-to-predict-return.git
   ```

## Contributors

- Gustavo C. Xavier - Professor of Finance UFPB / Head of MECAPLAB
- Haroldo Melo - Researcher on MECAPLAB
- Eduardo Santos - Researcher on MECAPLAB

## Disclaimer

This project is for educational and research purposes only and should not be interpreted as financial advice.

Enjoy exploring the code and contributing to the project!

## License

This project is licensed under the [MIT License](https://spdx.org/licenses/MIT.html). Feel free to fork and modify as needed for your own research or applications.

For any questions or suggestions, please contact [gustavocx@outlook.com].

Happy predicting! 🚀
