# Bagging and Random Forest Classification

## 📌 Overview
This project implements two **Ensemble Learning** algorithms, Bagging Classifier and Random Forest Classifier, using Python and Scikit-learn on the Iris dataset.

## 🧠 Algorithms Used

### 1. Bagging Classifier (Bootstrap Aggregating)

**Theory:**

Bagging is an Ensemble Learning technique that combines multiple models to improve prediction accuracy and reduce variance.

**Working:**
1. Creates multiple random samples from the training dataset using Bootstrap Sampling.
2. Trains a separate Decision Tree on each sample.
3. Combines predictions from all models using Majority Voting.
4. Produces the final classification result.

**Key Concepts:**
- Ensemble Learning
- Bootstrap Sampling
- Sampling with Replacement
- Decision Trees
- Majority Voting
- Variance Reduction

**Algorithm Workflow:**

`Training Data → Bootstrap Samples → Multiple Decision Trees → Majority Voting → Final Prediction`

![Bagging Algorithm](images/bagging.png)

---

### 2. Random Forest Classifier

**Theory:**

Random Forest is an Ensemble Learning algorithm that combines multiple Decision Trees to improve accuracy and reduce overfitting.

**Working:**
1. Creates multiple Bootstrap Samples from the training dataset.
2. Builds multiple Decision Trees using random subsets of features.
3. Each tree makes an independent prediction.
4. Combines predictions using Majority Voting.
5. Returns the final classification result.

**Key Concepts:**
- Ensemble Learning
- Bootstrap Sampling
- Random Feature Selection
- Decision Trees
- Majority Voting
- Variance Reduction
- Overfitting Prevention

**Algorithm Workflow:**

`Training Data → Bootstrap Samples → Random Feature Selection → Multiple Decision Trees → Majority Voting → Final Prediction`

![Random Forest Algorithm](images/random_forest.png)

---

## ⚙️ Implementation Steps

1. Import required libraries.
2. Load the Iris dataset.
3. Separate features (X) and target (Y).
4. Split data into training and testing sets (80:20).
5. Create Bagging and Random Forest classifiers.
6. Train models using `fit()`.
7. Predict results using `predict()`.
8. Evaluate performance using `accuracy_score()`.

## 🛠️ Technologies Used
- Python
- Scikit-learn
- Google Colab

## 📊 Evaluation Metric
**Accuracy Score:** Measures the percentage of correctly classified predictions.

## 🎯 Learning Outcomes
- Understanding Ensemble Learning techniques.
- Learning Bootstrap Sampling and Random Feature Selection.
- Understanding how multiple Decision Trees work together.
- Comparing Bagging and Random Forest classification.

## 🔑 Important Keywords
`Machine Learning` `Ensemble Learning` `Bagging` `Random Forest` `Decision Tree` `Bootstrap Sampling` `Majority Voting` `Classification` `Scikit-learn`