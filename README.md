# Water-Quality
# 💧 Water Quality Prediction Project

This project aims to predict whether water is **safe for consumption** using machine learning and deep learning models. The dataset includes chemical and microbial features, and the task is to build a binary classification model that outputs `is_safe` (1 for safe, 0 for unsafe).

## 📌 Problem Statement

Predict the safety of water based on 20 features representing various ingredients such as **lead**, **bacteria**, **silver**, and other chemical components. The target variable is `"is_safe"`.

## 📊 Dataset Overview

- **Original size**: 7,996 rows  
- **After up-sampling**: 14,168 rows  
- **Target**: `is_safe` (binary classification)

## ⚙️ Data Preprocessing

- Checked and removed **null values**
- Verified there were **no duplicate rows**
- **Up-sampled** the minority class to address class imbalance

## 📈 Data Visualization

- **Heatmap** to assess feature correlations  
- **Histograms** to analyze feature distributions

## 🤖 Models Used

### 📦 Pretrained / Traditional ML Models

- **XGBoost**: Achieved best performance among ML models (Accuracy: **99%**)
- **Random Forest Classifier**
- **Support Vector Machine (SVM)** with RBF kernel

### 🔬 Deep Learning Models

- **Feedforward Neural Network (FNN)**: Built from scratch  
- **Modified FNN with Dropout Layers**: Prevented overfitting, achieved Accuracy: **95%**

## 🏆 Results Summary

| Model                  | Accuracy |
|------------------------|----------|
| XGBoost (ML)           | 0.99     |
| Modified FNN (DL)      | 0.95     |

## ✅ Conclusion

- **XGBoost** was the top-performing model among traditional ML methods.
- **Modified FNN** with dropout showed the best results among neural network models, effectively handling potential overfitting.

## 🛠️ Tools & Technologies

- **Python**
- **pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **scikit-learn**, **XGBoost**
- **TensorFlow** or **PyTorch** (based on your DL framework)

---

Feel free to ⭐ this repo if you found it helpful or want to contribute!
