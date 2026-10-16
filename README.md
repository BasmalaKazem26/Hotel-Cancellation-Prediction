# Hotel Booking Cancellation Prediction 🏨

A machine learning project built with Python and XGBoost to predict whether a hotel booking will be cancelled at the moment of reservation.

## Project Overview
- **Objective:** Build a classification model to predict booking cancellations, helping hotels optimize occupancy and manage revenue effectively.
- **Algorithm Used:** XGBoost Classifier.
- **Model Performance:** Achieved an overall accuracy of **85%** with a solid classification report.

## Tech Stack & Libraries
- **Python**
- **Pandas & NumPy** (Data Manipulation & Preprocessing)
- **Scikit-Learn** (Data Splitting, Evaluation Metrics)
- **XGBoost** (Machine Learning Model)
- **Jupyter Notebook** (Development Environment)

 ## Pipeline & Steps
1. **Data Loading & Inspection:** Loaded the dataset (`data.csv`) and analyzed its shape and features.
2. **Data Cleaning & Preprocessing:** Handled missing values, dropped unnecessary identifiers (`company_id`, `agent_id`).
3. **Feature Engineering:** Applied One-Hot Encoding (`pd.get_dummies`) on categorical features.
4. **Data Splitting:** Split the dataset into training and testing sets (70/30 split) using `train_test_split`.
5. **Model Training & Evaluation:** Trained the `XGBoostClassifier` and evaluated it using Accuracy Score and Classification Report (`precision`, `recall`, `f1-score`).


