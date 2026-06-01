# FUTURE_ML_02

# Customer Support Ticket Classification & Priority Prediction

## 📌 Project Overview

Customer support teams receive a large number of tickets daily, making manual categorization and prioritization time-consuming and inefficient.

This project uses Natural Language Processing (NLP) and Machine Learning to automatically classify support tickets into categories and predict their priority levels. The solution helps businesses improve support operations, reduce response time, and enhance customer satisfaction.

---

## 🎯 Objectives

- Automatically classify customer support tickets into predefined categories.
- Predict ticket priority levels (High, Medium, Low).
- Reduce manual ticket sorting effort.
- Improve operational efficiency of support teams.

---

## 📂 Dataset

**Dataset Used:** Customer Support Ticket Dataset

The dataset contains:

- Ticket Description
- Ticket Type
- Ticket Priority
- Ticket Status
- Customer Information
- Resolution Information

### Ticket Categories

- Refund Request
- Technical Issue
- Cancellation Request
- Product Inquiry
- Billing Inquiry

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- VS Code
- Git & GitHub

---

## 🔄 Project Workflow

### 1. Data Loading

- Loaded customer support ticket dataset.
- Explored dataset structure and features.

### 2. Text Preprocessing

Performed:

- Lowercase conversion
- Punctuation removal
- Text cleaning
- Preparation of ticket descriptions for NLP processing

### 3. Feature Extraction

Used **TF-IDF Vectorization** to convert ticket text into numerical features suitable for machine learning models.

### 4. Ticket Classification

Implemented machine learning models to classify tickets into categories.

Models Used:

- Logistic Regression
- Multinomial Naive Bayes

### 5. Priority Prediction

Built a separate machine learning model to predict ticket priority levels.

Priority Classes:

- High
- Medium
- Low

### 6. Model Evaluation

Evaluated model performance using:

- Accuracy Score
- Classification Report
- Confusion Matrix

---

## 📊 Results

### Ticket Type Classification

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 18.18% |
| Multinomial Naive Bayes | 18.95% |

### Priority Prediction

| Model | Accuracy |
|---------|---------|
| Logistic Regression | 26.74% |

---

## 📈 Dataset Distribution

| Ticket Type | Count |
|------------|-------|
| Refund Request | 1752 |
| Technical Issue | 1747 |
| Cancellation Request | 1695 |
| Product Inquiry | 1641 |
| Billing Inquiry | 1634 |

---

## 📷 Output Visualizations

- Confusion Matrix
- Classification Results
- Model Performance Metrics

---

## 💼 Business Impact

This project can help organizations:

- Automatically route tickets to the correct department
- Reduce manual workload for support teams
- Improve ticket response times
- Prioritize urgent customer issues
- Increase customer satisfaction
- Improve operational efficiency

---

## 🚀 Future Improvements

Potential enhancements include:

- Advanced text preprocessing using NLTK and spaCy
- Hyperparameter tuning
- Deep Learning models
- BERT-based ticket classification
- Real-time ticket prediction API
- Deployment using Flask or Streamlit

---

## 📁 Project Structure

```text
FUTURE_ML_02
│
├── data
│   └── customer_support_tickets.csv
│
├── notebooks
│   └── support_ticket_classification.ipynb
│
├── outputs
│   └── confusion_matrix.png
│
├── src
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 📌 Internship Information

**Organization:** Future Interns

**Track:** Machine Learning

**Task:** Task 02 – Customer Support Ticket Classification & Priority Prediction

---

## 👨‍💻 Author

**SAI CHARITHA AMARNENI**

B.Tech – Artificial Intelligence & Machine Learning

Future Interns – Machine Learning Internship