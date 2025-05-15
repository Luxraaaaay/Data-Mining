# Pilot Study of Cross-fields AI-generated Content Sentiment Analysis

## Introduction
This is the pilot study of cross-fields AI-generated content sentiment analysis, aiming at exploring the feasibility of conducting large-scale research.  
The study is implemented in Jupyter Notebook, the data used comes from Kaggle, and the stopword files come from GitCode. This study focus on using Naive Bayes model and Support Vector Machine to classify the comments on AI-generated content in the fields of advertising, drawing, and technology, as positive and negative. Finally compare the performance of the two models by the values of accuracy, recall, and F1 score, and show the sentiment distribution.  
This study aims to validate the effectiveness of sentiment classification methods for AI-generated content and provide insights for future large-scale research.

## Research Objectives
- To perform sentiment analysis on AI-generated content across different fields.  
- To pre-process and do feature engineering using stopwords and text normalization techniques.  
- To train and evaluate Naive Bayes and SVM classifiers for multi-field sentiment classification.  
- To visualize and compare model performance and sentiment distributions across fields.  

## Study Structure
```
.
├── data/                    # Datasets used in the study (from Kaggle)
├── stopwords-master/        # Stopwords dictionaries (from GitCode)
├── data_processing.ipynb    # Jupyter Notebook contains all code and results (authored by Tang Shiyu)
└── README.md                # This file
```

## Methodology Overview
- **Data Collection & Preprocessing**  
Load datasets from Kaggle.  
Pre-process data: remove special characters, duplicate data, and null values.  
Tokenize and remove stopwords using external dictionaries from GitCode.  
- **Feature Engineering**  
Convert text into numerical features using TF-IDF vectorization.  
- **Model Training**  
Train both Naive Bayes and Support Vector Machine classifiers.  
- **Model Evaluation**  
Evaluate models using key metrics: Accuracy, Recall, Precision, and F1-Score.  
Visualize results using bar graphs and confusion matrices.  

## Results
- Both models achieved reasonable performance in classifying sentiments.  
- SVM showed slightly better accuracy and F1-score than Naive Bayes.  
- Sentiment distribution shows differences in different fields, indicating the importance of field-specific analysis.  

## Requirements
To run this project locally, you will need:  

- Python 3.x  
- Jupyter Notebook  
- Libraries: pandas, chardet, matplotlib, seaborn, jieba, sklearn  

## How to Run
- Clone the repository:
  ```
  git clone https://github.com/Luxraaaaay/Data-Mining.git
  ```
- Navigate to the directory:
  ```
  cd Data-Mining
  ```
- Launch Jupyter Notebook:
  ```
  jupyter notebook
  ```
- Open data_processing.ipynb and run the cells

## Acknowledgments
- Datasets: Kaggle  
- Stopwords dictionaries: GitCode  
- Author: Tang Shiyu  
