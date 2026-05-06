# ⚖️ AI Fairness Analyzer

## 📌 Overview
AI Fairness Analyzer is a web-based application that helps detect, analyze, and reduce bias in datasets used for AI/ML models. It provides visual insights, fairness metrics, and suggestions to improve model fairness.

---

## 🚀 Features

- 📂 Upload CSV dataset
- 🎯 Select target and sensitive attributes
- 👥 Multi-sensitive (intersectional) analysis
- 📊 Visualizations (bar charts, pie charts, comparison graphs)
- ⚖️ Fairness Metrics:
  - Bias Score
  - Fairness Score
  - Demographic Parity Difference (DPD)
  - Disparate Impact Ratio (DIR)
  - Equal Opportunity (EO)
- 🛠️ Bias Mitigation (Before vs After comparison)
- 🤖 AI Assistant (powered by Google Gemini)
- 📄 Auto-generated Report
- 🔐 Login / Signup / Forgot Password system

---

## 🧠 Problem Statement

AI systems can unintentionally produce biased outcomes when trained on imbalanced or sensitive data (e.g., gender, age, race). This leads to unfair decisions in areas like hiring, finance, and healthcare.

---

## 💡 Solution

This application allows users to:
- Detect bias in datasets
- Understand fairness metrics visually
- Identify most and least affected groups
- Apply bias correction techniques
- Interact with an AI assistant for insights

---

## 🛠️ Tech Stack

- **Frontend & Backend:** Streamlit  
- **Programming Language:** Python  
- **Data Handling:** Pandas  
- **Visualization:** Matplotlib  
- **AI Integration:** Google Gemini API  

---

## 🤖 AI Integration

We use **Google Gemini AI** to provide an intelligent assistant that answers user queries such as:
- Why is fairness score low/high?
- What is DPD?
- How to improve fairness?
- Dataset insights (rows, columns, missing values)

---

## 📊 How It Works

1. Upload dataset (CSV)
2. Select target column (output)
3. Select sensitive column (e.g., gender)
4. Click **Check Bias**
5. View:
   - Bias score
   - Fairness score
   - Graphs & comparisons
6. Explore mitigation results
7. Ask questions using AI Assistant

---

## 🔐 Security

- API keys are stored securely using `.env`
- `.env` is excluded using `.gitignore`
- Sensitive data is not exposed publicly

---

## 📦 Installation

```bash
git clone https://github.com/your-username/AI-Fairness-Analyzer.git
cd AI-Fairness-Analyzer
pip install -r requirements.txt
streamlit run app.py
