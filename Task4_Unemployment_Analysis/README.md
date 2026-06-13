# 📉 Unemployment Analysis & Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Project-green)

A Machine Learning project that analyzes unemployment trends in India and predicts unemployment rates using regression techniques.

---

## 📌 Project Overview

This project focuses on analyzing unemployment data to understand trends and patterns over time. It demonstrates how data analysis and machine learning can be used to predict unemployment rates and generate meaningful insights.

---

## 🎯 Problem Statement

Unemployment is a critical economic indicator. The goal of this project is to build a model that can analyze historical data and predict unemployment rates based on various factors.

---

## 📊 Dataset Information

* Dataset contains unemployment data across different regions and time periods

* Includes features like:

  * Region
  * Date / Time
  * Estimated Employed
  * Estimated Unemployment Rate (%)
  * Labour Participation Rate (%)

* Target variable:

  * Unemployment Rate

---

## ⚙️ Steps Involved

### 1. Data Loading & Understanding

* Loaded dataset using Pandas
* Explored dataset structure and key features

### 2. Data Cleaning

* Handled missing values
* Removed unnecessary columns

### 3. Exploratory Data Analysis (EDA)

* Visualized unemployment trends over time
* Analyzed regional differences
* Used line plots and heatmaps

### 4. Feature Engineering

* Selected relevant features
* Converted date/time data if required

### 5. Model Building

* Applied **Random Forest Regressor**

### 6. Model Evaluation

* Split dataset into training and testing sets
* Evaluated using:

  * MAE (Mean Absolute Error)
  * MSE (Mean Squared Error)
  * R² Score

---

## 📈 Results

🚀 **Model Performance:**

* MAE: 1.4607
* MSE: 3.1740
* R² Score: 0.8994

✅ **Accuracy: ~89.94%**

The model provides strong performance in predicting unemployment rates.

---

**Example Prediction:**

* Input: Region, employment data
* Output: Predicted Unemployment Rate

## 🛠️ Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## 📂 Project Structure

* `Unemployment_Analysis_Prediction.ipynb`
* `README.md`
* `output.png`
* `score.png`

---

## 🚀 Conclusion

This project demonstrates how machine learning models can be used to analyze economic data and predict unemployment trends effectively.

---

## 🔮 Future Scope

* Try advanced models (XGBoost, Gradient Boosting)
* Hyperparameter tuning
* Build interactive dashboards
* Deploy as a web application

---

## 👩‍💻 Author

* Sandhya
