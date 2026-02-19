# Trader Performance vs Market Sentiment Analysis

## Objective

This project analyzes the relationship between Bitcoin market sentiment (Fear vs Greed) and trader behavior on Hyperliquid. The goal is to understand how sentiment affects trader performance and derive actionable trading strategies.

---

## Dataset

* Bitcoin Market Sentiment (Fear/Greed Index)
* Historical Trader Data (Hyperliquid)

---

## Methodology

1. Data cleaning and preprocessing
2. Timestamp conversion and daily alignment
3. Feature engineering:

   * Daily PnL per trader
   * Trade frequency
   * Average position size
   * Win rate
   * Risk proxy (position size)
4. Sentiment-based performance comparison
5. Trader segmentation analysis
6. Strategy recommendation

---

## Key Insights

* Trader performance varies across market sentiment regimes.
* Traders increase risk exposure during Greed periods.
* High-risk traders show higher volatility in returns.
* Frequent traders show more consistent performance.

---

## Strategy Recommendations

* Reduce risk exposure during Fear periods.
* Increase trading activity during Greed sentiment.
* Use trader segmentation for adaptive strategies.

---

## How to Run

### Install dependencies

```
pip install -r requirements.txt
```

### Run notebook

```
jupyter notebook Assignment.ipynb
```

---

## Output

Charts and analysis results are available in the `outputs/` folder.
