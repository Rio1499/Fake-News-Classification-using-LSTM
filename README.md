# Fake News Detection using LSTM

This project involves building a fake news detection model using LSTM (Long Short-Term Memory) networks for text classification.

## Overview

The goal of this project is to classify news articles as either real or fake based on their content. The dataset used for training consists of news articles labeled as real or fake.

## Requirements

- Python 3.x
- Libraries: Pandas, NumPy, TensorFlow, NLTK, Scikit-learn

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/username/fake-news-lstm.git
    ```

2. Install the required libraries:

    ```bash
    pip install pandas numpy tensorflow nltk scikit-learn
    ```

3. Download NLTK stopwords:

    ```python
    import nltk
    nltk.download('stopwords')
    ```

## Dataset

The dataset used for training the model is available in the `train.csv` file. It contains columns:

- `id`: Unique identifier for each news article.
- `title`: Title of the news article.
- `author`: Author of the news article.
- `text`: Content of the news article.
- `label`: Binary label indicating real (0) or fake (1) news.

## Usage

1. Run `fake_news_detection.ipynb` to train the LSTM model for fake news detection.
2. Explore different hyperparameters, model architectures, and techniques for better performance.
3. Evaluate the model using various evaluation metrics to assess its performance.

## Model Performance

- Accuracy achieved: ~57%
- Precision (for fake news): 0.0
- Recall (for fake news): 0.0
- F1-score (for fake news): 0.0

## Improving Model Performance

- Address class imbalance.
- Hyperparameter tuning: Adjust dropout rates, learning rate, batch size, LSTM units.
- Explore pre-trained word embeddings.
- Fine-tune the prediction threshold.
- Analyze misclassifications for insights.

## Contributors

- [Your Name](https://github.com/username)
- [Collaborator Name](https://github.com/collaborator)

## License

This project is licensed under the [MIT License](LICENSE).
