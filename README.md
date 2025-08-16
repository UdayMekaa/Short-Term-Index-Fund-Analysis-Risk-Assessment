# Short-Term Stock Fund Forecasting & Risk Analysis

This project analyzes over **50 years of global stock index data** to identify the most promising short-term investment opportunities.  
It combines **historical performance analysis**, **time series forecasting**, and **risk assessment** to support data-driven fund selection.

---

## 📂 Dataset

- **Source:** Historical stock index data since 1965
- **Indexes:** 13 major global indexes
- **Columns:**
  - `Index` – Ticker symbol for indexes
  - `Date` – Date of observation
  - `Open` – Opening price
  - `High` – Highest price during the day
  - `Low` – Lowest price during the day
  - `Close` – Closing price
  - `Adj Close` – Adjusted close price
  - `Volume` – Shares traded
  - `CloseUSD` – Close price in USD

---

## 🎯 Project Objectives

1. **Identify** the index with the highest average annual return.
2. **Visualize** 30-day moving averages for trend analysis.
3. **Compare** volatility across indexes.
4. **Forecast** short-term prices using *Facebook Prophet*.
5. **Evaluate** risk with volatility measures & Sharpe ratios.
6. **Test** forecast stability using ±10% price shock stress tests.

---

## 🛠 Tools & Technologies

- **Python**
- Pandas
- NumPy
- Matplotlib / Seaborn
- Facebook Prophet
- Statsmodels
- Scikit-learn

---

## 📊 Key Insights

- Some high-return indexes show **high volatility** and are unstable under small market shocks.
- A **decision matrix** was built to integrate:
  - Return  
  - Risk  
  - Forecast stability  
- High stability indexes may provide **more reliable short-term returns** than the highest-return options.

---

## 📈 Sample Visuals

![Visualizations](https://github.com/UdayMekaa/Short-Term-Index-Fund-Analysis-Risk-Assessment/blob/cb81e7f0a0055efa9934d09b213e48b2a0d29d51/Visualization.pdf)

---

## 🚀 How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/index-fund-forecasting.git

## Future Work

* Expand dataset with more indexes.

* Integrate macroeconomic indicators into forecasting.

* Automate dashboard updates using Streamlit.

**Author**: Uday Meka
**Contact: Email –** satyaudaymeka@gmail.com
