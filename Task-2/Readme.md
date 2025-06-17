# 📊 Task-2: Predictive Model Plan — Credit Delinquency Risk

This repository contains the deliverables for **Task-2** of the Geldium Data Science Project, focused on designing a predictive model to forecast customer credit delinquency.

---

## 📌 Overview

In this task, we conceptualized and outlined a structured predictive modeling pipeline using **Generative AI tools**. The plan includes model logic, justification for model selection, and an evaluation strategy for assessing model performance and fairness.

---

## 📖 Deliverables

### 1️⃣ Model Logic (Generated with GenAI)

- **Model Type:** Random Forest Classifier
- **Purpose:** Predict the likelihood of a customer becoming delinquent based on financial and behavioral features.
- **Key Features:** 
  - Missed_Payments
  - Credit_Utilization
  - Credit_Score
  - Income
  - Debt_to_Income_Ratio
- **Workflow:** Data ingestion → Feature selection → Data split → Model training → Prediction → Evaluation → Bias check

---

### 2️⃣ Justification for Model Choice

- Random Forest offers a strong balance between **accuracy**, **robustness**, and **interpretability**.
- It is well-suited for financial data and aligns with Geldium’s need for **transparent**, **auditable**, and **reliable** risk prediction models.
- Alternative: Logistic Regression for high-transparency use cases.

---

### 3️⃣ Evaluation Strategy

- **Metrics Used:** Accuracy, F1 Score, ROC AUC, Confusion Matrix
- **Bias Detection:** Evaluate model performance across demographic groups (e.g., Employment Status, Age)
- **Ethical Considerations:** Ensure fairness, transparency, and regulatory compliance in financial decision-making.

---

## 📊 Tools & Libraries

- GenAI (ChatGPT, Gemini)
- Python (Pandas, Scikit-learn, Matplotlib, Seaborn)

---

## 📌 Next Steps

- Build and test the actual predictive model.
- Conduct cross-validation and hyperparameter tuning.
- Perform fairness and bias audits.
- Prepare deployment-ready model pipeline.

---

## 📑 License

This project is for academic and learning purposes under the Geldium predictive analytics program.

---

**Author:** P. Yaswanth Kumar  
**Project:** Geldium AI-Driven Credit Risk Modeling

