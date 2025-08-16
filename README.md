# Random Forest with Bagging on Iris Dataset

This project demonstrates the application of **Random Forest Classifier** using **Bagging** on the famous **Iris dataset**.  
The goal is to understand how ensemble learning improves classification accuracy and reduces overfitting compared to a single decision tree.

---

## 📌 Objectives
- Apply Random Forest using bagging on a classification dataset.
- Reinforce concepts of ensemble methods through coding and interpretation.
- Explore data visually and evaluate model performance.

---

## 📂 Sections Covered

### Section A – Data Preparation
- Load dataset using Pandas
- Explore dataset (shape, column names, data types)
- Handle missing values & duplicates
- Encode target variable using LabelEncoder

### Section B – Exploratory Data Analysis (EDA)
- Pairplot to observe class separability
- Boxplots for each feature by species
- Countplot for class distribution

### Section C – Model Building
- Train-test split (80-20)
- Train a Random Forest Classifier (default params)
- Evaluate using:
  - Accuracy Score
  - Confusion Matrix
  - Classification Report

### Section D – Visualization
- Plot **feature importances**
- Visualize one decision tree (plot_tree or export_text)

### Section E – Tuning
- Experiment with:
  - `n_estimators`
  - `max_depth`
- Analyze effect on accuracy & overfitting

---

## 📊 Results
- Achieved **100% accuracy** on the Iris test set across multiple hyperparameter settings.
- Feature importance showed **Petal Length** and **Petal Width** as the most influential features.
- Even shallow trees (max_depth=3) performed perfectly due to clear class separability.

---

## 🚀 How to Run
Clone the repository:
   ```bash
https://github.com/HastiGohel/random-forest-bagging-iris.git
