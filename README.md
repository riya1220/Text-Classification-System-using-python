# Email Spam Detection using NLP & Machine Learning
This project classifies emails and SMS messages as spam or not spam using Natural Language Processing (NLP) and Machine Learning. It preprocesses text, extracts features using TF-IDF and Word Embeddings, and trains models like Logistic Regression and Naive Bayes to detect spam with high accuracy.

## Features
- Preprocesses text with tokenization, stopword removal, stemming, and lemmatization
- Extracts features using TF-IDF, Count Vectorization, and Word Embeddings
- Trains models like Logistic Regression and Naive Bayes for classification
- Achieves high accuracy in detecting spam emails and messages

## Tech Stack
- Languages: Python
- Libraries: Pandas, NumPy, Scikit-learn, NLTK, Gensim, Matplotlib
- Techniques: NLP, Text Preprocessing, Machine Learning

## Dataset
- Source: SMS Spam Collection Dataset
- Size: 5,572 messages
- Labels: "Spam" (Unwanted messages) & "Ham" (Legitimate messages)

## Installation & Setup  
- Clone the repository: 
   ```bash
   git clone https://github.com/riya1220/spam-detection.git
   cd spam-detection
   ```
- Install dependencies:
  ```bash
  pip install -r requirements.txt
  ```
- Run the project:
  ```bash
  python main.py
  ```


## Results
- Accuracy: 95%
- Model Used: Logistic Regression, Naive Bayes, Support Vector Machine, Random Forest

