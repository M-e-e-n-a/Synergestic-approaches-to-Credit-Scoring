# Synergestic-approaches-to-Credit-Scoring

# Credit Score Classification Project

## Project Overview

This project aims to accurately classify individuals' credit scores into three categories: 'Good', 'Standard', and 'Bad'. By utilizing a publicly available dataset, the project compares several machine learning models to identify the most effective approach for credit score prediction.

## Dataset

The dataset comprises 8 months of credit score data for various individuals, with each month's data serving as a separate record. The preprocessing steps include splitting the data into categorical and numerical sets, encoding, normalization, and feature analysis through a correlation matrix. The target variable has been categorized into three distinct classes for classification purposes.

## Models

Three models are compared in this study:

- Baseline Sequential Model: A simple neural network with fully connected layers.
- Ensemble Learning Model: An ensemble of Random Forest and baseline neural network.
- Ensemble Model with Attention Mechanism: A stacked ensemble that includes Random Forest, Gradient Boosting, and an attention-augmented neural network.
