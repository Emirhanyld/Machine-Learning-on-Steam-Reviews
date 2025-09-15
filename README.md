# Steam Reviews Sentiment Analysis

This project applies **machine learning models** to predict whether Steam game reviews are **recommended or not recommended**.

## Dataset
- Collected around **100,000 reviews** from Steam.  
- Binary classification:  
  - **80% Positive (Recommended)**  
  - **20% Negative (Not Recommended)**  

## Features
- Preprocessing of text data (stopword removal, stemming, TF-IDF, n-grams).  
- Models used: **K-Nearest Neighbors (KNN), Naive Bayes, Decision Tree**.  
- Dimensionality reduction with **Feature Selection** and **PCA**.  
- Evaluation with Accuracy, Precision, Recall, and F1-Score.  

## Results
You can view the detailed results in the PDF file: [results.pdf](results.pdf)  

## Files
- `ml_steam_reviews.ipynb` → Jupyter Notebook with training and evaluation.  
- `results.pdf` → Model performance comparison.  

## Requirements
- Python 3.x  
- Libraries: scikit-learn, pandas, numpy, matplotlib, nltk  

## Usage
1. Open the notebook:  
   ```bash
   jupyter notebook ml_steam_reviews.ipynb
   ```
2. Run all cells to train models and view results.
