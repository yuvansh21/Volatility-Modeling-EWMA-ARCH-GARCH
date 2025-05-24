
# 📈 Volatility Modeling using ARCH, GARCH, and EWMA (Reliance Stock)

This project models how stock market volatility changes over time using historical data of **Reliance Industries**. It uses three models:

- **EWMA** (Exponentially Weighted Moving Average)
- **ARCH(1)** (Autoregressive Conditional Heteroskedasticity)
- **GARCH(1,1)** (Generalized ARCH)

We also calculate **Value-at-Risk (VaR)** using the EWMA model to estimate potential losses.

---

## 📊 Key Features

- Load and clean real stock price data
- Compute daily returns
- Estimate volatility using EWMA, ARCH(1), and GARCH(1,1)
- Compare volatility visually
- Calculate 1-day 95% EWMA-based Value-at-Risk (VaR)

---

## 📁 Project Structure

```

volatility-models/
├── data/
│   └── RELI Historical Data.csv
├── notebooks/
│   └── volatility\_modeling.ipynb
├── README.md
└── requirements.txt

````

---

## 📦 Requirements

Install these Python packages before running the project:

```bash
pip install pandas numpy matplotlib yfinance arch
````

---

## 🚀 How to Run

1. Open the notebook `volatility_modeling.ipynb`
2. It will:

   * Load Reliance stock prices
   * Calculate daily returns
   * Estimate volatility using EWMA, ARCH(1), and GARCH(1,1)
   * Plot volatility over time
   * Calculate 1-day 95% EWMA-based Value-at-Risk (VaR)

---

## 📉 EWMA VaR Formula

We use the formula:

```
VaR = - z * EWMA Volatility
```

Where `z = 1.65` for a 95% confidence level.

---

## ✅ Output: What You’ll See

* 📈 Line chart comparing EWMA, ARCH, and GARCH volatility
* 📉 Table showing daily VaR in % and ₹ terms
* 📊 Insight into how financial volatility evolves over time

---

## 🙌 Tools Used

* [pandas](https://pandas.pydata.org/)
* [matplotlib](https://matplotlib.org/)
* [arch](https://arch.readthedocs.io/)
* [yfinance](https://pypi.org/project/yfinance/)

---





```

---

✅ Just run this cell — it creates a perfect `README.md` file, no copying, no manual errors, all headings fixed. Let me know if you want this zipped with folder structure too!
```
