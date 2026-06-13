# 📧 Email Spam Detection using Machine Learning

## 📌 Project Overview

This project focuses on classifying emails as **Spam** or **Not Spam (Ham)** using Machine Learning. It demonstrates how text data can be processed and used for building a predictive model.

---

## 🎯 Problem Statement

Spam emails are a common issue in digital communication. The goal of this project is to build a machine learning model that can automatically identify whether an email is spam or not.

---

## 📊 Dataset Information

* The dataset contains labeled email messages
* Two categories:

  * Spam (1)
  * Not Spam (0)
* Text data is used as the main feature

---

## ⚙️ Steps Involved

### 1. Data Loading & Understanding

* Imported dataset using Pandas
* Checked structure and basic information

### 2. Data Cleaning

* Removed unnecessary columns
* Converted labels into numerical format

### 3. Exploratory Data Analysis (EDA)

* Visualized spam vs non-spam distribution using countplot

### 4. Text Processing

* Converted text data into numerical vectors using **CountVectorizer**

### 5. Model Building

* Used **Multinomial Naive Bayes** algorithm for classification

### 6. Model Evaluation

* Split data into training and testing sets
* Evaluated model using accuracy score

---

## 📈 Results

* ✅ **Accuracy: 97.48%**
* The model performs very well in distinguishing spam and non-spam emails.

---

## 📸 Output

The model successfully predicts whether a message is spam or not.

### Example:

* Input: *"Congratulations! You won a free lottery ticket"*
* Output: **Spam**

![Output Screenshot](output.png)

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## 🚀 Conclusion

This project demonstrates how machine learning can be applied to text classification problems like spam detection with high accuracy.

---

## 🔮 Future Scope

* Improve text preprocessing
* Try advanced models like Logistic Regression or Deep Learning
* Deploy the model as a web application
