# 📱 SMS Spam Classifier

A Machine Learning-based web application that detects whether a given SMS message is **Spam** or **Not Spam (Ham)**.

The project uses Natural Language Processing (NLP) and Machine Learning techniques to analyze the content of SMS messages and classify them into the appropriate category.

---

## 📌 Project Overview

With the increasing number of unwanted and fraudulent messages, identifying spam SMS messages has become important.

This project aims to automatically classify an SMS message as either:

- 🚨 **Spam** – Unwanted or potentially fraudulent message
- ✅ **Ham** – Normal and legitimate message

The trained Machine Learning model processes the input SMS and predicts its category.

---

## ✨ Features

- 📩 Enter any SMS message as input
- 🤖 Machine Learning-based spam detection
- 🔍 Text preprocessing and feature extraction
- 📊 SMS classification into Spam or Ham
- 🌐 User-friendly web interface
- ⚡ Fast prediction results

---

## 🧠 Machine Learning Approach

The project follows a typical Machine Learning pipeline:

1. **Data Collection**
2. **Data Preprocessing**
3. **Text Cleaning**
4. **Feature Extraction / Text Vectorization**
5. **Model Training**
6. **Model Evaluation**
7. **Model Prediction**
8. **Web Application Integration**

The trained model and text vectorizer are saved as `.pkl` files and used by the application to make predictions on new SMS messages.

---

## 🛠️ Technologies Used

- **Python**
- **Machine Learning**
- **Natural Language Processing (NLP)**
- **Scikit-learn**
- **Pandas**
- **NumPy**
- **Flask**
- **HTML**
- **CSS**
- **Jupyter Notebook**

---

## 📂 Project Structure

```text
SMS-Spam-Classifier/
│
├── .gitignore
│
├── app.py
│   └── Main application file
│
├── model.pkl
│   └── Trained Machine Learning model
│
├── vectorizer.pkl
│   └── Saved text vectorizer used to transform SMS messages
│
├── requirements.txt
│   └── Required Python libraries
│
├── setup.sh
│   └── Setup script for deployment
│
├── sms-spam-detection
│   └── Jupyter Notebook containing data analysis,
│       preprocessing, model training, and evaluation
│
├── spam
│   └── Dataset / project-related file
│
└── README.md
    └── Project documentation
