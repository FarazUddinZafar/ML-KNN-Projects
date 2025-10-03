# ML-KNN-Projects
titanic_knn.ipynb → Jupyter/Colab notebook for Titanic dataset

iris_knn.ipynb → Iris dataset KNN

sms_tfidf_knn.ipynb

# 🧠 KNN Classification Projects (Iris • Titanic • SMS Spam)

This repository contains multiple **Machine Learning projects** showcasing the use of **K-Nearest Neighbors (KNN)** algorithm on different types of datasets — from numerical (Iris), to real-world mixed data (Titanic), and text data (SMS Spam using TF-IDF).  

Each project focuses on **data preprocessing, model training, hyperparameter tuning**, and **evaluation using accuracy, confusion matrix, and classification reports**.

---

## 📂 Project Structure

---

## 📊 1. **Iris Dataset — Basic KNN**
- **Dataset**: Built-in Iris dataset (150 samples, 4 features, 3 classes)
- **Goal**: Classify iris flowers into species using KNN
- **Key Steps**:
  - Train-test split
  - KNN classification with varying `k` values
  - Accuracy visualization vs K
- **Result**: Achieved ~97% accuracy with optimal K

---

## 🚢 2. **Titanic Dataset — Real-World Example**
- **Dataset**: Seaborn Titanic dataset (passenger survival data)
- **Goal**: Predict passenger survival
- **Key Steps**:
  - Data cleaning (fill missing values)
  - Encoding categorical variables with `LabelEncoder`
  - Model training with KNN
  - Hyperparameter tuning with `GridSearchCV`
- **Result**: Achieved solid accuracy and identified the best K using cross-validation.

---

## ✉️ 3. **SMS Spam Classification — Text + TF-IDF**
- **Dataset**: SMS Spam Collection dataset ([Source](https://raw.githubusercontent.com/justmarkham/pycon-2016-tutorial/master/data/sms.tsv))
- **Goal**: Classify messages as spam or ham using text features
- **Key Steps**:
  - Text vectorization using `TfidfVectorizer`
  - Train-test split and KNN classification
  - Model evaluation using confusion matrix & classification report
- **Result**: Achieved good accuracy on text classification with simple preprocessing.

---

## 🧪 Technologies Used
- Python 🐍  
- scikit-learn  
- Pandas  
- Matplotlib / Seaborn  
- TF-IDF (Text Feature Extraction)

---

## ⚡ Future Improvements
- Compare KNN with other algorithms (Logistic Regression, Decision Trees, Naive Bayes)  
- Implement cross-validation more extensively  
- Deploy one of the models as a small API or web app

---

## 📬 Contact
**Faraz Uddin Zafar**  
🔗 (https://github.com/FarazUddinZafar/) 
💼 Machine Learning & Web Developer

---

⭐ **If you like this project, don’t forget to star the repo!**


