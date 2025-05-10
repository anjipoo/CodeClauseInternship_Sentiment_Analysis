# Sentiment Analysis and Customer Segmentation

This project analyzes the Women's E-commerce Clothing Reviews dataset to segment customers and classify review sentiments.

## Overview
- **Dataset**: [Women's E-commerce Clothing Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)
- **Tasks**:
  - **Clustering**: Uses K-Means to segment customers based on purchase frequency and average rating.
  - **Sentiment Analysis**: Classifies reviews as Negative, Neutral, or Positive using Logistic Regression with TF-IDF.
- **Visualizations**:
  - Elbow plot for cluster selection.
  - Scatter plot of customer segments.
  - Sentiment distribution bar plot.
  - Word cloud for Positive reviews.
  - Confusion matrices for Negative, Positive, Neutral.
  - Sentiment distribution by cluster.

## Files
- `preprocess.ipynb`: Jupyter Notebook with code, analysis, and visualizations.
- `.gitignore`: Excludes virtual environment and dataset.

## Requirements
```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn wordcloud
```

## Usage

1. clone the repo:
```bash
git clone https://github.com/anjipoo/CodeClauseInternship_Sentiment_Analysis.git
```
2. install dependencies in virtual environment:
3. download dataset from kaggle
4. run `preprocess.ipynb` in Jupyter Notebook.

## Results
1. **clustering**
2. **sentiment analysis**: 82% accuracy in classifying reviews as Negative, Neutral, or Positive.
3. **insights**