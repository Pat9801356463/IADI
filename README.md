Investor-Aligned Dynamic Index (IADI)
Personalized Index Construction Using Investor Profiling and Market Regimes

Overview
The IADI framework is a personalized index construction engine that adapts to individual investor profiles and prevailing macroeconomic conditions. Unlike traditional benchmarks (e.g., NIFTY 50, SENSEX), IADI dynamically generates asset allocations using data-driven profiling, macro regime detection, and multi-factor stock scoring.

This project addresses the static disconnect in traditional indexing by offering a modular, behavior-aware, and regime-responsive solution for smart investing—tailored for India's diverse retail investor landscape.

Key Features
Investor Signature Profiling using demographic, behavioral, and financial goal inputs

Macro Regime Detection with real-world indicators: VIX, Repo Rate, CPI, and more

Smart Asset Mapping based on multi-factor scoring (momentum, quality, value, etc.)

Quarterly Rebalancing tied to both market shifts and user profile updates

Backtested Strategy delivering up to 22% outperformance during FY25 Q2 volatility

Tech Stack
Python – Core logic

Pandas, NumPy – Data manipulation and processing

yfinance – Stock price and macroeconomic data fetching

Matplotlib, Seaborn – Visualization

(Optional: TA-Lib, Scikit-learn for further extensions)

Project Structure
bash
Copy
Edit
investor_signature.py         # Profile classification logic (e.g., A1, B2, C3)
macro_regime.py               # Regime detection using indicators like VIX, CPI, etc.
asset_selector.py             # Multi-factor scoring, filtering, and weighting
rebalance_simulation.py       # Quarterly rebalancing logic
backtest.ipynb                # Full backtesting and visualization notebook
README.md
Sample Output
Profile A1 + Growth Regime → Overweight tech/midcaps (e.g., Zomato)

Profile C3 + Volatility → Large-cap defensives (e.g., ITC, SBI)

FY25 Q2 Backtest → IADI delivered 22% higher returns vs static index

Future Scope
Incorporate machine learning for dynamic regime classification

Build a web dashboard with real-time personalization

Expand to include mutual funds, ETFs, and international equities

