# 🧠 Diabetes Diagnosis Prediction using Machine Learning

This project explores the application of various machine learning models to classify patients into **diabetic**, **pre-diabetic**, or **healthy**, based on clinical data.

## 📊 Dataset

We use a dataset consisting of **21 clinical attributes** per patient, including biometric measurements, lab results, and lifestyle factors.

- Total samples: [X] patients
- Classes:
  - 0: Healthy
  - 1: Pre-diabetic
  - 2: Diabetic

*(Dataset source: (https://archive.ics.uci.edu/dataset/891/cdc+diabetes+health+indicators))*

## 🎯 Objective

The goal is to **build a predictive model** that can accurately classify a patient's diabetic condition using the provided attributes. This can be used as a support tool for early detection and prevention of diabetes.

## 🔧 Technologies Used

- Python
- pandas, NumPy
- scikit-learn
- matplotlib, seaborn
- Jupyter Notebooks

## 🧠 Machine Learning Methods

### 🔬 Supervised Learning:
- Logistic Regression
- Random Forest
- Gradient Boosting
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- **Multilayer Perceptron (MLP / Neural Network)**

### 🧪 Feature Selection:
- Recursive Feature Elimination (RFE)
- Feature importance from tree-based models
- Correlation analysis

### 🧭 Unsupervised Learning:
- **Hierarchical Clustering**
- **Unsupervised KNN (distance-based grouping)**

## 📈 Evaluation Metrics

- Accuracy
- F1-score
- Confusion matrix
- ROC and AUC curves
- Silhouette score (for clustering)
- 
## 📈 Results
- Detailed results and visualizations can be found in the notebook.

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/enriquebravo22/diabetes-ml.git
   cd diabetes-ml
