# 🏦 Bank Marketing Decision Tree Classifier

## 📌 Overview

This project focuses on building a **Decision Tree Classifier** using a real-world dataset from a Portuguese bank's direct marketing campaign. The goal is to analyze customer information and predict whether a client will subscribe to a term deposit based on various socio-economic attributes and historical marketing interaction data.

---

## 🎯 Objectives

* Predict if a customer will subscribe to a term deposit (`y` = yes or no).
* Understand the most influential features affecting a customer's decision.
* Visualize the decision-making process using a Decision Tree.
* Practice data preprocessing, one-hot encoding, model training, and evaluation using scikit-learn.

---

## 🌟 Key Features

* Loads and processes the `bank-full.csv` dataset.
* Converts categorical features using **one-hot encoding**.
* Transforms the target variable `y` to binary for classification.
* Splits the dataset into training and test sets.
* Trains a **Decision Tree Classifier** (`sklearn.tree.DecisionTreeClassifier`).
* Evaluates the model using:

  * Accuracy Score
  * Classification Report
  * Confusion Matrix
* Visualizes the trained decision tree using `matplotlib`.

---

## 💻 Technologies Used

| Technology                     | Purpose                            |
| ------------------------------ | ---------------------------------- |
| **Python**                     | Programming language               |
| **Pandas**                     | Data loading and preprocessing     |
| **Matplotlib**                 | Visualization of the decision tree |
| **scikit-learn (sklearn)**     | Model building and evaluation      |
| **Jupyter Notebook / VS Code** | Development environment            |
