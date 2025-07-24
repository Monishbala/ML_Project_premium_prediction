# ML_Project_premium_prediction

# 🏥 Insurance Premium Predictor

A sleek, Streamlit-based web application that predicts annual insurance premiums using a smart **hybrid modeling pipeline**—designed for clarity, performance, and real-world practicality.

---

## 🚀 Live Demo

Experience it live:  
https://mlprojectpremiumprediction-cashbhcbhjcasjhacb.streamlit.app/

---

## 🧠 Hybrid Model Logic

We combined **linear regression** and **XGBoost** to optimize accuracy and interpretability:

```python
if age <= 25:
    model = linear_regression
else:
    model = xgboost
```

---


Linear Regression for applicants ≤ 25 years: transparent and easy to explain.

XGBoost for ages > 25: powerful and accurate for complex feature relationships.

This switch demonstrates thoughtful model selection tailored to age-based data dynamics.


---

Clone the repo
```
git clone https://github.com/Monishbala/ML_Project_premium_prediction
cd insurance-premium-prediction
```

---

Install dependencies
```
pip install -r requirements.txt
```

---
Run the Streamlit app


```
streamlit run main.py
```



