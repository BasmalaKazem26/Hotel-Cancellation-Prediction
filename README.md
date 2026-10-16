# Hotel Booking Cancellation Prediction 🏨

A machine learning project built with Python and XGBoost to predict whether a hotel booking will be cancelled at the moment of reservation.

## 🚀 Project Overview
- **Objective:** Build a classification model to predict booking cancellations, helping hotels optimize occupancy and manage revenue effectively.
- **Algorithm Used:** XGBoost Classifier[cite: 3].
- **Model Performance:** Achieved an overall accuracy of **85%** with a solid classification report[cite: 3].

## 🛠️ Tech Stack & Libraries
- **Python**[cite: 1]
- **Pandas & NumPy** (Data Manipulation & Preprocessing)[cite: 1, 3]
- **Scikit-Learn** (Data Splitting, Evaluation Metrics)[cite: 1, 3]
- **XGBoost** (Machine Learning Model)[cite: 1, 3]
- **Jupyter Notebook** (Development Environment)

## 📊 Pipeline & Steps
1. **Data Loading & Inspection:** Loaded the dataset (`data.csv`) and analyzed its shape and features[cite: 1, 3].
2. **Data Cleaning & Preprocessing:** Handled missing values, dropped unnecessary identifiers (`company_id`, `agent_id`)[cite: 3].
3. **Feature Engineering:** Applied One-Hot Encoding (`pd.get_dummies`) on categorical features[cite: 3].
4. **Data Splitting:** Split the dataset into training and testing sets (70/30 split) using `train_test_split`[cite: 3].
5. **Model Training & Evaluation:** Trained the `XGBoostClassifier` and evaluated it using Accuracy Score and Classification Report (`precision`, `recall`, `f1-score`)[cite: 3].

---
*Created as part of a Data Science & Machine Learning Portfolio.*
