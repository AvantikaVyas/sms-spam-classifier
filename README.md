# SMS Spam Classifier:
A beginner machine learning project that classifies SMS messages as spam or ham.

This project uses Natural Language Processing (NLP) and machine learning to detect spam messages. The pipeline is:
Dataset → TF-IDF → Multinomial Naive Bayes → Prediction → Evaluation

## Technologies:
- Python
- Pandas
- Scikit-learn
- Matplotlib
- Jupyter Notebook

## Dataset:
The project uses the SMS Spam Collection dataset.
Each message is labeled as either:
- 'ham' -> legitimate message
- 'spam' -> unwanted message

## Method:
### 1. Data Preparation:
The SMS messages and their labels are separated into input ('x') and target ('y').

### 2. Train-Test Split:
The dataset is divided into 80% training data and 20% test data.

### 3. TF-IDF:
TF-IDF converts the text messages into numerical features.

### 4. Classification:
Multinomial Naive Bayes is trained on the TF-IDF features.

### 5. Evaluation:
The model is evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

## Results:
The baseline model achieved approximately:
- Accuracy: 96%
- Spam Precision: 1.00
- Spam Recall: 0.70
- Spam F1-score: 0.83

The model performs well overall but misses some spam messages.

## What I Learned:
Through this project, I learned how to build an end-to-end text classification pipeline, including data preprocessing, TF-IDF vectorization, model training, evaluation, and error analysis.
