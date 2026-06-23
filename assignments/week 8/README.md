## Week 08– NLP Pipeline and Text Classification
# Task Overview
This assignment builds a complete Natural Language Processing pipeline in Python to classify customer return reasons for a Canadian retailer. The work covers loading and inspecting a labeled review dataset, cleaning and normalizing raw text, exploring word frequency patterns, and extracting linguistic structure. 

# Repository Contents
Main Jupyter notebook is Assignment 8(AI Prog).ipynb

# Dataset summary 
Source: NLP_Dataset_10_Ecommerce_Return_Reason.xlsx
Target variable: Return Reason

# Pipeline and Key Results
 Preprocessing steps: lowercasing, hashtag/punctuation/number removal, tokenization, stopword removal, lemmatization (NLTK)
Algorithm: Multinomial Naive Bayes
Train/test split: 80% / 20%, stratified (96 / 24 records)
Metric	Score
Accuracy	100%
Precision (all classes)	1.00
Recall (all classes)	1.00
F1-Score (all classes)	1.00
# Dependencies
pandas

nltk

scikit-learn

matplotlib

openpyxl
# Use
Open Assignment 8(AI Prog).ipynb in Google Colab or Jupyter Notebook.
Update the dataset path in the first cell to point to your local copy of NLP_Dataset_10_Ecommerce_Return_Reason.xlsx.  

