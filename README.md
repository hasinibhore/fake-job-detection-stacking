# Fake Job Posting Detection using Multi-Layer Stacking Ensemble

## Overview
Detects fake job postings using a 3-layer stacking ensemble
combining NLP (TF-IDF) and categorical features.

## Model Architecture
Layer 1: Logistic Regression, Decision Tree, Naive Bayes, SVM (OOF)
Layer 2: Random Forest + Logistic Regression (Meta models)
Layer 3: Final Logistic Regression

## Results
Test Accuracy: 95.12%

## Tech Stack
Python | Scikit-learn | TF-IDF | Pandas | NumPy

## How to Run
1. Open notebook in Google Colab
2. Upload CompiledjobListNigeria.csv
3. Run all cells
