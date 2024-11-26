# IIT Madras Machine Learning Challenge

This repository contains the solution for the IIT Madras Machine Learning Challenge, where the goal is to build a predictive model using advanced preprocessing and deep learning techniques.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Dataset](#dataset)
- [Methodology](#methodology)
- [Technologies Used](#technologies-used)
- [Results](#results)
- [License](#license)

## Project Overview

The project is designed to analyze the given training data, extract meaningful insights, and develop a robust predictive model using advanced deep learning methods. The focus is on achieving low error rates and generalizability across unseen data.

## Features

- **Data Preprocessing**:
  - Missing value imputation.
  - Outlier detection and scaling using RobustScaler.
- **Exploratory Data Analysis (EDA)**:
  - Visualized distributions and correlations to understand the dataset.
- **Deep Learning Architecture**:
  - Sequential and Bidirectional LSTM models.
  - Attention mechanisms to improve feature importance learning.
- **Performance Evaluation**:
  - Mean Absolute Error (MAE) as the primary metric.

## Dataset

- **Train Dataset**: `train.csv` - Contains labeled data for training the model.
- **Test Dataset**: `test.csv` - Used for making predictions and evaluating performance.

## Methodology

1. **Data Preprocessing**:
   - Handled missing values, scaled numerical data, and performed feature engineering.
   - Implemented robust scaling to manage outliers.

2. **Exploratory Data Analysis**:
   - Analyzed data distributions, correlations, and feature importance.

3. **Model Development**:
   - Designed LSTM-based models for sequence prediction tasks.
   - Added Attention layers for feature weighting.

4. **Performance Evaluation**:
   - Used Mean Absolute Error (MAE) to evaluate the model's accuracy and robustness.

## Technologies Used

- **Programming Language**: Python
- **Libraries**:
  - Data Handling: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Deep Learning: `tensorflow`, `keras`
  - Preprocessing: `scikit-learn`

## Results
- The deep learning model demonstrated promising performance with low Mean Absolute Error (MAE). Further optimization and testing are ongoing.

## License
- This project is licensed under the [MIT License]([url](https://github.com/BenedictRaymond/IIT-Madras-ML-Challenge/blob/main/LICENSE)).
