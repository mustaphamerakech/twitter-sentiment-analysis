# twitter-sentiment-analysis



This project aims to classify tweets into positive and negative sentiments using a Logistic Regression model. The dataset used for training and evaluation comes from the [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140/data) dataset available on Kaggle.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Results](#results)
- [License](#license)

## Introduction

Social media has become an essential part of communication, and analyzing the sentiments expressed in tweets can provide valuable insights into public opinion. This project utilizes machine learning techniques to classify tweets based on their sentiments, helping in understanding user emotions and feedback.

## Dataset

The dataset used in this project is sourced from Kaggle's Sentiment140, which contains 1.6 million tweets labeled as positive (1) or negative (0). The dataset includes two main columns:

- `target`: Indicates the sentiment (0 for negative, 1 for positive).
- `stemmed_data`: Contains the processed text of the tweets after stemming.

You can download the dataset from [this link](https://www.kaggle.com/datasets/kazanova/sentiment140/data).

## Installation

To run this project, you'll need the following Python packages:

- numpy
- pandas
- scikit-learn

You can install the required packages using pip:

```bash
pip install numpy pandas scikit-learn

 
