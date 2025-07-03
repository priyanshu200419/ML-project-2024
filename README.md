# 🎯 Machine Learning Project: Gender and Age Detection from Voice

This project uses machine learning to predict **gender** and **age group** from a person's **voice features**. It applies multiple classification algorithms, evaluates their performance, and compares them using accuracy and confusion matrices.

## 🧠 Project Overview

The aim is to analyze voice recordings and identify patterns that correlate with gender and age (child/adult). It is a classic **classification problem**, and the following machine learning models are implemented and compared:

- Logistic Regression
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)

## 🛠️ Technologies Used

- Python 3
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib / Seaborn
- scikit-learn

## 📂 Dataset

- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/biometric+voice+dataset)
- **Attributes:** 20+ voice features like mean frequency, max frequency, jitter, shimmer, etc.
- **Target Variables:** `label` (gender) and `age` (child or adult)

## 📊 Results

Each model was trained and evaluated using classification metrics like accuracy and confusion matrix. Here’s a brief summary:

| Model               | Accuracy (%) |
|--------------------|--------------|
| Logistic Regression| 91%          |
| Decision Tree      | 94%          |
| Random Forest      | 96%          |
| SVM                | 93%          |
| KNN                | 88%          |

> Random Forest performed the best among all tested models.

## 🚀 How to Run

1. Clone the repo:

   ```bash
   git clone https://github.com/your-username/voice-gender-age-detection.git
   cd voice-gender-age-detection
