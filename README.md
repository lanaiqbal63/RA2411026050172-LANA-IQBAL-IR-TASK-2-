# Text Classification Battle

## Overview
A comparative study of four machine learning algorithms for BBC News topic classification using Python and TF-IDF.

## Dataset
- **Source:** [Kaggle BBC News Dataset](https://www.kaggle.com/datasets/yufengdev/bbc-fulltext-and-category)
- **Classes:** Business, Entertainment, Politics, Sport, Tech
- **Preprocessing:** Lowercasing, tokenization, stop-word removal and TF-IDF feature extraction.

## Algorithms
1. Decision Tree
2. K-Nearest Neighbours (KNN)
3. Support Vector Machine (SVM)
4. Multinomial Naïve Bayes

## Methodology
- 80:20 stratified train-test split
- Evaluation using Accuracy, Precision, Recall and F1-score
- Confusion matrices and performance comparison graphs
- Training and testing time analysis
- What-if experiment comparing KNN with K = 3, 5 and 7

## Technologies
Python, Google Colab, Pandas, Matplotlib, Seaborn and Scikit-learn.

## How to Run
1. Download the dataset from Kaggle.
2. Open the notebook in Google Colab.
3. Upload the dataset when prompted.
4. Run all cells in order to train and evaluate the models.

## Results
The best-performing classifier is selected based on the experimental results, including weighted F1-score and accuracy.ct
