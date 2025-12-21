# ❤️ Heart Disease Prediction Using Machine Learning

## 📌 Project Overview
This project focuses on predicting heart disease using multiple machine learning classification algorithms.  
The goal is to identify whether a patient is likely to have heart disease based on clinical and demographic features.

Several models were trained, evaluated, and compared to select the best-performing model using standard evaluation metrics.

---

## 📂 Dataset
- **Source:** Heart Disease Dataset (`heart.csv`)
- **Target Variable:** `HeartDisease`
  - `1` → Patient has heart disease
  - `0` → Patient does not have heart disease

### Key Features:
- Age  
- Sex  
- Chest Pain Type  
- Resting Blood Pressure  
- Cholesterol  
- Max Heart Rate  
- Exercise-Induced Angina  
- ST Slope  

---

## ⚙️ Data Preprocessing
- Separated features (`X`) and target (`y`)
- Applied **One-Hot Encoding** for categorical variables
- Performed **Train-Test Split (80% / 20%)**
- Applied **Feature Scaling** for distance-based models (Logistic Regression, SVM, KNN)

---

## 🤖 Machine Learning Models Implemented
The following classification models were trained and evaluated:

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

## 📊 Model Evaluation Metrics
Each model was evaluated using:
- Accuracy  
- Precision  
- Recall  
- F1-Score  

A comparison table was created to identify the best-performing model.

---

## 🏆 Best Model
- **Extra Trees Classifier**
- Achieved approximately **91% accuracy**
- Provided the best balance between precision, recall, and F1-score

---

## 📈 Confusion Matrix Analysis
The confusion matrix of the best model shows:
- High True Positives and True Negatives
- Low False Negatives, which is crucial in medical diagnosis

This indicates that the model is reliable for heart disease prediction.

---

## 🧠 Key Learnings
- Ensemble models outperform single classifiers on structured medical data
- Recall is a critical metric for healthcare-related prediction problems
- Proper preprocessing and model comparison significantly improve performance

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
   git clone https://github.com/your-username/heart-disease-prediction.git
