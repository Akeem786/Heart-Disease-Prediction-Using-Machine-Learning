# ❤️ Heart Disease Prediction Using Machine Learning

![Banner](https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a0a0a&height=200&section=header&text=Heart%20Disease%20Prediction&fontSize=36&fontColor=ff6b6b&animation=twinkling&fontAlignY=35&desc=Machine%20Learning%20Classification%20|%2091%25%20Accuracy&descAlignY=55&descColor=ffa5a5)

<p align="center">
  <img src="https://img.shields.io/badge/Accuracy-91%25-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Model-Extra%20Trees%20Classifier-red?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Status-Complete-brightgreen?style=for-the-badge" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge" />
</p>

---

## 📋 About This Project

This project focuses on predicting heart disease using multiple **Machine Learning classification algorithms**. The objective is to determine whether a patient is likely to have heart disease based on medical and demographic features.

Multiple models were trained, evaluated, and compared to identify the best-performing algorithm — achieving approximately **91% accuracy** using the **Extra Trees Classifier**.

---

## 📂 Dataset

- **Dataset:** Heart Disease Dataset (`heart.csv`)
- **Target Variable:** `HeartDisease`

| Value | Meaning |
|---|---|
| `1` | Patient has heart disease |
| `0` | Patient does not have heart disease |

### Key Features:

| Feature | Description |
|---|---|
| Age | Patient age |
| Sex | Gender |
| Chest Pain Type | Type of chest pain |
| Resting Blood Pressure | Blood pressure at rest |
| Cholesterol | Serum cholesterol level |
| Fasting Blood Sugar | Blood sugar > 120 mg/dl |
| Resting ECG | Electrocardiogram results |
| Maximum Heart Rate | Max heart rate achieved |
| Exercise-Induced Angina | Angina induced by exercise |
| ST Slope | Slope of peak exercise ST segment |

---

## ⚙️ Data Preprocessing

```
✔ Separated features (X) and target (y)
✔ Applied One-Hot Encoding for categorical variables
✔ Split dataset — Training (80%) and Testing (20%)
✔ Applied Feature Scaling for Logistic Regression, SVM, and KNN
```

---

## 🤖 Machine Learning Models Implemented

| # | Model |
|---|---|
| 1 | Logistic Regression |
| 2 | K-Nearest Neighbors (KNN) |
| 3 | Support Vector Machine (SVM) |
| 4 | Decision Tree |
| 5 | Random Forest |
| 6 | Naive Bayes |
| 7 | Gradient Boosting |
| 8 | AdaBoost |
| 9 | **Extra Trees Classifier** ⭐ |

---

## 📊 Model Evaluation

Each model was evaluated using:

<p align="center">
  <img src="https://img.shields.io/badge/Accuracy-✓-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Precision-✓-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/Recall-✓-blue?style=flat-square" />
  <img src="https://img.shields.io/badge/F1--Score-✓-blue?style=flat-square" />
</p>

A comparison table was created to rank all models based on performance metrics.

---

## 🏆 Best Performing Model

<p align="center">
  <img src="https://img.shields.io/badge/🏆%20Extra%20Trees%20Classifier-~91%25%20Accuracy-gold?style=for-the-badge" />
</p>

```
✔ Best balance of Precision, Recall, and F1-Score
✔ Ensemble learning — combines multiple decision trees
✔ Robust against overfitting
✔ Ideal for structured medical data
```

---

## 📈 Confusion Matrix Analysis

```
✔ High True Positives  — correctly identified heart disease patients
✔ High True Negatives  — correctly identified healthy patients
✔ Low False Negatives  — critical in healthcare predictions
✔ Strong and reliable predictive performance
```

> ⚠️ **Note:** In healthcare, **Recall** is the most critical metric — minimizing False Negatives (missed diagnoses) is more important than overall accuracy.

---

## 🧠 Key Learnings

- ✅ Ensemble models (Extra Trees, Random Forest) outperform individual classifiers on structured medical data
- ✅ **Recall** is the most important metric for healthcare problems — missing a diagnosis is more dangerous than a false alarm
- ✅ Comparing multiple models helps select the most reliable solution
- ✅ Feature scaling is essential for distance-based algorithms (KNN, SVM)
- ✅ One-Hot Encoding is necessary for categorical medical features

---

## 🛠️ Technologies Used

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" />
  <img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" />
  <img src="https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Seaborn-4c72b0?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" />
</p>

---

## 🚀 How to Run

### Step 1: Clone Repository
```bash
git clone https://github.com/Akeem786/Heart-Disease-Prediction-Using-Machine-Learning.git
cd Heart-Disease-Prediction-Using-Machine-Learning
```

### Step 2: Install Dependencies
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

### Step 3: Run the Notebook
```bash
jupyter notebook
```
Open `heart_disease_prediction.ipynb` and run all cells.

---

## 👤 Author

**Akeem Ali**

<p>
  <a href="https://github.com/Akeem786">
    <img src="https://img.shields.io/badge/GitHub-Akeem786-181717?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  <a href="https://linkedin.com/in/akeem-ali-ba8178323">
    <img src="https://img.shields.io/badge/LinkedIn-Akeem%20Ali-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://leetcode.com/u/Akeem051/">
    <img src="https://img.shields.io/badge/LeetCode-Akeem051-FFA116?style=for-the-badge&logo=leetcode&logoColor=white" />
  </a>
</p>

![Footer](https://capsule-render.vercel.app/api?type=waving&color=0:1a0a0a,100:0d1117&height=120&section=footer&fontColor=ff6b6b)
