# AI/ML Engineering Internship Projects

**Organization:** DevelopersHub Corporation  
**Intern:** Shayan Ali  
**Submission Date:** April 3rd, 2026

This repository contains a collection of machine learning and natural language processing tasks completed during my AI/ML Engineering internship. Each project focuses on the end-to-end pipeline, from data cleaning and exploratory analysis to model deployment and evaluation.

---

## 📋 Task Summaries

### Task 3: Heart Disease Prediction
* **Objective:** Build a binary classification model to predict the presence of heart disease based on clinical parameters.
* **Dataset:** Heart Disease UCI Dataset.
* **Models Applied:** Logistic Regression.
* **Key Results & Findings:** * Achieved a model accuracy of **~85%** with an **AUC score of 0.90**.
    * Identified **Chest Pain Type (cp)** and **Max Heart Rate (thalach)** as the most significant risk indicators.

### Task 5: Mental Health Support Chatbot
* **Objective:** Create an empathetic conversational AI designed to provide mental health support and listen to user concerns.
* **Dataset:** Mental Health Counseling Conversations (Hugging Face).
* **Models Applied:** Fine-tuned Transformer models (`AutoModelForCausalLM`).
* **Key Results & Findings:** * Implemented an interactive chat interface with built-in crisis disclaimers.
    * Successfully fine-tuned the model to provide validating and supportive responses rather than just factual answers.

### Task 6: House Price Prediction
* **Objective:** Develop a regression model to estimate median house values using demographic and geographical data.
* **Dataset:** California Housing Dataset.
* **Models Applied:** Linear Regression.
* **Key Results & Findings:** * Performed rigorous data preprocessing including **outlier removal using the IQR method**.
    * Discovered that **Median Income (MedInc)** is the strongest positive driver of house prices in the region.

---

## 🛠️ Requirements & Installation

To run the notebooks locally, ensure you have Python 3.10+ installed along with the following dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn transformers datasets accelerate torch
