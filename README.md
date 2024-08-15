# Spark-MLLib-Twitter-Sentiment-Analysis
Sentiment Analysis on the Kaggle Sentiment140 Dataset with PySpark and MLLib

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MustafaAbbasi98/Spark-MLLib-Twitter-Sentiment-Analysis/blob/main/PySpark_MLLib_Tweet_Sentiment_Analysis.ipynb)


## Description
This repository contains a jupyter notebook for preprocessing and training a `RandomForest` model with `PySpark` and `MLLib`.

## Usage
1. Clone the repository.
2. Install required dependencies.
3. Open the notebook in Jupyter Notebook or Google Colab.

## Overview
The notebook shows how to achieve the following tasks:
1. Installing and setting up PySpark (especially on Colab).
2. Setting up kaggle and downloading the [Sentiment140](https://www.kaggle.com/datasets/kazanova/sentiment140) dataset for sentiment analysis.
3. Loading dataset in either Pandas or Spark.
4. Using the pandas-on-spark dataframe (Spark pandas api) to perform pandas-like processing on dataframes using Spark.
5. Creating and training a Spark MLLib Pipeline with several transformers and a `RandomForest` model.
6. Evaluating Spark MLLib models using built-in evaluators.
7. Performing hyperparameter tuning using MLLib's built-in `CrossValidator`.
8. Additional steps to consider.
