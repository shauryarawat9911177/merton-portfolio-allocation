# Continuous-Time Portfolio Allocation (Merton Model)

This project implements and evaluates the classical Merton portfolio allocation framework.

The goal is to understand how theoretical continuous-time portfolio optimization behaves under:

- Monte Carlo simulation
- Multi-asset portfolio extension
- Empirical ETF backtesting

## Project Overview

The Merton model provides a closed-form optimal allocation between risky assets and the risk-free asset under CRRA utility.

This project includes:

1. **Monte Carlo validation**
   - Simulates wealth dynamics
   - Verifies the theoretical optimal allocation

2. **Multi-asset extension**
   - Uses covariance matrix formulation
   - Studies diversification effects

3. **Empirical backtest**
   - ETF data from 2015–2025
   - Out-of-sample evaluation
   - Comparison with equal-weight benchmark

## Key Findings

- The unconstrained Merton allocation produces high returns but relies heavily on leverage.
- Removing leverage stabilizes the portfolio while maintaining improved risk-adjusted performance relative to equal-weight portfolios.
- Empirical implementation highlights sensitivity to parameter estimation.

## Repository Structure

```
report/   → full project report  
code/     → Python implementation (Jupyter notebook)  
figures/  → simulation and backtest plots  
```

## Author

Shaurya Rawat
