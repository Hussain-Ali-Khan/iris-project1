# 🌸 Iris Dataset Analysis and Classification

This project performs **exploratory data analysis (EDA)** on the classic **Iris dataset** and trains multiple **machine learning models** to classify iris flower species based on their physical measurements.

---

## 📋 Table of Contents
1. [Introduction](#introduction)
2. [Dataset Loading and Preparation](#dataset-loading-and-preparation)
3. [Exploratory Data Analysis](#exploratory-data-analysis)
4. [Model Training](#model-training)
5. [Model Evaluation](#model-evaluation)
6. [Technologies Used](#technologies-used)
7. [How to Run](#how-to-run)
8. [Results](#results)
9. [License](#license)

---

## 🌱 Introduction
The **Iris dataset** is one of the most well-known datasets in the field of machine learning.  
The goal of this project is to **classify iris flowers into three species** — *Setosa*, *Versicolor*, and *Virginica* — using four key features:

- Sepal Length  
- Sepal Width  
- Petal Length  
- Petal Width  

This notebook demonstrates a **complete ML workflow**, from data loading and visualization to model training and evaluation.

---

## 📊 Dataset Loading and Preparation
The dataset is loaded using the `sklearn.datasets.load_iris()` function and converted into a **pandas DataFrame** for easy manipulation.  
A target column (`species`) is added, mapping each flower’s numeric label to its corresponding class name.

Steps:
1. Load dataset using `scikit-learn`
2. Convert to DataFrame
3. Add target labels
4. Prepare features (`X`) and target (`y`)

---

## 🔍 Exploratory Data Analysis
To understand the dataset better, several analyses and visualizations were performed:

- Summary statistics using `pandas.describe()`
- Histograms for each feature to view their distributions
- Scatter plots (e.g., sepal length vs. petal length)
- Correlation analysis between features

These steps help in identifying patterns, separability between classes, and potential feature importance.

---

## 🧠 Model Training
The dataset is split into **training and testing sets** (typically 80/20).  
Feature scaling is applied using `StandardScaler` to normalize the data.  
Three classification models are trained and compared:

1. **Support Vector Classifier (SVC)**  
2. **Random Forest Classifier**  
3. **Logistic Regression**

Each model is trained on the scaled training data and later tested for performance.

---

## 📈 Model Evaluation
Models are evaluated using multiple metrics:

- **Confusion Matrix**
- **Classification Report** (Precision, Recall, F1-Score)
- **Accuracy Score**

Confusion matrices are visualized using **heatmaps** for clarity.  
Performance metrics help determine which model best distinguishes between the iris species.

---

## 🧰 Technologies Used
- Python 3.x  
- NumPy  
- Pandas  
- Matplotlib / Seaborn  
- Scikit-learn (sklearn)  

---

## ⚙️ How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/iris-classification.git
   cd iris-classification
