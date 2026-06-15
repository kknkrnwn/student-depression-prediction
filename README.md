# 🎓 Student Depression Prediction using Machine Learning

## 📌 Overview

This project aims to predict student depression based on academic, lifestyle, and mental health factors using Machine Learning techniques.

The study follows the **Knowledge Discovery in Databases (KDD)** methodology and compares the performance of three classification algorithms:

* 🌳 Decision Tree
* 🌲 Random Forest
* 🚀 XGBoost

The objective is to identify the most effective model for predicting depression among students.

---

## 📂 Dataset

Dataset: **Depression Student Dataset**

### Features

| Feature                              | Description                  |
| ------------------------------------ | ---------------------------- |
| Gender                               | Student gender               |
| Age                                  | Student age                  |
| Academic Pressure                    | Academic workload level      |
| Study Satisfaction                   | Satisfaction with studies    |
| Sleep Duration                       | Average sleep duration       |
| Dietary Habits                       | Eating habits                |
| Have you ever had suicidal thoughts? | History of suicidal thoughts |
| Study Hours                          | Daily study hours            |
| Financial Stress                     | Financial stress level       |
| Family History of Mental Illness     | Family mental health history |

### Target

| Variable   | Description |
| ---------- | ----------- |
| Depression | Yes / No    |

---

## 🔍 Methodology

This project follows the **Knowledge Discovery in Databases (KDD)** process:

### 1️⃣ Data Selection

* Selecting relevant features and target variable.

### 2️⃣ Data Preprocessing

* Missing Value Handling
* Duplicate Data Removal
* Outlier Detection using IQR Method

### 3️⃣ Data Transformation

* Label Encoding
* Data Preparation for Machine Learning

### 4️⃣ Exploratory Data Analysis (EDA)

* Target Distribution
* Age Distribution
* Academic Pressure Analysis
* Financial Stress Analysis
* Correlation Matrix

### 5️⃣ Data Mining

Implementation of:

* Decision Tree
* Random Forest
* XGBoost

### 6️⃣ Evaluation

Performance metrics:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

### 7️⃣ Feature Importance Analysis

Using Random Forest Feature Importance.

---

## 🛠️ Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* XGBoost
* Google Colab
* Jupyter Notebook

---

## 📁 Repository Structure

```text
student-depression-prediction/
│
├── dataset/
│   └── Depression Student Dataset.csv
│
├── notebooks/
│   └── Student_Depression_Prediction.ipynb
│
├── images/
│   ├── target_distribution.png
│   ├── age_distribution.png
│   ├── academic_pressure.png
│   ├── financial_stress.png
│   ├── correlation_matrix.png
│   ├── confusion_matrix_dt.png
│   ├── confusion_matrix_rf.png
│   ├── confusion_matrix_xgb.png
│   ├── model_comparison.png
│   └── feature_importance.png
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Visualizations

### Target Distribution

<img width="650" alt="target_distribution" src="https://github.com/user-attachments/assets/17a87a78-c7a7-4e05-a4f7-6a90bed191ff" />

### Correlation Matrix

<img width="650" alt="correlation_matrix" src="https://github.com/user-attachments/assets/beb14ba6-4dad-4d78-9cb3-152826baea2f" />

### Model Comparison

<img width="650" alt="model_comparison" src="https://github.com/user-attachments/assets/d88b31f7-fddd-4677-bfaf-1a23190fc896" />

### Feature Importance

<img width="650" alt="feature_importance" src="https://github.com/user-attachments/assets/fc816b00-0683-4e60-ab08-8adfdacb1006" />

---

## 🚀 Installation

Clone repository:

```bash
git clone https://github.com/kknkrnwn/student-depression-prediction.git
```

Move into project folder:

```bash
cd student-depression-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook:

```bash
jupyter notebook
```

---

## 📈 Results

The models are evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score

The best-performing model is selected based on the highest classification performance.

---
