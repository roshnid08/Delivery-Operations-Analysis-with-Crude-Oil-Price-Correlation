# 🚚 Delivery Operations Analysis with Crude Oil Price Correlation

## 📌 Overview
This project analyzes how **crude oil prices (WTI)** impact **delivery operations and logistics performance**.

By combining internal delivery data with external oil market data, the project uncovers key drivers of **delivery disruptions, demand shifts, and fleet inefficiencies**, and builds a predictive model for operational risk.

---

## 🎯 Objectives
- Analyze impact of oil prices on delivery operations  
- Identify drivers of delivery reschedules  
- Detect seasonality and demand patterns  
- Build predictive model for disruption risk  
- Provide data-driven business recommendations  

---

## 📊 Dataset

### Delivery Operations Data
- 763 business days (2022–2025)  
- Includes delivery volume, truck scheduling, reschedules, utilization  

### Crude Oil Data (WTI)
- Daily oil prices (OHLC)  
- Source: Kaggle  
- Joined on date with delivery dataset  

---

## 🛠️ Methodology
- Data Cleaning & Preprocessing  
- Feature Engineering (14+ features):
  - Oil metrics (price, volatility)  
  - Temporal features (day, month, seasonality)  
  - Operational metrics (utilization, volume)  
- Exploratory Data Analysis (EDA)  
- Statistical Testing (correlation, t-tests)  
- Machine Learning:
  - Linear Regression (baseline)  
  - Random Forest (final model)  

---

## 🔍 Key Findings
- Strong correlation between oil prices and reschedules (**r = 0.56**)  
- Oil price increases lead to higher delivery disruptions  
- Random Forest model explains **54% of variability (R² = 0.54)**  
- Delivery demand declined **~20% from 2022 to 2025**  
- Type A trucks exceeded capacity on **~17% of days**  
- Oil price is the **most important predictive feature (~55%)**  

---

## 📈 Model Performance

| Model              | R² Score | MAE |
|-------------------|---------|-----|
| Linear Regression | 0.42    | 1.37 |
| Random Forest     | 0.54    | 1.22 |

---

## 💡 Business Impact
- Enables **predictive risk scoring** for delivery disruptions  
- Supports **dynamic fleet allocation** instead of fixed capacity  
- Improves dispatch planning using external signals (oil price)  
- Reduces operational inefficiencies and costs  

---

## 🚀 Recommendations
- Build a **daily oil-based risk scoring system**  
- Implement **dynamic fleet sizing (Type A trucks)**  
- Pre-plan capacity for **peak season & high-demand days**  
- Use predictive signals for **proactive customer communication**  

---

## ⚠️ Limitations
- Single-yard dataset  
- 47-day data gap in 2023  
- Model explains ~54% variance  
- Correlation does not imply causation  

---

## 🔮 Future Work
- Integrate diesel fuel price data  
- Add weather impact analysis  
- Expand to multi-location datasets  
- Apply time-series forecasting (ARIMA / Prophet)  

---

## 🧰 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- SciPy  
- Matplotlib, Seaborn  

---

## 👩‍💻 Author
**Roshni Dodhi**  
M.S. Computer Science (Data Analytics), Boston University  

---

## ⭐ If you found this useful
Give this repo a ⭐ or connect with me on LinkedIn!
