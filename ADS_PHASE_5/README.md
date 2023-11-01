# IMDb Score Prediction for Netflix Original Films

![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)

Predict IMDb scores for Netflix original films using Linear Regression. This project analyzes movie data, handles missing values, encodes categorical features, and trains a model for score prediction.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Requirements](#requirements)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Accuracy Calculation](#accuracy-calculation)
- [Conclusion](#conclusion)
- [License](#license)

## Introduction

IMDb scores are essential for assessing movie quality. This project utilizes Linear Regression to predict IMDb scores for Netflix original films. It involves data preprocessing, model training, evaluation, and accuracy calculation.

## Dataset

- The dataset used: [Netflix Original Films IMDb Scores](https://www.kaggle.com/datasets/luiscorter/netflix-original-films-imdb-scores)
- Features include movie title, genre, language, release date, director, and cast.

## Requirements

- Python 3
- Pandas
- Matplotlib
- Scikit-Learn
- Chardet (for encoding detection)

## Data Preprocessing

- Detect encoding and handle missing values.
- Encode categorical variables.
- Normalize numerical features.
- Feature engineering, e.g., rolling means.

## Model Training

- Split data into training and test sets.
- Use Linear Regression for predictions.
- Evaluate using Mean Squared Error and R-squared.

## Model Evaluation

- Assess the model's performance with MSE and R2.

## Accuracy Calculation

- Make predictions and calculate accuracy.

## Conclusion

This project provides insights into the IMDb scores of Netflix original films. Feel free to ask questions and share feedback.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
