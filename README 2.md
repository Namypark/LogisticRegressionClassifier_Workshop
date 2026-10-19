# Logistic Regression Classifier Workshop

## Overview

This workshop introduces **logistic regression for binary classification**, using student study hours to predict pass/fail outcomes. Students connect the mathematical foundations of probability-based classification with Python implementation and evaluation.

## Learning Objectives

- Explain the **sigmoid function** and how predicted probabilities become class labels through a decision threshold.
- Identify features, labels, classifiers, and **decision boundaries**.
- Train a logistic regression classifier with **scikit-learn**, generate predictions, and assess accuracy.
- Derive and interpret **binary cross-entropy (log-loss)**, including its penalty for confidently incorrect predictions.
- Visualize sigmoid behavior and log-loss curves.
- Implement logistic regression **from scratch**, using vectorized Python, log-loss, and **gradient descent** to optimize model weights.

## In-Class Activity and Deliverables

Students develop and document their own binary classifier in a Jupyter Notebook, commit their work to GitHub, and exchange code reviews with a peer. Each student prepares three technical talking points and discusses their implementation and reflections.

Submit a `PairProgrammingReport.ipynb` notebook containing the cross-entropy implementation and talking points, plus a brief team PDF report through the course dropbox. Follow the notebook's submission instructions.

## Project Files

This workshop repository additionally includes the following notebooks and data assets:

- [`Pair Programming.ipynb`](Pair%20Programming.ipynb) — collaborative notebook for pair programming and model-building exercises.
- [`data/`](data) — folder containing the dataset used in the workshop.
  - [`data/StudentPerformanceFactors.csv`](data/StudentPerformanceFactors.csv) — student performance dataset used for classification tasks.

## Peer Programming Notebook Summary

The [`Pair Programming.ipynb`](Pair%20Programming.ipynb) notebook focuses on building a logistic regression model from scratch using the `StudentPerformanceFactors.csv` dataset. It introduces a practical workflow for predicting whether a student passes an exam based on study hours, while demonstrating binary classification concepts such as the sigmoid function, decision threshold, and cross-entropy loss.

The notebook walks through data loading, feature engineering, train/test splitting, model training with batch gradient descent, and evaluation of model behavior. It emphasizes the relationship between study time and outcomes, while also explaining the limits of prediction and the importance of validating the model on unseen data. This notebook is designed to support collaborative learning, code review, and a deeper understanding of how logistic regression works under the hood.

## Getting Started

Open [`LogisticRegressionClassifier_Workshop.ipynb`](LogisticRegressionClassifier_Workshop.ipynb) and follow the activities in sequence. Install dependencies using `pip install -r requirements.txt`.
