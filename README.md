# 🚜 Predicting the Sale Price of Bulldozers using Machine Learning

## Overview
In this project, we use machine learning to predict the sale price of bulldozers based on their characteristics and past sales data.

- **Inputs:** Bulldozer characteristics such as make year, base model, model series, state of sale (e.g. which US state it was sold in), drive system, and more.
- **Outputs:** Bulldozer sale price (in USD).

Since we're predicting a number, this is a **regression problem**. And since we're predicting future sales based on past sales data, it's also a **time series / forecasting problem**.

## Data & Evaluation
The data and evaluation metric used in this project come from the [Kaggle Bluebook for Bulldozers competition](https://www.kaggle.com/c/bluebook-for-bulldozers). The evaluation metric is **Root Mean Square Log Error (RMSLE)**.

## Techniques
The techniques used in this project were inspired by and adapted from the [fast.ai Machine Learning course](https://www.fast.ai/).

## Project Structure
```
bulldozer-price-prediction-project/
│
├── end-to-end-bluebook-bulldozer-price-regression.ipynb   # Main notebook
├── .gitignore                                              # Ignores data/env folders
└── README.md                                              # This file
```

## How to Run
1. Clone this repo
2. Download the dataset from [Kaggle](https://www.kaggle.com/c/bluebook-for-bulldozers/data) and place it in a `data/` folder
3. Set up a Python environment and install dependencies
4. Open and run the notebook
