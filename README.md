# Codtech-Task-3-End-to-End-Data-science-project
This project builds a machine learning model to predict student performance based on various academic and demographic features.
# 🎓 Student Performance Prediction - End-to-End Data Science Project

## 📌 Project Overview

This project aims to predict student performance (math score) using machine learning techniques. It follows a complete data science pipeline, including data preprocessing, model training, evaluation, and deployment. The final model is exposed as a web API using Flask for real-time predictions.

---

## 🎯 Objectives

* Analyze student data to identify factors affecting performance
* Build a predictive machine learning model
* Evaluate model accuracy using appropriate metrics
* Deploy the trained model as a REST API

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Flask
* Pickle

---

## 📂 Project Structure

```
├── student_data.csv       # Dataset
├── model.pkl              # Trained model
├── app.py                 # Flask API
├── requirements.txt       # Dependencies
└── notebook.ipynb         # Colab notebook
```

---

## ⚙️ Steps Involved

### 1. Data Collection

* Dataset loaded from CSV file

### 2. Data Preprocessing

* Handling missing values
* Encoding categorical variables
* Splitting into training and testing sets

### 3. Model Building

* Random Forest Regressor used for prediction

### 4. Model Evaluation

* Metrics used: Mean Squared Error (MSE), R² Score

### 5. Model Saving

* Model saved using pickle (`model.pkl`)

### 6. Deployment

* Flask used to create API
* Endpoint `/predict` returns predicted score

---

## 🚀 How to Run Locally

### Step 1: Install dependencies

```
pip install -r requirements.txt
```

### Step 2: Run the Flask app

```
python app.py
```

### Step 3: Open in browser

```
http://127.0.0.1:5000/
```

---

## 📬 API Usage

### Endpoint:

```
POST /predict
```

### Sample Input (JSON):

```
{
  "feature1": 1,
  "feature2": 0,
  "feature3": 1
}
```

### Output:

```
{
  "predicted_score": 75.4
}
```

---

## 📊 Results

* Model successfully predicts student performance
* Achieved good accuracy on test data
* Ready for real-time usage via API

---

## 📦 Deliverables

* Google Colab Notebook
* Trained Model (`model.pkl`)
* Flask API (`app.py`)
* GitHub Repository

---

## 🎯 Conclusion

This project demonstrates a complete machine learning workflow from data preprocessing to deployment, enabling real-time student performance prediction through a web API.

---
Author 

Chandan M

