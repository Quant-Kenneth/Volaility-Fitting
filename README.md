# GARCH and EGARCH Models for Estimating Volatility: AAPL

This project applies **time series modeling techniques** to estimate and forecast the volatility of Apple Inc. (AAPL) returns using **GARCH(1,1)** and **EGARCH(1,1)** models.

---

## 📈 Project Overview

Volatility modeling is central to:
- 📊 **Portfolio optimization**
- 💰 **Risk valuation**
- 🧮 **Derivatives pricing**
- 🛡 **Hedging strategies**

Using Python and daily returns from AAPL, this project follows the full quant workflow:

1. **Data preprocessing** (log returns, missing values)
2. **Initial GARCH(1,1) modeling**
3. **Residual diagnostics and model validation**
4. **Improved modeling with EGARCH(1,1)**
5. **30-day ahead volatility forecasting**
6. **Forecast comparison and interpretation**

---

## 🔧 Tools & Libraries

- `pandas` & `numpy` for data manipulation
- `arch` for GARCH/EGARCH modeling
- `matplotlib` & `seaborn` for visualization
- `statsmodels` for statistical diagnostics

---

## 📊 Key Findings

- The initial GARCH(1,1) model captured general volatility clustering but failed diagnostic tests.
- EGARCH(1,1) accounted for **leverage effects** and **fat tails**, improving residual behavior and forecast quality.
- EGARCH produced more realistic volatility forecasts, aligning closely with rolling historical volatility.

---

## 🔍 Use Cases

✅ Quantitative research  
✅ Portfolio construction  
✅ Market risk forecasting  
✅ Systematic strategy design  

---

## 📂 Files

| File | Description |
|------|-------------|
| `AAPL_GARCH_EGARCH.ipynb` | Full notebook with modeling workflow |
| `Fiting Volatility.pdf` | LaTeX write-up of full methodology and results |

---

## 📥 Run It Yourself

To reproduce results:
```bash
pip install arch pandas matplotlib statsmodels
