# Trader Performance in Relation to Market Sentiment Analysis

## Goal

This research examines the influence of Bitcoin market sentiment (Fear/Greed Index) on trader actions and results on Hyperliquid. The objective is to recognize behavior patterns that depend on the regime and derive actionable trading insights.

---

# Methodological Approach

1) Both datasets were cleaned and standardized.

2) Adjusted timestamps and synchronized data on a daily basis.

3) Combined trade-level information with daily sentiment categorization.

4) Developed performance indicators:
- Trade-level profit and loss
- Daily profit and loss for each account
- Victory percentage 
- Frequency of trades
- Mean transaction volume

5) Divided traders into:
- Elevated vs Reduced Activity
- Big vs Tiny Dimensions
- Elevated vs Diminished Volatility (Steadiness)

6) Daily aggregation was utilized for thorough performance evaluation.

---

# Main Insights

## 1) Sentiment Significantly Influences Trading Activity

- Trade frequency rises almost 6 times during Extreme Fear compared to Greed.
- Traders utilize bigger average trade sizes in Fear regimes.
- Panic situations result in excessive trading and heightened capital risk.

## 2) Performance Varies Among Regimes

- Win rates reach their highest point during Extreme Greed (~46%).
- Nonetheless, the peak average daily PnL takes place during Fear, suggesting a smaller number of more significant profitable trades.
- The variability of returns is greatest during periods of Fear and Greed.

This indicates that sentiment increases the variability of payoffs.

## 3) Segmentation Based on Volatility Unveils Convexity

### Traders focusing on high volatility:

- Produce considerably greater average daily profit and loss.
- Show reduced win rates yet significantly greater profits.
- Performance surges during Fear periods.

### Low Volatility investors:

- Sustain elevated success rates.
- Create reduced yet more consistent gains.
- Show protective traits.

Traders who engage in high volatility depend on rare significant profits, whereas those who focus on low volatility prefer steadiness.

---

# Behavioral Analysis

- Fear-driven systems lead to increased volatility.
- Assertive traders gain from curved payoff arrangements.
- Defensive investors focus on protecting their capital.
- Intense Fear leads to excessive trading actions.

---

# Suggestions for Strategy

## Tactic 1 — Capital Allocation Based on Regime

In times of Fear regimes, invest more in High-Volatility traders, since they seize greater benefits from volatility increases.  
Minimize exposure in situations of Extreme Fear if volatility surpasses risk tolerance.

## Strategy 2 — Sentiment-Aware Risk Control

When sentiment shifts from Neutral/Greed to Fear:
- Reduce position size for High-Activity traders.
- Increase selectivity and risk filters.
- This mitigates panic-driven overtrading losses.

---

# How to Run

1) Install the required libraries:

```
pip install pandas numpy matplotlib seaborn scipy
```

2) Ensure the following files are present in the project directory:
- analysis.ipynb
- fear_greed_index.csv
- historical_data.csv
- requirements.txt

3) Open and run the notebook:

```
analysis.ipynb
```

Run all cells from top to bottom to reproduce the full analysis.

---

# Conclusion

- Market sentiment significantly influences trader behavior, return dispersion, and risk exposure.
- Fear regimes amplify opportunity for aggressive traders, while disciplined traders maintain steadier outcomes across regimes.
- Understanding sentiment-dependent behavior enables more adaptive capital allocation and risk management.
