# Comparative Analysis of Machine Learning Models in Financial Sentiment Analysis

## Overview

This project focuses on a comprehensive comparative study of various machine learning models for analysing financial sentiments (positive, neutral, negative) from textual data. Utilising modern research methodologies and adopting cutting-edge machine learning techniques, this study aims to identify the most effective model based on accuracy, efficiency, and scalability.

## Project Structure

This repository is organised into several directories, each containing specific components of the project:

- `0_EDA`: Notebooks for exploratory data analysis to understand the datasets' characteristics.
- `1_Logistic_Regression` - `9_OpenAI`: Directories for each machine learning model tested, including logistic regression, random forests, decision trees, XGBoost, CNN, LSTM, BERT, and various OpenAI models. Each folder contains Jupyter notebooks for individual experiments and full dataset evaluations.
- `Data`: Contains all datasets used in `.feather` format, allowing for efficient I/O operations.
- `Data_Generation`: Notebooks for data preprocessing and augmentation.
- `Datasets`: Raw datasets and their respective labels used in the experiments.
- `Figs`: Contains figures generated from evaluations of models.
- `Notes`: Directory of notes from individual and group meetings.
- `Utility`: Includes figure generating and dataset sampling noteboks.

## Installation

Before running any notebook, ensure that all dependencies are installed:

```bash
pip install -r requirements.txt
```

## Project Presentation Link

[Youtube Video](https://youtu.be/3i2GwZLAbUA)