Markdown
# RELATIVE_VALUATION_ENGINE: DR_REDDYS_LABORATORIES

## PROJECT_OVERVIEW
This repository contains a high-fidelity Comparable Company Analysis (CCA) framework used to determine the intrinsic value of Dr. Reddy's Laboratories. The model benchmarks Dr. Reddy's against 9 sectoral peers to identify valuation discrepancies based on current market trading multiples.

## DATA_ARCHITECTURE: PEER_GROUP_METRICS
The model utilizes a comprehensive peer universe to establish sectoral benchmarks. All figures represent the median trading levels for the Indian pharmaceutical sector.

### SECTORAL_BENCHMARKS
- EV/REVENUE_MEDIAN: 4.41x
- EV/EBITDA_MEDIAN: 15.51x
- P/E_RATIO_MEDIAN: 29.24x
- SECTOR_HIGH_PE: 108.18x
- SECTOR_LOW_PE: 10.52x

### TARGET_INPUTS: DR_REDDYS_LABS
- SHARE_PRICE: INR 1,335.00
- SHARES_OUTSTANDING: 83.47 Cr
- REVENUE: INR 34,682 Cr
- EBITDA: INR 9,488 Cr
- NET_INCOME: INR 5,523 Cr
- NET_DEBT: INR 3,394 Cr

---

## VALUATION_SYNTHESIS: IMPLIED_EQUITY_VALUE

The engine calculates the implied share price by applying peer medians to target financials and reconciling for the net debt stack.

### 1. EV/EBITDA_METHODOLOGY (Core Operational Value)
- CALCULATED_EV: INR 1,47,191.94 Cr
- LESS_NET_DEBT: INR 3,393.80 Cr
- IMPLIED_MARKET_CAP: INR 1,43,798.14 Cr
- IMPLIED_SHARE_PRICE: INR 1,722.75

### 2. PRICE_TO_EARNINGS_METHODOLOGY (Equity Value)
- CALCULATED_MARKET_CAP: INR 1,61,483.72 Cr
- IMPLIED_SHARE_PRICE: INR 1,934.63

### 3. EV/REVENUE_METHODOLOGY (Top-Line Value)
- CALCULATED_EV: INR 1,52,986.98 Cr
- IMPLIED_SHARE_PRICE: INR 1,792.18

---

## QUANTIFIABLE_CONCLUSION
- CURRENT_MARKET_PRICE: INR 1,335.00
- FUNDAMENTAL_FLOOR: INR 1,722.75
- VALUATION_DELTA: 29.04% Undervalued (Base Case)
- MAXIMUM_UPSIDE_TARGET: INR 1,934.63 (P/E Basis)

The analysis confirms that Dr. Reddy's Laboratories is trading at a significant discount to its peer group across all major valuation vectors. The company’s current EV/EBITDA of 12.14x is 21.7% lower than the sectoral median of 15.51x, suggesting potential for significant price correction toward the fundamental mean.
