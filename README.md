# Disaster Tweet Prediction

This repository contains code and resources for predicting whether tweets are about real disasters or not. The task is approached using machine learning techniques and Natural Language Processing (NLP). The goal is to build a model that accurately classifies tweets from Twitter as either describing real disasters (target = 1) or not (target = 0).

## Competition Overview

This project is based on a Kaggle competition [NLP Getting Started - Disaster Tweets](https://www.kaggle.com/competitions/nlp-getting-started/overview), aimed at beginners in NLP. The dataset includes text from tweets, along with optional metadata such as keyword and location. The evaluation metric used is the F1 score, which balances precision and recall.

## Dataset

The dataset consists of:
- **train.csv**: Training set containing tweets labeled with their target (0 or 1).
- **test.csv**: Test set for which predictions need to be made.
- **sample_submission.csv**: Sample submission format.

## Approach

1. **Data Preprocessing**: Text cleaning, tokenization, and feature extraction.
2. **Feature Engineering**: Additional features like tweet length and punctuation count.
3. **Modeling**: Utilizing an XGBoost classifier with hyperparameter tuning to predict tweet labels.
4. **Evaluation**: Performance assessed using the F1 score on a validation set.

## Repository Structure

- **`data/`**: Folder containing the dataset files.
- **`notebooks/`**: Jupyter notebooks for data exploration, preprocessing, modeling, and evaluation.
- **`scripts/`**: Python scripts for preprocessing, modeling, and submission generation.
- **`README.md`**: Detailed documentation including setup instructions, methodology, and results.

## Usage

To replicate the results:
1. Clone the repository.
2. Install the required dependencies (`requirements.txt`).
3. Run the notebooks or scripts sequentially to preprocess data, train models, and generate predictions.

## Results

The final model achieved an F1 score of 0.75 on the test set, demonstrating effective prediction of disaster-related tweets.

## Dependencies

- Python 3.7+
- Libraries: pandas, numpy, scikit-learn, nltk, xgboost

## Authors

- Sakshi Fadnavis
