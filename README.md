## ⚠️ Note
This model is trained on a Kaggle dataset and differs from Gmail's spam filter,
which uses large-scale user behavior and metadata.

# Email Spam Classifier using Naive Bayes

## 📌 Project Overview
This project builds an email spam classifier using the Naive Bayes algorithm.
The goal is to classify emails as **Spam** or **Ham (Not Spam)** using text data.

## 📂 Dataset
- Source: Kaggle – https://www.kaggle.com/datasets/satyajeetbedi/email-hamspam-dataset
- Labels: ham (0), spam (1)
- Encoding issue handled using `latin-1`

## 🧠 Approach
1. Data cleaning and preprocessing
2. Label encoding (ham → 0, spam → 1)
3. Text vectorization using CountVectorizer
4. Classification using Multinomial Naive Bayes
5. End-to-end pipeline using sklearn
6. Model evaluation using confusion matrix and classification report

## ⚙️ Tech Stack
- Python
- Pandas
- scikit-learn
- Naive Bayes
- CountVectorizer
- Pipeline

## 📊 Results
- Accuracy: ~98%
- Strong precision and recall for spam class

## 🧪 Real Email Testing
The trained model was tested on real emails from an inbox.
It correctly classified scam-style spam but classified marketing emails as ham,
highlighting the importance of dataset definition.

## 🚀 Key Learnings
- Difference between scam spam and marketing spam
- Importance of vectorization for text data
- How pipelines prevent data leakage
- Why Naive Bayes is effective for text classification

## 🔮 Future Improvements
- Use TF-IDF Vectorizer
- Try Logistic Regression / SVM
- Improve recall for spam class
