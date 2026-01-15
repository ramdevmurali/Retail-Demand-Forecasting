 Due to commercial sensitivity (Co-op Data) and academic IP restrictions, the source code for this project cannot be shared publicly. This repository contains the comprehensive technical report detailing the methodology, mathematical framework, and results.


# Retail Demand Forecasting for In-Store Bakeries
**Optimization of inventory for 12 supermarket locations using Poisson GLMs and ARIMA.**

![Main Forecast Chart](link_to_screenshot.png)

##  Executive Summary
Developed a predictive modeling system to forecast daily demand for bakery products, addressing the trade-off between waste (over-supply) and lost revenue (under-supply).

##  Methodology
- **Data:** 50,000+ sales records across 12 stores (May 2021 - Aug 2022).
- **Models Benchmarked:**
  - **Poisson GLMs:** Used for counting non-negative integer sales data.
  - **XGBoost:** Captured non-linear relationships (weather, holidays).
  - **ARIMA:** Best performer for capturing seasonality.
- **Key Findings:** The ARIMA model achieved the lowest RMSE (2.08), significantly outperforming baseline heuristics.

## 📄 Full Analysis
[Download the Full Technical Report](Co-Op forcasting.pdf)
