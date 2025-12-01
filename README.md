# Market-Risk-Modelling with Python
# Overview

This repository presents a complete Python-based implementation of core Market Risk Modelling techniques, commonly used in trading, risk management, and quantitative finance.
The project focuses on Value-at-Risk (VaR), Expected Shortfall (ES), historical & parametric risk measurement, and simulation methodologies used by banks and hedge funds.

# Key Objectives

Build a comprehensive framework for market risk measurement.

Implement VaR and ES using multiple industry-standard methods.

Use Python to simulate portfolio risk under different conditions.

Demonstrate capability in statistical modelling, simulation, and quantitative analysis.

# Topics Covered

1. **Value-at-Risk (VaR) Modelling**

Implementation of multiple VaR techniques:

✔ 1. **Historical VaR**

Pure data-driven approach

Uses actual historical returns

No distributional assumptions

✔ 2. **Parametric (Variance–Covariance) VaR**

VaR under assumption of normality

Uses volatility & correlation estimates

Suitable for linear portfolios

✔ 3. **Monte Carlo VaR**

Random sampling from fitted distributions

Simulation of return paths

Captures non-linear risks more accurately

2. **Expected Shortfall (ES) / Conditional VaR**

ES calculation for all VaR methods

Discussion on the Basel III regulatory preference for ES

Tail-risk quantification and stress metrics

3. **Statistical Diagnostics**

Backtesting:

✔ VaR

Model validation and interpretation

4. **Tech Stack**

- Python 3.x

- Pandas for financial time-series

- NumPy for statistical computing

- Matplotlib / Seaborn for risk visualizations

- SciPy / Statsmodels for distribution & tests
