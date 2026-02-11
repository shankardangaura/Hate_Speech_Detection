# Hate_Speech_Detection
A machine learning project focused on detecting hate speech in text data. The system uses TF-IDF vectorization for feature extraction, dimensionality reduction (SVD), and a trained classification model to accurately categorize unseen tweets as hate speech or non-hate speech.

# Objectives
-Detect hate speech from text data

-Compare multiple classification algorithms

-Perform hyperparameter tuning to improve performance

-Evaluate models using multiple metrics

-Save and deploy the final optimized model

# Dataset

-The dataset contains labeled text samples.

-Target classes: Hate Speech / Non-Hate Speech

-Data preprocessing includes:

  -Lowercasing
  
  -Removing punctuation & special characters
  
  -Stopword removal
  
  -Tokenization

# Project Workflow

1️⃣ Data Preprocessing

-Text cleaning

-Tokenization

-Stopword removal

-Vectorization using TF-IDF

2️⃣ Feature Engineering

-Applied Truncated SVD for dimensionality reduction

3️⃣ Model Training

The following models were trained and compared:

-Logistic Regression

-Linear SVM

-SVC (RBF)

-Random Forest

-Gradient Boosting

-KNN

-Bernoulli Naive Bayes

4️⃣ Model Selection

Best model selected based on accuracy and F1-score.

5️⃣ Hyperparameter Tuning

-Used GridSearchCV / RandomizedSearchCV

-Applied cross-validation

-Optimized parameters to reduce overfitting

6️⃣ Model Evaluation

Models were evaluated using:

-Accuracy

-Precision

-Recall

-F1-score

-Confusion Matrix

-ROC-AUC

-Log Loss

7️⃣ Model Saving & Deployment

Final model saved using Joblib

Pipeline includes:

-TF-IDF Vectorizer

-SVD Transformer

-Trained Classifier

8️⃣ Testing on Unseen Data

-Model tested on new input text

-Successfully predicted hate / non-hate speech
