# CAPM-FAMA-MVP

# Mastering Statistical Modeling with R

This repository contains R code and analysis for various statistical modeling concepts and techniques. The code is based on assignments and exercises from a statistics course.

## Files

1. **fama.rmd**: This file contains the code and analysis for the Fama-French Three-Factor Model. It includes fitting the model, calculating returns, and performing hypothesis tests.

2. **GARCH.rmd**: This file focuses on the GARCH (Generalized Autoregressive Conditional Heteroskedasticity) models. It covers GARCH(1,1), GJR-GARCH(1,1), log-likelihood ratio tests, residual analysis, and forecasting with bootstrap prediction intervals.

3. **CAPM.rmd**: This file explores the Capital Asset Pricing Model (CAPM) and its assumptions. It includes hypothesis testing, confidence interval construction, and visualizations related to the CAPM.

## Data

The analysis in these files uses stock data from various companies (AAPL, ABBV, DAL, GOOGL, GM, JPM, and VZ) and the Fama-French Research Data Factors. The data files are not included in this repository but can be obtained from the respective sources.

## Prerequisites

To run the code in these files, you need to have the following R packages installed:

- `xts`
- `zoo`
- `urca`
- `testcorr`
- `rugarch`
- `parallel`
- `anytime`
- `dplyr`

You can install these packages using the following command in R:

