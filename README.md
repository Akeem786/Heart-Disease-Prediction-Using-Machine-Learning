# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting heart disease using multiple machine learning classification algorithms.  
The objective is to determine whether a patient is likely to have heart disease based on medical and demographic features.

Multiple models were trained, evaluated, and compared to identify the best-performing algorithm.

---

## 📂 Dataset
- **Dataset Name:** Heart Disease Dataset (`heart.csv`)
- **Target Variable:** `HeartDisease`
  - `1` → Patient has heart disease
  - `0` → Patient does not have heart disease

### Key Features:
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Fasting Blood Sugar  
- Resting ECG  
- Maximum Heart Rate  
- Exercise-Induced Angina  
- ST Slope  

---

## ⚙️ Data Preprocessing
- Separated features (`X`) and target (`y`)
- Applied **One-Hot Encoding** for categorical variables
- Split the dataset into **Training (80%)** and **Testing (20%)**
- Applied **Feature Scaling** for Logistic Regression, SVM, and KNN

---

## 🤖 Machine Learning Models Implemented
The following classification models were implemented and compared:

- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest  
- Naive Bayes  
- Gradient Boosting  
- AdaBoost  
- Extra Trees Classifier  

---

## 📊 Model Evaluation
Each model was evaluated using the following metrics:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

A comparison table was created to rank models based on performance.

---

## 🏆 Best Performing Model
- **Extra Trees Classifier**
- Achieved approximately **91% accuracy**
- Provided the best balance of precision, recall, and F1-score

---

## 📈 Confusion Matrix Analysis
The confusion matrix of the selected model shows:
- High True Positives and True Negatives
- Low False Negatives, which is crucial in healthcare predictions

This indicates strong and reliable predictive performance.

---

## 🧠 Key Learnings
- Ensemble learning models outperform individual classifiers on structured medical data
- Recall is a critical metric for healthcare-related problems
- Comparing multiple models helps in selecting the most reliable solution

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  
- Seaborn  

---

## 🚀 How to Run the Project

1. Clone the repository
   ```bash
   git clone https://github.com/Akeem786/heart-disease-prediction.git
