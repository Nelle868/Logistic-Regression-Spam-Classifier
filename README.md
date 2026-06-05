# Logistic Regression Spam Classifier

A binary classification model built from the ground up in Python that distinguishes spam email from legitimate email using logistic regression.

## Overview

This project trains a logistic regression classifier to flag spam. Raw email text is transformed into a numeric design matrix of binary word occurrence features, the model is fit using scikit-learn, and performance is evaluated using metrics chosen specifically for the filtering task rather than relying on accuracy alone.

## Features

**Feature Engineering**: Transforms raw email text into a binary design matrix where each feature records whether a given word appears in an email.

**Model Training**: Fits a logistic regression classifier using scikit-learn to predict whether an email is spam or legitimate.

**Evaluation Beyond Accuracy**: Evaluates the model using precision, recall, and false positive rate. Demonstrates why accuracy alone is misleading on class imbalanced data where legitimate email outnumbers spam.

**Error Tradeoff Analysis**: Analyzes the tradeoff between false positives and false negatives in the context of a real spam filter, prioritizing the metric that best limits undetected spam reaching the inbox.

## Tech Stack

Python, scikit-learn, NumPy, Pandas. Logistic regression for classification, with precision, recall, and false positive rate for evaluation.

## Running the Project

Open the notebook in Jupyter and run the cells in order. Make sure scikit-learn, NumPy, and Pandas are installed in your environment.
