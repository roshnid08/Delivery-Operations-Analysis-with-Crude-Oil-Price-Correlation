# Delivery-Operations-Analysis-with-Crude-Oil-Price-Correlation


📌 Overview

This project analyzes the relationship between crude oil prices (WTI) and delivery operations performance to understand how external market signals impact logistics disruptions.

By combining internal delivery data with external oil price data, the project identifies key drivers of reschedules, demand shifts, and fleet utilization inefficiencies, and builds a predictive model for operational risk.

🎯 Objectives
Analyze the impact of oil prices on delivery operations
Identify drivers of delivery reschedules
Detect seasonality and demand patterns
Build a predictive model for disruption risk
Provide actionable recommendations for supply chain optimization
📊 Dataset
1. Delivery Operations Data
763 business days (2022–2025)
Features: truck scheduling, delivery volume, reschedules, fleet utilization
2. Crude Oil Data (WTI)
Historical daily oil prices (OHLC)
Source: Kaggle
Joined with delivery data on date
🛠️ Methodology
Data Cleaning & Preprocessing
Feature Engineering (14+ features):
Oil metrics (price, volatility)
Temporal features (day, month, seasonality)
Operational metrics (utilization, volume)
Exploratory Data Analysis (EDA)
Statistical Testing (correlation, t-tests)
Machine Learning:
Linear Regression (baseline)
Random Forest (final model)
🔍 Key Findings
Strong correlation between oil prices and reschedules (r = 0.56)
Oil price increases → higher delivery disruptions
Random Forest model explains 54% of variability (R² = 0.54)
Delivery demand declined ~20% from 2022 to 2025
Type A trucks exceeded capacity on ~17% of days
Oil price is the dominant predictive feature (~55% importance)
📈 Model Performance
Model	R² Score	MAE
Linear Regression	0.42	1.37
Random Forest	0.54	1.22
💡 Business Impact
Enables predictive risk scoring for delivery disruptions
Supports dynamic fleet allocation instead of fixed capacity
Improves dispatch planning using external signals (oil price)
Helps reduce operational inefficiencies and costs
🚀 Recommendations
Build a daily oil-based risk scoring system
Shift to dynamic fleet sizing (especially Type A trucks)
Pre-plan capacity for peak season & high-demand days
Use predictive signals for proactive customer communication
⚠️ Limitations
Single-yard dataset (not fully generalized)
47-day data gap in 2023
Model explains ~54% variance (external factors remain)
Correlation does not imply causation
🔮 Future Work
Integrate diesel fuel prices (more direct cost signal)
Add weather data for operational impact
Expand to multi-location analysis
Apply time-series forecasting (ARIMA / Prophet)
🧰 Tech Stack
Python
Pandas, NumPy
Scikit-learn
SciPy
Matplotlib, Seaborn
👩‍💻 Author

Roshni Dodhi
M.S. Computer Science (Data Analytics), Boston University

⭐ If you found this useful

Feel free to ⭐ the repo or connect with me on LinkedIn!
