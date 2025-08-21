# Back---testing-II


# 📈 Bollinger Bands Trading Strategies

This repository contains multiple **Bollinger Bands–based trading strategies** implemented in Jupyter Notebooks. Each notebook explores different variations of entry rules, stop-loss mechanisms, and trailing logic. The aim is to test and compare how Bollinger Bands can be used for systematic trading.

---

## 🔍 What Are Bollinger Bands?

Bollinger Bands are a volatility-based technical indicator consisting of:

* **Middle Band** → Moving Average (20-period SMA).
* **Upper Band** → Middle Band + (2 x standard deviation).
* **Lower Band** → Middle Band – (2 x standard deviation).

They expand and contract based on volatility and are widely used for spotting overbought/oversold conditions, reversals, and trend continuations.

---

## 📂 Repository Contents

| Notebook                                                     | Description                                                                |
| ------------------------------------------------------------ | -------------------------------------------------------------------------- |
| `bollinger bands final-entry at lowerbb sl1.5.ipynb`         | Entry at **Lower Bollinger Band** with a stop-loss of **1.5× volatility**. |
| `bollinger bands final-entry at lowerbb sl1.5 notrail.ipynb` | Same as above, but without a trailing stop.                                |
| `bollinger bands final-entry at lowerbb sl1.5 trail.ipynb`   | Same entry logic with a **trailing stop-loss**.                            |
| `bollinger bands final-sl2.5.ipynb`                          | Variation with a wider stop-loss of **2.5× volatility**.                   |
| `reversebollingerband.ipynb`                                 | A **mean-reversion strategy**, betting on reversals at the bands.          |

---

## ⚙️ Features

* Different Bollinger Band–based strategies with minor variations.
* Fixed and trailing stop-loss implementations.
* Backtesting framework for trade evaluation.
* Equity curve and PnL visualization.
* Comparison of stop-loss multipliers and strategy performance.

---

## 📊 Strategy Variations

* **Lower Band Entry Strategy:** Buy at the lower band with stop-loss variations (1.5×, 2.5×).
* **Trailing vs Non-Trailing Stops:** Compare dynamic vs fixed exits.
* **Reversal Strategy:** Enter trades expecting mean-reversion when price touches bands.

---

## 🔮 Future Enhancements

* Add parameter optimization (grid/random search).
* Multi-asset testing (stocks, forex, crypto).
* Advanced position sizing & portfolio-level risk management.
* Integration with broker APIs for live/paper trading.

---

