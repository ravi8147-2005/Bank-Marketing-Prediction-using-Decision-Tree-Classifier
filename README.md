# 🧠 Customer Purchase Prediction using Decision Tree Classifier

This project builds a **Decision Tree Classifier** to predict whether a customer will subscribe to a **bank term deposit** based on their **demographic** and **behavioral data**. The model is trained using the real-world **Bank Marketing dataset** from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Bank+Marketing).

---

## 📁 Dataset Overview

- **Source**: UCI Machine Learning Repository
- **File Used**: `bank-additional-full.csv`
- **Records**: 41,188
- **Features**: 20 input features + 1 target
- **Target Variable**: `y` — whether the customer subscribed to a term deposit (`yes` or `no`)

### 🔑 Key Features Used

- **Demographic Data**: Age, job, marital status, education
- **Behavioral Data**: Housing and personal loans, campaign contacts
- **Communication Info**: Last contact method, day, and month
- **Economic Indicators**: Employment variation, consumer confidence index, euribor rate, etc.

> ⚠️ Note: `duration` column was excluded during training to avoid data leakage.

---

## 🎯 Project Objective

> To train and evaluate a Decision Tree model that can **predict client subscription outcomes** using clean, interpretable machine learning techniques.

---

## 📊 Model Pipeline

1. Load and inspect dataset
2. Data preprocessing
   - Drop `duration` column
   - Encode categorical variables using `LabelEncoder`
3. Split dataset into training and test sets
4. Train a `DecisionTreeClassifier` using scikit-learn
5. Evaluate model using accuracy, confusion matrix, and classification report
6. Visualize the decision tree structure

---

✅ Output
📈 Trained Decision Tree model

📉 Accuracy and classification metrics

🌳 Visualized decision tree (interpretable model)

📄 Citation
Moro, S., Cortez, P., & Rita, P. (2014). A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems. DOI
---

📁 customer-purchase-decision-tree/
├── data/
│   └── bank-additional-full.csv
├── decision_tree_classifier.ipynb
├── decision_tree_classifier.py
├── requirements.txt
└── README.md

