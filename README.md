# Investor-Aligned Dynamic Index (IADI) 📊

## Overview
**IADI** is a personalized index construction framework that adapts to **individual investor profiles** and **prevailing macroeconomic regimes**. Unlike traditional static benchmarks (e.g., NIFTY 50, SENSEX), IADI dynamically generates customized asset allocations through a data-driven fusion of **investor signature profiling**, **macro regime detection**, and **multi-factor stock scoring**.

This framework is designed for India’s diverse retail investor base, addressing the limitations of one-size-fits-all indexing by creating **modular, behavior-aware, and market-responsive portfolios**.

---

## 🔍 Key Features
- 🧠 **Investor Signature Profiling**  
  Classifies investors using demographic inputs, financial goals, and behavioral attributes into custom profiles (e.g., A1, B2, C3).

- 🌐 **Macro Regime Detection**  
  Dynamically determines current market regime (e.g., Growth, Volatility, Stagflation) using indicators like:
  - VIX (Volatility Index)
  - Repo Rate
  - CPI (Consumer Price Index)
  - INR volatility

- 📈 **Smart Asset Mapping**  
  Allocates assets using multi-factor stock scoring models including:
  - Momentum
  - Quality
  - Value
  - Volatility
  - Size

- 🔁 **Quarterly Rebalancing**  
  Portfolio updates are triggered by:
  - Regime shifts
  - Profile reclassification (e.g., change in age, goals, risk appetite)

- 📊 **Backtested Performance**  
  In FY25 Q2 volatility scenarios, IADI outperformed traditional static indices by up to **22%**, particularly by aligning with defensive and growth themes based on context.

---

## 🛠 Tech Stack
- **Python** – Core programming language
- **Pandas, NumPy** – Data processing & analysis
- **yfinance** – Fetching historical stock and macroeconomic data
- **Matplotlib, Seaborn** – Data visualization
- *(Optional extensions: TA-Lib for technical indicators, Scikit-learn for ML-based regime detection)*

---

## 📁 Project Structure


---

## 🧪 Sample Output
- 👤 **Profile A1 + Growth Regime** → Overweight Tech/Midcaps *(e.g., Zomato, Infosys)*
- 👤 **Profile C3 + Volatile Regime** → Defensive Large Caps *(e.g., ITC, SBI, HUL)*
- 📊 **Backtest Result (FY25 Q2)** →  
  IADI outperformed benchmark by **22%** during high volatility through dynamic rotation into defensives.

---

## 🚀 Future Scope
- 🤖 Integrate machine learning for **adaptive regime classification**
- 🌐 Build a real-time **web dashboard** for investor onboarding and live profiling
- 🌍 Expand asset universe to include **mutual funds, ETFs**, and **global equities**
- 📲 Enable mobile app for **portfolio nudges and alerts** based on regime changes

---

## ⚠️ Disclaimer
This project is intended for **educational and research purposes only**. Investment decisions should not be made solely based on this framework without consulting a licensed financial advisor.



