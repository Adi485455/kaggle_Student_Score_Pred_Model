# Student Exam Score Prediction 🧠📊

This project is a machine learning solution for a Kaggle Playground regression competition focused on predicting student exam scores.

## 📌 Problem Statement
Given student-related features (demographics, academic data, etc.), the task is to predict the final exam score.

## 🛠️ Approach
- Data preprocessing and feature cleaning
- Native categorical feature handling using LightGBM
- Train–validation split for sanity checking
- K-Fold Cross-Validation for robust evaluation
- Early stopping using modern LightGBM callbacks
- Prediction averaging across folds

## 🚀 Model
- **Algorithm:** LightGBM Regressor
- **Metric:** RMSE
- **Key techniques:**
  - Pandas categorical dtype
  - Early stopping
  - Cross-validation

## 📈 Results
Achieved a competitive leaderboard score on Kaggle with stable and realistic predictions.

## 📂 Files
- `student_exam_score_lightgbm.ipynb` – Full training and evaluation notebook

## 🔗 Competition
Kaggle Playground Series – Student Exam Score Prediction

## 🧠 What I Learned
- Handling categorical features in LightGBM
- Debugging real-world ML errors
- Cross-validation and early stopping
- Building an end-to-end ML pipeline

---

**Author:** Aditya Jalindar Turkunde  
**Domain:** Machine Learning / Data Science
