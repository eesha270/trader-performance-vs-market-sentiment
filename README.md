![Python](https://img.shields.io/badge/Python-3.x-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

# trader-performance-vs-market-sentiment
Exploratory analysis and trader segmentation to study Fear vs Greed market sentiment effects on trading performance.

# Dataset
1. Bitcoin Fear & Greed Index
2. Historical Hyperliquid Trader Data

# Methodology
Cleaned and standardized timestamps from multiple formats (unix seconds & milliseconds)

Merged datasets at daily granularity

Engineered trading metrics:
1. Daily PnL
2. Win rate
3. Average trade size
4. Trade frequency
5. Directional behavior
   
Performed exploratory analysis across sentiment states

Segmented traders using K-Means clustering

# Key Insights
1. Average trader profitability is higher during Greed periods compared to Fear.
2. Fear periods show spikes in trading activity, suggesting reactive or panic-driven behavior.
3. Trade size variability increases during Fear, indicating higher risk dispersion.
4. Trader clustering reveals distinct behavioral groups (aggressive vs consistent traders).

# Strategy Recommendations
1. Reduce leverage or trade frequency during Fear periods to avoid volatility-driven losses.
2. Allow higher activity during Greed phases, especially for historically profitable trader segments.

# Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Google Colab

# How to Run
pip install -r requirements.txt

Open the notebook and run all cells sequentially.
