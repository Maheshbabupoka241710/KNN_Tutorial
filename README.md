#  KNN Wine Quality Classification – Tutorial

A student-friendly machine learning tutorial using the K-Nearest Neighbours (KNN) algorithm to classify wine quality (low / medium / high) from the WineQT dataset.

---

##  Project Overview

This project walks through an **end-to-end ML pipeline**:
from understanding KNN → exploring the data → preprocessing → modelling → tuning → visualising → comparing with Logistic Regression → reflecting on results.

---

##  Tutorial Flow (Stage-by-Stage – Crisp Summary)

### 1️⃣ Introduction  
Explain the intuition behind KNN: “look at who is closest and follow the majority”, with a simple diagram showing how neighbours decide the class.

### 2️⃣ Understanding KNN  
Break down how KNN predicts a label using k nearest neighbours, majority voting, and distance metrics (Euclidean, Manhattan, Minkowski).

### 3️⃣ Visual Overview  
Describe how different plots (class distribution, heatmap, boxplots, PCA, confusion matrices) help us see how KNN interacts with the wine data.

### 4️⃣ Exploratory Data Analysis (EDA)  
Check class balance, feature relationships, and key trends using plots like class distribution, correlation heatmap, and boxplots.

### 5️⃣ Data Preprocessing  
Clean the data, create quality labels (low/medium/high), scale features using StandardScaler, and perform a stratified train–test split.

### 6️⃣ Baseline Models  
Build a baseline KNN model and a baseline Logistic Regression model to understand initial performance and set a reference.

### 7️⃣ Hyperparameter Tuning  
Use GridSearchCV to search over k values, distance metrics, and weight types, optimising on F1-macro to handle class imbalance.

### 8️⃣ Model Visualisations  
Create PCA plots, F1 vs k curves, and confusion matrices for KNN and Logistic Regression to visually inspect performance and errors.

### 9️⃣ Model Comparison  
Compare KNN and Logistic Regression, explaining why Logistic Regression slightly outperforms KNN and what this says about the data (near-linear boundaries).

### 🔟 Discussion  
Summarise key insights: importance of scaling, influence of alcohol and volatile acidity, impact of class imbalance, and why metrics like F1-macro matter.

### 1️⃣1️⃣ Limitations & Future Work  
Note dataset size and imbalance, KNN’s speed on large data, and suggest improvements like SMOTE, advanced models, weighted KNN, and UMAP.

### 1️⃣2️⃣ Conclusion  
Wrap up by stating that KNN is simple and interpretable, Logistic Regression is slightly stronger here, and the pipeline follows good ML practice from start to finish.

---

## ▶️ How to Run

1. Clone the repo:
```bash
git clone https://github.com/your-username/KNN-Wine-Quality-Project.git
cd KNN-Wine-Quality-Project

## Project Structure

KNN-Wine-Quality-Project/
│
├── KNN_Tutorial.ipynb        # Main tutorial notebook (code + explanations)
├── WineQT.csv                # Wine quality dataset (from Kaggle)
├── README.md                 # This documentation
├── requirements.txt          # Python dependencies
│
└── images/                   # (Optional) Saved plots for the report
    ├── knn_workflow.png
    ├── class_distribution.png
    ├── correlation_heatmap.png
    ├── boxplot_alcohol.png
    ├── boxplot_residual_sugar.png
    ├── boxplot_volatile_acidity.png
    ├── pca_projection.png
    ├── f1_vs_k_curve.png
    ├── confusion_knn.png
    └── confusion_logreg.png


