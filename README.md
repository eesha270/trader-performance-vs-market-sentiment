![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

# trader-performance-vs-market-sentiment
Exploratory analysis and trader segmentation to study Fear vs Greed market sentiment effects on trading performance.

# Dataset
1. Bitcoin Fear & Greed Index
2. Historical Hyperliquid Trader Data

# Strategy Recommendations
1. Reduce leverage or trade frequency during Fear periods to avoid volatility-driven losses.
2. Allow higher activity during Greed phases, especially for historically profitable trader segments.

# Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

# How to Run
pip install -r requirements.txt

Open the notebook and run all cells sequentially.

# Insights Summary
# Objective

This project analyzed whether Bitcoin market sentiment (Fear vs Greed) influences trader performance and behavior using Hyperliquid trading data combined with the Fear & Greed Index.

# Methodology

The datasets were cleaned and aligned at daily granularity by converting timestamps from unix formats into consistent dates. Trading metrics such as closed PnL, trade frequency, trade size, and directional behavior were analyzed across sentiment regimes. Traders were further segmented using clustering based on profitability, trade size, and activity levels.

# Key Findings

1. Higher profitability during Greed periods:
The average trader's PnL was significantly higher during Greed phases than during Fear phases, suggesting that bullish market conditions provide stronger momentum and clearer trading opportunities.

2. Fear periods show increased trading activity but lower efficiency:
Trade-frequency distributions indicate that traders trade more aggressively during Fear periods, yet average profitability declines. This suggests reactive or panic-driven trading behavior.

3. Risk dispersion increases during Fear:
Trade-size distributions show larger outliers during Fear phases, indicating higher variability in risk-taking and possible forced repositioning during volatile markets.

4. Behavioral trader segments exist:
Clustering analysis revealed distinct trader groups, including high-activity aggressive traders and more consistent moderate-risk traders, indicating that strategy performance varies across behavioral profiles.

# Actionable Strategy Ideas

1. Risk Adjustment by Sentiment: Reduce leverage and position size during Fear periods to avoid volatility-driven losses; allow normal or higher risk exposure during Greed periods.

2. Activity Control Rule: Limit trade frequency during Fear phases to avoid overtrading and focus on high-confidence setups.

# Conclusion

Market sentiment meaningfully influences trader behavior and profitability. Incorporating sentiment-aware risk management and behavior-based segmentation can improve trading decision-making and strategy robustness.
