# 🏦 Bank Marketing Response Predictor

## 📌 Overview

This project uses machine learning techniques to analyze a bank's telemarketing campaign data and predict whether a customer will subscribe to a term deposit.

The goal is to help banks optimize their marketing strategies by identifying potential customers who are more likely to respond positively, thereby reducing costs and increasing campaign efficiency.

---

## 🎯 Objectives

* Analyze customer and campaign data
* Identify key factors influencing customer decisions
* Build predictive models for subscription likelihood
* Improve marketing targeting and efficiency

---

## 📊 Dataset

* **Source:** Bank Marketing Dataset (`bank-additional-full.csv`)

* **Records:** ~41,000 entries

* **Features include:**

  * Demographics (age, job, marital status)
  * Financial indicators
  * Campaign details (contact type, duration, number of contacts)
  * Economic indicators

* **Target Variable:**

  * `y` → Whether the client subscribed to a term deposit (`yes` / `no`)

---

## 🧪 Project Workflow

### 1. Data Exploration (EDA)

* Understanding feature distributions
* Identifying categorical and numerical variables
* Visualizing relationships using plots

### 2. Data Preprocessing

* Cleaning column names
* Handling categorical variables
* Encoding and scaling data

### 3. Model Building

The following machine learning models were implemented:

* Support Vector Machine (SVM)
* K-Nearest Neighbors (KNN)
* Linear Regression (used for experimentation)

### 4. Prediction Goal

* Classify customers as likely or unlikely to subscribe
* Support better decision-making for marketing campaigns

---

## 🛠️ Tech Stack

* **Programming Language:** Python
* **Libraries:**

  * pandas
  * numpy
  * matplotlib
  * seaborn
  * scikit-learn

---

## 📈 Key Insights

* Call duration is a strong predictor of customer response
* Certain job categories and contact methods influence outcomes
* Targeted marketing can significantly improve conversion rates

---

## 🚀 Future Improvements

* Use classification-specific models like Logistic Regression
* Try advanced models (Random Forest, XGBoost)
* Perform hyperparameter tuning
* Deploy as a web app using Flask or Streamlit

---

## 📂 Project Structure

```
├── bank.ipynb
├── bank-additional-full.csv
├── README.md
```

---

## 💡 Author

Naresh
