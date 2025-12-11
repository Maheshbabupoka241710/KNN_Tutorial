# KNN Wine Quality Classification – Tutorial

A student-friendly machine learning tutorial using the K-Nearest Neighbours (KNN) algorithm to classify wine quality (low / medium / high) from the WineQT dataset.

---

## Project Overview

This project demonstrates a complete end-to-end machine learning pipeline:
understanding how KNN works → exploring the dataset → preprocessing data → building models → tuning hyperparameters → visualising results → comparing with Logistic Regression → summarising findings.

The goal is to present a clear, easy-to-understand tutorial suitable for students and beginners.

---

## Tutorial Flow (Stage-by-Stage Summary)

### 1. Introduction  
Explains the intuition behind KNN: “look at who is closest and follow the majority”, supported by a simple classification workflow diagram.

### 2. Understanding KNN  
Describes how KNN predicts labels using k nearest neighbours, majority voting, and distance metrics such as Euclidean, Manhattan, and Minkowski.

### 3. Visual Overview  
Introduces all visualisations used in the tutorial, including class distribution, correlation heatmap, boxplots, PCA projection, F1 vs k curve, and confusion matrices.

### 4. Exploratory Data Analysis (EDA)  
Examines class balance, correlations, and feature patterns using multiple plots to understand key characteristics of the wine data.

### 5. Data Preprocessing  
Cleans the dataset, converts numeric quality scores into class labels (low, medium, high), scales features using StandardScaler, and performs a stratified train–test split.

### 6. Baseline Models  
Builds initial baseline models using KNN and Logistic Regression to establish reference performance levels.

### 7. Hyperparameter Tuning  
Uses GridSearchCV to optimise over k values, distance metrics, and weighting strategies, evaluating each model using F1-macro due to class imbalance.

### 8. Model Visualisations  
Generates PCA plots, tuning curves, and confusion matrices to visually analyse how each model performs and where errors occur.

### 9. Model Comparison  
Compares KNN and Logistic Regression, explaining why Logistic Regression performs slightly better and how this reflects near-linear class boundaries in the dataset.

### 10. Discussion  
Summarises key insights: importance of scaling, influence of specific features (alcohol and volatile acidity), handling class imbalance, and reliability of F1-macro.

### 11. Limitations and Future Work  
Highlights dataset size, imbalance, and KNN’s computational cost; proposes improvements such as SMOTE, weighted KNN, advanced models, and dimensionality reduction.

### 12. Conclusion  
Concludes that KNN is simple and interpretable, Logistic Regression is slightly more suitable for this dataset, and the overall pipeline demonstrates strong machine learning practice.

---

## Project Structure

KNN-Wine-Quality-Project/
│
├── KNN_Tutorial.ipynb # Main tutorial notebook (code + explanations)
├── WineQT.csv # Wine quality dataset (from Kaggle)
├── README.md # This documentation
├── requirements.txt # Python dependencies
│
└── images/ # (Optional) Saved plots for the report
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


---

If you'd like, I can also generate:

- A clean **requirements.txt**  
- A **license file**  
- A **short GitHub project description** (appears on top of the repo)  
- A **badge section** (Python version, framework versions, etc.)

Just tell me what you want next.
