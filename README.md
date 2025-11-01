### Heart Disease Predictor

## Overview
This project aims to predict the likelihood of a heart attack based on patient health data using machine learning models.  
The notebook explores data preprocessing, model training, evaluation, and performance comparison using **F1-scores** and **confusion matrices**.  

Three different classification algorithms were evaluated:
- **Logistic Regression**  
- **Random Forest Classifier**  
- **XGBoost Classifier**

The project provides a hands-on example of comparing model performance for a healthcare-related predictive task.

---

## Dataset
The dataset from Kaggle (https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease) contains various **health indicators** such as GeneralHealth, PhysicalHealthDays, MentalHealthDays, LastCheckupTime, PhysicalActivities, SleepHours and other relevant features.  
These features were used to predict whether a patient is likely to experience a **heart attack** (binary classification problem).

---

## Data Preprocessing
The preprocessing pipeline involved:
- Handling missing or inconsistent data  
- Converting categorical features into numerical form  
- Splitting the dataset into **training** and **testing** sets  

> **Note:** Feature scaling was **not applied** due to time constraints.  
Applying scaling or normalization (e.g., `StandardScaler`) would likely improve the performance of certain models — particularly **Logistic Regression**.

---

## Models Trained
Three classification models were trained and evaluated:

| Model | Description |
|--------|--------------|
| **Logistic Regression** | A linear model that predicts the probability of heart attack based on weighted features. |
| **Random Forest Classifier** | An ensemble of decision trees that captures non-linear relationships effectively. |
| **XGBoost Classifier** | A gradient boosting model optimized for speed and performance. |

Each model was evaluated using the **F1-score**, a metric that balances precision and recall.

---

## Evaluation & Results

### Metrics Used
- **F1 Score** — measures the balance between precision and recall.  
- **Confusion Matrix** — visualizes true positives, false positives, false negatives, and true negatives.

### Model Comparison
A bar chart was created to visualize and compare the **F1-scores** of the three models.

<img width="691" height="470" alt="image" src="https://github.com/user-attachments/assets/20529d93-224d-4923-8f0c-d7788c1cd2de" />
