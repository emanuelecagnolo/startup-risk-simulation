# Risk-Return Simulation

This project reproduces the intuition behind Howard Marks' risk-return chart 
through a Monte Carlo simulation. Realized returns are drawn at increasing 
risk levels, with dispersion growing faster than expected returns. The 
result illustrates why picking the right investments matters more at higher 
levels of risk.

## Method

Five risk levels are defined. At each level, actual returns are drawn from 
a normal distribution with mean and standard deviation calibrated to reflect 
the risk profile of asset classes ranging from government bonds to venture 
capital. The number of observations decreases with risk to reflect the 
smaller number of deals at higher risk levels.

## Files

- `power_law.ipynb`: full notebook with the simulation and plot.

## Tools

Python, numpy, matplotlib.
