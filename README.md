# Risk-Return Simulation

This repository contains simulations exploring risk and return in investment 
outcomes, with a focus on venture capital and private equity.

## Projects

### 1. Realized returns across risk levels

Reproduces the intuition behind Howard Marks' risk-return chart through a 
Monte Carlo simulation. Realized returns are drawn at increasing risk 
levels, with dispersion growing faster than expected returns. The result 
illustrates why picking the right investments matters more at higher levels 
of risk.

File: `risk_return_simulation.ipynb`

### 2. Survivorship bias in risk-return estimation

Extends the simulation to show how survivorship bias distorts the estimated 
relationship between risk and return. Investments below a risk-dependent 
threshold are dropped from the observable sample, mimicking the way failed 
funds and failed deals disappear from track records. Comparing the OLS 
slope on the full sample versus the survivor sample makes the bias visible.

File: `survivorship_bias_simulation.ipynb`

## Tools

Python, numpy, pandas, matplotlib, statsmodels.
