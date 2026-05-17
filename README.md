# 🏥 Healthcare Patient Risk Prediction

A machine learning project focused on predicting diabetes risk using patient health records and clinical attributes. The project applies data analysis, visualization, and classification models to identify patterns associated with diabetes risk.

---

## 📌 Overview

Early prediction of diabetes can help improve preventive healthcare and reduce long-term medical complications. This project analyzes healthcare data to predict whether a patient is likely to develop diabetes based on diagnostic measurements such as glucose level, BMI, insulin, and age.

The workflow includes:
- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature relationship analysis
- Machine learning model development
- Performance evaluation

---

## 📊 Dataset

The project uses the **Pima Indians Diabetes Dataset**, which contains medical diagnostic information collected from female patients.

### Dataset Information

| Attribute | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Triceps skin fold thickness |
| Insulin | 2-Hour serum insulin |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes inheritance likelihood |
| Age | Patient age |
| Outcome | Diabetes prediction (0 or 1) |

- Total Records: **768**
- Target Variable: **Outcome**

---

## 🧠 Project Workflow

### 1. Data Cleaning
- Handled missing and zero-valued entries
- Checked for null values and inconsistencies
- Prepared data for model training

### 2. Exploratory Data Analysis
- Distribution analysis of patient features
- Correlation analysis between medical attributes
- Visualization of diabetes patterns

### 3. Model Building
Implemented multiple classification models:
- Logistic Regression
- Random Forest Classifier

### 4. Model Evaluation
Models were evaluated using:
- Accuracy
- Confusion Matrix
- Precision & Recall
- Classification Report

---

## 📈 Key Insights

- Glucose level was the strongest predictor of diabetes
- Higher BMI and age showed increased diabetes risk
- The dataset showed class imbalance between diabetic and non-diabetic patients
- Random Forest captured non-linear relationships more effectively than Logistic Regression

---

## 🤖 Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 75% |
| Random Forest | 76% |

### Observation
Random Forest performed slightly better in identifying diabetic patients due to its ability to model complex feature interactions.

---

## 📷 Visualizations

The project includes:
- Correlation Heatmap
- Feature Distribution Plots
- Outcome Comparison Charts
- Model Evaluation Metrics

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📁 Project Structure

```bash
healthcare-risk-prediction/
│
├── data/
├── healthcare_risk_prediction.ipynb
├── requirements.txt
└── README.md
