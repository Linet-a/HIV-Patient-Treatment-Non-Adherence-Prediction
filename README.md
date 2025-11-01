# HIV Patient Treatment Non-Adherence Prediction

This project explores **treatment non-adherence among HIV patients** using real-world data provided by **Kasha**.  
It combines **data analytics**, **machine learning**, and **explainable AI** (SHAP) to identify and interpret the most significant factors influencing patient adherence.  

In the next phase, the project will integrate a **Large Language Model (LLM)** to provide intelligent, data-driven **stakeholder support** — helping healthcare workers, policymakers, and NGOs make informed decisions on improving treatment outcomes.

---

## 🚀 Project Overview

The **HIV Patient Treatment Non-Adherence Prediction** system is designed to:

- Analyze patient-related, clinical, and socio-economic data from **Kasha**.  
- Predict the likelihood of **non-adherence to HIV treatment**.  
- Provide **explainable insights** through **SHAP visualizations**, highlighting key predictors (e.g., missed appointments, age group, counseling frequency).  
- Offer **stakeholder-friendly insights** through an interactive **Streamlit dashboard**.  
- Prototype an **LLM-powered assistant** that can summarize findings, generate recommendations, and answer stakeholder questions in plain language.

---

## 🧠 Core Features

- 🧩 **Data Preprocessing & Cleaning:**  
  Includes handling missing data, normalization, and encoding of categorical features.

- 📊 **Exploratory Data Analysis (EDA):**  
  Visual summaries of adherence trends and demographic distributions.

- 🤖 **Machine Learning Model:**  
  A predictive model (e.g., Random Forest / XGBoost) trained to classify adherence vs. non-adherence.

- 🔍 **Explainability with SHAP:**  
  SHAP (SHapley Additive exPlanations) is used to:
  - Interpret model outputs.
  - Show which variables most influence non-adherence.
  - Improve transparency and trust for medical stakeholders.

- 💬 **LLM-Based Stakeholder Support (Future Phase):**  
  Integrate an LLM (such as GPT or LLaMA) to:
  - Translate data insights into simple narratives.  
  - Support decision-making through conversational Q&A.  
  - Generate policy briefs or stakeholder summaries directly from model outputs.

- 🌐 **Streamlit App Interface:**  
  An interactive dashboard for visual exploration, scenario simulation, and stakeholder engagement.

---

## 🧰 Tech Stack

| Category | Tools & Libraries |
|-----------|-------------------|
| **Programming** | Python |
| **Web App** | Streamlit |
| **ML & Explainability** | scikit-learn, pandas, numpy, SHAP |
| **Visualization** | matplotlib, seaborn, plotly |
| **Future AI Support** | OpenAI / LLaMA-based LLM integration |
| **Data Source** | Kasha patient adherence dataset |

---

## 🧩 How to Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/Linet-a/HIV-Patient-Treatment-Non-Adherence-Prediction.git
   cd HIV-Patient-Treatment-Non-Adherence-Prediction
