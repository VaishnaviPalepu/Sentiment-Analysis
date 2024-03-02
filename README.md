# Sentiment-Analysis

This project performs sentiment analysis on customer review data using machine learning algorithms, natural language processing techniques, and data visualization methods. The analysis aims to understand customer sentiments towards products/services based on their reviews.

Key Features:
- Utilizes machine learning algorithms for sentiment classification
- Applies natural language processing techniques such as tokenization and lemmatization
- Visualizes sentiment distribution and most frequent words/phrases in reviews

Technologies Used: Python, scikit-learn, NLTK, Matplotlib, Seaborn, Plotly.

Data Source: Amazon Customer reviews  from Kaggle.

Analysis Results:
- Identified trends and patterns in customer sentiments towards products/services

Performance Metrics:
- Evaluation metrics: accuracy, precision, recall, F1-score.

- Individual Algorithm Performance:
    Random Forest:
  
    Accuracy:90%
  
    Naive Bayes:
  
    Accuracy:81%
  
    Logistic Regression:
  
    Accuracy:90%
  
    SVM (before hyperparameter tuning):
  
    Accuracy:93%
  
- Hyperparameter Tuning for SVM:

Method: Grid search with cross-validation.

Parameters tuned: C, kernel.

Improved performance metrics: 

Accuracy:93%

Induvidual metrics such as precision,recall and f1-score have improved after tuning.

- Explanation for SVM's Success:
- 
Dataset characteristics favorable for SVM.
SVM's ability to handle high-dimensional data.
Specific strengths of SVM compared to other algorithms.

- Conclusion:
- 
SVM was selected as the final model due to its superior performance after hyperparameter tuning.
The analysis demonstrates the effectiveness of SVM for sentiment analysis on the given dataset.
