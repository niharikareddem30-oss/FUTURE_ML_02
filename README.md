# Support Ticket Classification & Prioritization System

## 📌 Project Overview
This project focuses on building a **Machine Learning-based Support Ticket Classification and Prioritization System**.

Customer support teams receive thousands of support tickets daily, making manual sorting time-consuming and inefficient. This system automates:

- **Ticket Category Classification**
- **Ticket Priority Prediction**

The goal is to help businesses respond faster, reduce delays, and improve customer satisfaction.

---

## 🎯 Objectives
The project aims to:

✔ Automatically classify support tickets into categories  
✔ Predict priority levels for faster issue resolution  
✔ Use NLP techniques for text preprocessing  
✔ Evaluate model performance using ML metrics

---

## 🛠️ Technologies Used

### Programming Language
- Python

### Development Environment
- Google Colab / Jupyter Notebook

### Libraries Used
- Pandas
- NumPy
- Matplotlib
- NLTK
- Scikit-learn

---

## 📂 Dataset
Dataset used:

**Customer Support Ticket Dataset (Kaggle)**

The dataset contains customer support ticket details including:

- Ticket Description
- Ticket Type
- Ticket Priority
- Ticket Status
- Resolution Details

---

## ⚙️ Project Workflow

### 1. Data Loading
- Imported customer support ticket dataset
- Explored dataset structure

### 2. Data Preprocessing
Performed NLP preprocessing:

- Converted text to lowercase
- Removed punctuation
- Removed stopwords
- Cleaned ticket descriptions

### 3. Feature Extraction
Used **TF-IDF Vectorization** to convert ticket text into numerical features.

### 4. Ticket Category Classification
Built a machine learning model to classify tickets into categories such as:

- Technical Issue
- Billing Inquiry
- Product Inquiry
- Refund Request
- Cancellation Request

### 5. Priority Prediction
Built a classification model to predict ticket priority:

- Critical
- High
- Medium
- Low

### 6. Model Evaluation
Evaluated model performance using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Results
### Ticket Category Classification
- Model trained successfully
- Classification report generated
- Accuracy evaluated

### Priority Prediction
- Priority prediction model trained successfully
- Accuracy ≈ **25%**
- Performance evaluated using classification metrics

---

## 📈 Business Impact
This system helps organizations:

- Automate ticket sorting
- Prioritize urgent issues faster
- Reduce manual workload
- Improve response efficiency
- Enhance customer satisfaction

---

## 🚀 Future Improvements
Possible improvements include:

- Using advanced NLP models
- Trying Logistic Regression or Random Forest
- Hyperparameter tuning
- Using deep learning models (LSTM/BERT)
- Improving classification accuracy

---

## 📌 Repository Structure

```bash
├── Support_Ticket_Classification_Task2_Niharika.ipynb
├── customer_support_tickets.csv
└── README.md
```

---

## Author
**Niharika Reddy**

Machine Learning Internship Project – Future Interns (2026)
