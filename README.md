# 📧 Email & SMS Spam Classifier

An end-to-end Natural Language Processing (NLP) project that classifies Email and SMS messages as **Spam** or **Not Spam (Ham)** using Machine Learning techniques. The application is deployed using **Streamlit** and provides real-time predictions through an interactive web interface.

---

## 🚀 Live Demo

🔗 Add Your Streamlit App Link Here

Example:

https://your-app-name.streamlit.app

---

## 📌 Project Overview

Spam messages are a common problem in digital communication. This project uses Natural Language Processing (NLP) and Machine Learning algorithms to automatically classify messages as Spam or Not Spam.

The project covers the complete Machine Learning lifecycle:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Text Preprocessing
- Feature Engineering
- Model Building
- Model Evaluation
- Model Deployment

---

## 🛠️ Tech Stack

- Python
- Pandas
- NumPy
- NLTK
- Scikit-Learn
- Streamlit
- Pickle
- GitHub
- Streamlit Community Cloud

---

## 📊 Dataset

Dataset Used:

SMS Spam Collection Dataset

Target Classes:

- Ham (0)
- Spam (1)

---

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

### Text Cleaning

- Convert text to lowercase
- Tokenization
- Remove special characters
- Remove stopwords
- Stemming using Porter Stemmer

Example:

Input:

Congratulations! You have won a FREE lottery prize.

Processed Text:

congratul free lotteri prize

---

## ⚙️ Feature Engineering

TF-IDF (Term Frequency – Inverse Document Frequency) Vectorization was used to convert text into numerical features.

```python
TfidfVectorizer(max_features=3000)
```

This helps assign higher importance to meaningful and rare words while reducing the impact of common words.

---

## 🤖 Machine Learning Models Evaluated

The following algorithms were trained and compared:

- Support Vector Classifier (SVC)
- K-Nearest Neighbors (KNN)
- Multinomial Naive Bayes
- Gaussian Naive Bayes
- Bernoulli Naive Bayes
- Logistic Regression
- Decision Tree
- Random Forest
- AdaBoost
- Gradient Boosting
- XGBoost
- Extra Trees Classifier
- Voting Classifier
- Stacking Classifier

---

## 📈 Evaluation Metrics

Models were evaluated using:

- Accuracy Score
- Precision Score

Since Spam Detection is a classification problem where false positives are costly, Precision was given special importance during model evaluation.

---

## 🏆 Final Model Selection

Although ensemble models such as Voting Classifier achieved slightly better performance, **Multinomial Naive Bayes** was selected for deployment because it provided:

- High Accuracy
- High Precision
- Fast Prediction Speed
- Low Memory Usage
- Easy Deployment
- Better Scalability

Final Model:

```python
MultinomialNB()
```

---

## 🌐 Web Application

A Streamlit-based web application was developed for real-time message classification.

Features:

- User-friendly interface
- Real-time prediction
- Spam / Not Spam classification
- Lightweight deployment

---

## 📂 Project Structure

```text
sms_spam_classifier/
│
├── app.py
├── model.pkl
├── vectorizer.pkl
├── requirements.txt
├── README.md
└── spam.csv
```

---

## ▶️ Installation

Clone the repository:

```bash
git clone https://github.com/your-username/sms-spam-classifier.git
```

Move into project directory:

```bash
cd sms-spam-classifier
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the Streamlit application:

```bash
streamlit run app.py
```

---

## 📸 Application Screenshot

Add your deployed app screenshot here.

Example:

![App Screenshot](screenshot.png)

---

## 🎯 Key Learnings

- Natural Language Processing (NLP)
- Text Preprocessing
- TF-IDF Vectorization
- Machine Learning Model Selection
- Ensemble Learning
- Model Deployment using Streamlit
- GitHub Version Control

---

## 🔮 Future Improvements

- Deep Learning based Spam Detection
- BERT/Transformer Integration
- Probability Score Display
- User Feedback Collection
- Multi-language Spam Detection

---

## 👨‍💻 Author

Devank Verma

LinkedIn: Add Your LinkedIn Link

GitHub: Add Your GitHub Profile Link

---

## ⭐ If you found this project useful, please consider giving it a star!
