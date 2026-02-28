# 📘 Capstone Project – Student Query Classification System

**Author:** Syed Sameer
**File:** `capestone_project_91.ipynb`

---

## 📌 Project Overview

This capstone project builds a **Machine Learning-based Student Query Classification System** that automatically predicts the **priority level** of student queries (High, Medium, Low).

The objective is to help academic institutions **identify urgent issues quickly**, streamline response management, and improve overall efficiency in handling student concerns.

---

## 🎯 Problem Statement

Universities receive large volumes of student queries daily across multiple departments. Manually reviewing and prioritizing these queries is time-consuming and inefficient.

This project solves the problem by:

* Applying **Natural Language Processing (NLP)**
* Training a **classification model**
* Automatically predicting query priority levels

---

## 📂 Dataset Description

The dataset used in this project contains:

* `Query_ID` – Unique identifier
* `Department` – Department handling the query
* `Query Text` – Student's query message
* `Priority_Label` – Target variable (High / Medium / Low)

---

## 🔎 Exploratory Data Analysis (EDA)

The notebook performs detailed data exploration including:

### 📊 Distribution Analysis

* Department-wise query distribution
* Priority label frequency

### 🔁 Relationship Analysis

* Department vs Priority comparison
* Cross-tabulation and pivot tables

### ☁️ Text Visualization

* WordCloud of most frequent terms
* Common patterns in student queries

These analyses help understand data imbalance and query trends.

---

## 🧹 Data Preprocessing

Text preprocessing steps include:

* Converting text to lowercase
* Removing punctuation and special characters
* Removing stopwords
* Tokenization
* Cleaning non-alphabetic characters

These steps improve model accuracy by reducing noise in textual data.

---

## ⚙️ Feature Engineering

The textual data is converted into numerical format using:

* **TF-IDF Vectorization**

This transforms text into weighted features suitable for machine learning models.

---

## 🤖 Model Development

The workflow includes:

1. Train-Test Split
2. Model Training
3. Prediction
4. Model Evaluation

Evaluation metrics used:

* Accuracy Score
* Confusion Matrix
* Classification Report

The trained model predicts whether a query is:

* 🔴 High Priority
* 🟡 Medium Priority
* 🟢 Low Priority

---

## 📊 Results & Insights

The model successfully classifies student queries into priority levels, helping institutions:

* Reduce response delay
* Improve ticket resolution efficiency
* Allocate departmental workload effectively

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* NLP Techniques
* WordCloud

---

## ▶️ How to Run

1. Open `capestone_project_91.ipynb` in Jupyter Notebook.
2. Install required libraries if not available.
3. Update dataset path if necessary.
4. Run all cells sequentially.

---

## 🚀 Future Enhancements

* Deploy model using Flask / FastAPI
* Integrate with a real-time student helpdesk system
* Apply Deep Learning models (LSTM / Transformers)
* Handle class imbalance using advanced resampling techniques

---

## 📌 Conclusion

This capstone project demonstrates the practical application of **Machine Learning and NLP** in automating student query prioritization.

It combines structured data analysis, text processing, and classification modeling to deliver a scalable and impactful solution for academic institutions.
