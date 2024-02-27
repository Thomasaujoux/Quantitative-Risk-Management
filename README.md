# Quantitative Risk Management & Risk Forecasting with Extreme Value Theory

This repository contains the coursework submissions for the MATH70110 Quantitative Risk Management module, part of the MSc in Mathematics and Finance at Imperial College London for the academic year 2023–2024. It includes solutions for two assessed pieces of coursework focusing on the statistical analysis and modelling of financial data, as well as risk forecasting using extreme value theory.

## Coursework 1: Quantitative Risk Management

### Overview
The first part of the coursework involves statistical analysis and GARCH modelling of the EURO STOXX 50 stock market index, covering a range of statistical measures, fitting a standard GARCH(1,1) model, and evaluating risk measures for the ProShares Short Dow30 ETF.

### Files
- `QRM-2023-cw1-data-a.csv`: Daily values of the EURO STOXX 50 index.
- `QRM-2023-cw1-data-b.csv`: Daily closing prices of the ProShares Short Dow30 ETF.

### Tasks
1. Statistical analysis of log returns.
2. Empirical ACFs computation.
3. GARCH(1,1) model fitting.
4. Goodness of fit assessment.
5. ARMA(1,1)-GARCH(1,1) model with Student t-distributed innovations.
6. Risk measures computation for the DOG ETF.

## Coursework 2: Risk Forecasting with Extreme Value Theory

### Overview
The second piece of coursework focuses on forecasting the risk of investing in Tesla (TSLA) using daily log-returns data. It involves fitting a GARCH(1,1) model, assessing the fit of a normalised Student t distribution, fitting a Generalised Pareto Distribution (GPD), and computing VaR and ES forecasts under different assumptions.

### Files
- `QRM-2023-cw2-data.csv`: Daily closing prices of Tesla (TSLA).

### Tasks
1. GARCH(1,1) model fitting and analysis.
2. Normalised Student t distribution fitting.
3. Generalised Pareto Distribution (GPD) fitting.
4. VaR and ES forecasts computation and backtesting.


## Dependencies

- Python packages: `numpy`, `pandas`, `matplotlib`, `scipy`, `arch`, `statsmodels`.
- R packages (optional): `rugarch`, `fGarch`.


