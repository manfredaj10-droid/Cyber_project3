# Phishing Email Detection Model

A machine learning project that detects whether an email is **Phishing** or **Safe** using Natural Language Processing and Naive Bayes algorithm.

---

## Features

- Detects phishing emails based on text content
- Uses Machine Learning (Naive Bayes)
- Converts text into numerical features
- Displays prediction results clearly
- Calculates model accuracy
- Visualizes performance using Confusion Matrix

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## Project Structure
Phishing-Email-Detection/
│
├── phishing_detector.ipynb
├── dataset.csv
└── README.md

---

## 🧠 How It Works

1. Dataset is loaded from CSV file
2. Email text is converted into numerical form using CountVectorizer
3. Data is split into training and testing sets
4. Model is trained using Multinomial Naive Bayes
5. Predictions are made on new emails
6. Accuracy and confusion matrix are generated

---

## ▶️ How to Run

1. Open Jupyter Notebook
2. Open `phishing_detector.ipynb`
3. Run all cells step-by-step

---

Example Output
Email: Click here to win money
Result: Phishing ❌
Accuracy: 85%
