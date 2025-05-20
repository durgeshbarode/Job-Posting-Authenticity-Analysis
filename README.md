# **Fraudulent Job Posting Detection System**

**Live Demo:** [Click Here](https://jobposting-authenticity-analysis.onrender.com/)

###### Due to free instance will spin down with inactivity, which can delay requests by 50 seconds or more. so please wait until it loads

## Preview 

![alt text](image-1.png)
![alt text](image-2.png)


## **Overview**
Detecting fraudulent job postings is crucial in today's online job market. This web-based application leverages machine learning to assess the authenticity of job postings. By analyzing the job description, it predicts whether a listing is genuine or fraudulent, helping users make informed decisions.

---

## **Key Features**
- **Multiple Machine Learning Models:**
  - Predictions are generated using five different ML models: Naive Bayes, Support Vector Machine (SVM), Random Forest, XGBoost, and Logistic Regression.
- **User-Friendly Interface:**
  - A clean and responsive web design that allows users to easily input job descriptions and view results.
- **Instant Results:**
  - Predictions from all models are displayed in real time, with an aggregated final verdict.
- **Keyword-Based Fraud Detection:**
  - Identifies potentially fraudulent postings using specific keywords and patterns.

---

## **Technology Stack**
### **Front-End**
- **HTML & CSS** – Provides structure and styling for a seamless user experience.

### **Back-End**
- **Flask** – Manages web requests and integrates the machine learning models.
- **Python** – Handles data processing, model prediction, and logic implementation.

### **Machine Learning**
- **Algorithms Used:** Naive Bayes, SVM, Random Forest, XGBoost, Logistic Regression.
- **Libraries & Tools:** Scikit-learn, XGBoost, Pandas, NumPy, Pickle (for model storage and loading).

---

## **How It Works**
1. The user inputs a job description into the web interface.
2. The system processes the text and runs it through five different machine learning models.
3. Individual model predictions are displayed alongside a final aggregated result.
4. If fraud-indicating keywords are detected, an alert is provided.

This project serves as a valuable tool for job seekers, recruiters, and organizations aiming to identify and prevent job fraud effectively. 🚀
