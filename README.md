# Sales Forecasting — Store 1, Item 1

**Goal:** Forecast next 12 months of sales using historical daily sales data (2013-2017).

**Method:** 
- Aggregated daily sales to monthly totals
- Applied Holt-Winters Exponential Smoothing (additive trend + additive seasonality, 12-month cycle)
- Held out last 12 months as test set to validate accuracy

**Result:** 5.52% MAPE (Mean Absolute Percentage Error) — forecast closely tracked actual sales trend and seasonal pattern.

**Tools:** Python, pandas, statsmodels, matplotlib
https://www.loom.com/share/e028aef169e2438399ea4366c3e6406e
