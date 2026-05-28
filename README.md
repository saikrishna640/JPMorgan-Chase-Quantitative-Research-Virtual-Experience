# J.P. Morgan Chase — Quantitative Research Virtual Experience
**Platform:** Forage | **Duration:** Feb 2026 – Mar 2026

## Overview
Four-task quantitative research simulation executing real financial 
engineering and predictive modeling problems used by JPMorgan analysts.

## Task 1 — Natural Gas Price Forecasting
- Loaded and visualized historical monthly natural gas prices (2020–2024)
- Built a price estimation function for any past or future date
- Used linear interpolation for historical dates
- Used seasonal lag model (same date prior year + daily growth trend) 
  for future forecasting
- **Output:** Price on Jan 15 2022 = $11.45 | Predicted Jan 15 2025 = $12.81

## Task 2 — Commodity Storage Contract Pricing Engine
- Built a function to calculate net value of a gas storage trade
- Formula: (Sell Price − Buy Price) × Volume − Storage Costs − 
  Injection/Withdrawal Fees − Transport Costs
- **Output:** 1M MMBtu stored 4 months = $490,000 net contract value

## Task 3 — Credit Default Prediction Model
- Trained Logistic Regression on 10,000+ loan records
- Features: FICO score, income, debt, employment years, credit lines
- Built expected loss calculator: PD × 90% × Loan Amount
- **Output:** FICO 500 customer → 100% default probability | 
  FICO 750 customer → 0% default probability

## Task 4 — FICO Score Risk Bucketing (Dynamic Programming)
- Used Dynamic Programming to find statistically optimal FICO boundaries
- Maximized log-likelihood to ensure each bucket has distinct default rates
- **Output:** 5 risk tiers — Bucket 1: <455 (highest risk) through 
  Bucket 5: ≥754 (lowest risk)

## Tools Used
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook

## Certificate
Issued by Forage — Credential verifiable at forage.com
