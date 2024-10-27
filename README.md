# Text Clarity and Classification Prototype

This project demonstrates a text classification prototype developed for the University of Greenwich that enhances text clarity prediction by leveraging machine learning algorithms. The goal of the project was to build a model capable of predicting clarity issues in text and provide an expected date of compromise, achieving high accuracy and reliable performance metrics.

## Project Overview
- **Duration**: February 2024 - April 2024
- **Institution**: University of Greenwich, London, UK
- **Technologies Used**: Python, Scikit-Learn, Pandas, TF-IDF vectorization, Logistic Regression, Random Forest, One-Class SVM

## Objective
The primary objective of this project was to develop a machine learning model to classify text clarity using labeled data, ensuring high accuracy without overfitting. The prototype was also designed to predict the expected date of compromise for classified text with high precision.

## Features
- **Text Classification**: Predicts clarity in text data with 96% accuracy.
- **Model Performance**: Uses Logistic Regression and Random Forest classifiers for optimal classification, with TF-IDF vectorization for text feature extraction.
- **Overfitting Control**: Ensures robustness with an F1 score as the primary performance metric.
- **Compromise Prediction**: Utilizes a One-Class SVM to predict the date of text clarity compromise, achieving an 80% improvement in prediction accuracy.

## Installation

Clone the repository and install the required dependencies.

```bash
git clone https://github.com/username/text-clarity-classification.git
cd text-clarity-classification
pip install -r requirements.txt
