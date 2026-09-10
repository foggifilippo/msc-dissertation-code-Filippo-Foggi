# Value-at-Risk Modelling and Backtesting

Python implementation accompanying the MSc dissertation:

**Value-at-Risk Modelling and Backtesting for a Multi-Asset Banking Portfolio**

The notebook implements pricing, portfolio valuation, VaR estimation and backtesting for a multi-asset portfolio containing fixed-income, interest-rate, commodity, equity and foreign-exchange exposures.

## VaR specifications

The analysis compares 15 VaR specifications across three modelling regimes:

- Static: Historical Simulation, Weighted Historical Simulation, Gaussian and Student-t.
- Moving window: Historical Simulation, Weighted Historical Simulation, Gaussian, Student-t and EWMA.
- Dynamic: GARCH with Gaussian and Student-t innovations combined with parametric, HS and WHS quantile estimation.

Backtesting includes unconditional coverage tests and comparative forecast evaluation using quantile loss and pairwise Diebold-Mariano tests.

## Data

The market data used in the dissertation were provided by Banca Monte dei Paschi di Siena and are confidential. They are therefore not included in this repository.

The notebook cannot be run end to end without the original data or equivalent market data with the required structure.

## Requirements

See `requirements.txt`.