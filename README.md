# Predicting Patient Dropout from a Long-Term Health Treatment Program

This project aims to predict patient dropout from a long-term healthcare treatment program using logistic regression. By analyzing anonymized patient data, the model identifies at-risk patients and highlights key factors contributing to dropout, enabling healthcare providers to intervene proactively.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Objectives](#objectives)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Evaluation](#model-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

---

## 🎯 Project Overview
The healthcare dataset includes anonymized patient interactions, such as activity logs, goal progress, and online engagement metrics. Using logistic regression, this project:
- Predicts the likelihood of a patient discontinuing treatment.
- Identifies critical factors influencing dropout decisions.
- Provides actionable insights to improve patient retention strategies.

---

## 🚀 Objectives
1. **Predict Dropout Likelihood**: Develop a logistic regression model to classify patients as "at-risk" or "retained."
2. **Identify Key Factors**: Determine which features (e.g., missed appointments, low engagement) most strongly correlate with dropout.
3. **Evaluate Model Performance**: Assess accuracy, precision, recall, and AUC-ROC to ensure reliability.

---

## 📁 Dataset
The dataset includes anonymized features such as:
- Patient demographics
- Treatment activity logs
- Progress review metrics
- Online interaction frequency
- Historical dropout records (target variable)

**Note**: The dataset is not included in this repository due to privacy constraints.

---

## 🔧 Installation
### Dependencies
- Python 3.8+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### Setup
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

---

## 🖥️ Usage
1. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Normalize/standardize features.
2. **Exploratory Data Analysis (EDA)**:
   - Visualize correlations, class distributions, and feature relationships.
3. **Model Training**:
   - Split data into training and testing sets.
   - Train a logistic regression model.
4. **Evaluation**:
   - Generate metrics (accuracy, precision, recall, F1-score, AUC-ROC).
   - Plot confusion matrices and ROC curves.

---

## 📊 Model Evaluation
The model is evaluated using:
- **Accuracy**: Overall correctness of predictions.
- **Precision**: Proportion of true positives among predicted positives.
- **Recall**: Proportion of actual positives correctly identified.
- **F1-Score**: Harmonic mean of precision and recall.
- **ROC-AUC**: Model’s ability to distinguish between classes.

---

## 📌 Results
### Key Factors Influencing Dropout
1. **Missed Appointments**: Strongest predictor of dropout.
2. **Low Engagement**: Patients with fewer online interactions.
3. **Progress Stagnation**: Minimal improvement in treatment goals.

### Visualization
- **Confusion Matrix**: Highlights true/false positives and negatives.
- **Feature Importance**: Coefficients from the logistic regression model.


---

## 📜 License
This project is under the MIT License. See [LICENSE](LICENSE) for details.

---
