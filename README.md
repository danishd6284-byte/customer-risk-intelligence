# 🛒 SmartKart Churn Prediction

### Predicting Customer Churn Using Machine Learning

SmartKart Churn Prediction is a Machine Learning project designed to identify customers who are likely to leave the business.

The project demonstrates a complete ML workflow, starting with a messy customer dataset and ending with **churn predictions and customer risk analysis**.

---

## 🔎 Problem Statement

Customer churn can negatively affect a company's revenue and long-term growth.

SmartKart wants to identify **customers who are at risk of leaving** so that the retention team can take action before they churn.

### Objective

> Build a Machine Learning model that predicts whether a customer is likely to churn.

---

## 🤖 Machine Learning Model

**Algorithm:** Logistic Regression

Logistic Regression is used because the project involves a **binary classification problem**:

| Value | Meaning                 |
| ----- | ----------------------- |
| `0`   | Customer will not churn |
| `1`   | Customer will churn     |

---

## 📂 Dataset

The project uses:

`SmartKart_dirty_100_rows.csv`

The dataset contains **100 customer records** and intentionally includes real-world data quality problems such as:

* Missing values
* Duplicate records
* Invalid entries
* Outliers

The main customer variables include:

* Customer ID
* Age
* Monthly Spend
* Complaints
* Churn

---

## 🔄 Project Workflow

The project follows a **15-step Machine Learning pipeline**:

```text
Data Collection
      ↓
Data Understanding
      ↓
Data Cleaning
      ↓
Outlier Detection & Treatment
      ↓
Feature Selection
      ↓
Target Variable Definition
      ↓
Target Encoding
      ↓
Train-Test Split
      ↓
Feature Standardisation
      ↓
Model Building
      ↓
Model Training
      ↓
Prediction
      ↓
Model Evaluation
      ↓
Model Interpretation
      ↓
Final Output
```

---

## 🧹 Data Preprocessing

Before training the model, the data is prepared by:

* Checking the dataset structure
* Identifying missing values
* Removing duplicate records
* Handling invalid values
* Treating extreme values
* Selecting relevant features
* Standardising numerical variables

This ensures that the model receives cleaner and more useful data.

---

## 📊 Features Used

The model focuses on customer attributes that can help explain churn:

```text
Age
Monthly_Spend
Complaints
```

`Customer_ID` is treated as an identifier rather than a predictive feature.

---

## 🧪 Model Training

The cleaned dataset is divided into:

```text
80% → Training Data
20% → Testing Data
```

The numerical features are standardised using **StandardScaler** before being passed to the Logistic Regression model.

---

## 📈 Model Evaluation

The model performance is evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

These metrics help understand how effectively the model identifies customers who may churn.

---

## 💡 Business Insights

The project is not only about building a model — it also connects Machine Learning with business decisions.

### 💬 Customer Complaints

A higher number of complaints can indicate an increased risk of customer churn.

**Business Action:**
SmartKart can focus on improving complaint resolution and customer support.

### 💰 Monthly Spending

Customer spending is also considered when analysing churn risk.

**Business Action:**
SmartKart can identify valuable customers and develop personalised retention strategies.

---

## 🎯 Churn Risk Prediction

The model generates a **churn probability** for customers.

This allows SmartKart to rank customers according to their risk level.

For example:

```text
Customer A → 91% Churn Probability
Customer B → 68% Churn Probability
Customer C → 22% Churn Probability
```

The retention team can prioritise customers with higher predicted risk.

---

## 📁 Repository Structure

```text
smartkart-churn-prediction/
│
├── SmartKart_Churn_Prediction_ML_Pipeline.ipynb
│
├── SmartKart_dirty_100_rows.csv
│
├── smartkart_churn_risk_report.csv
│
└── README.md
```

---

## 🛠️ Tools & Technologies

**Programming Language**

* Python

**Libraries**

* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

**Environment**

* Google Colab / Jupyter Notebook

**Machine Learning**

* Logistic Regression
* StandardScaler
* Train-Test Split
* Classification Metrics

---

## ▶️ How to Run

### 1. Download or clone the repository

```bash
git clone https://github.com/your-username/smartkart-churn-prediction.git
```

### 2. Open the notebook

Open:

```text
SmartKart_Churn_Prediction_ML_Pipeline.ipynb
```

### 3. Add the dataset

Upload:

```text
SmartKart_dirty_100_rows.csv
```

to your Google Colab or Jupyter environment.

### 4. Run the notebook

Run the notebook from **top to bottom**.

---

## 📌 Final Output

The project produces a customer churn risk report containing predicted churn information and churn probability.

This output can help a business answer:

> **"Which customers should we try to retain first?"**

---

## 🚀 Key Learning Outcomes

Through this project, I worked with:

* Data Cleaning
* Data Preprocessing
* Missing Value Handling
* Outlier Treatment
* Feature Selection
* Feature Standardisation
* Logistic Regression
* Classification
* Model Evaluation
* Model Interpretation
* Customer Analytics
* Business Decision-Making

---

## 👨‍💻 Project

**SmartKart Customer Churn Prediction**

Built as an academic Machine Learning project demonstrating how **AI/ML can be applied to a real-world business problem**.
