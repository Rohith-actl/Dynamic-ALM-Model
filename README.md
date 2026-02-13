# Dynamic-ALM-Model
This project implements a multi-year stochastic Asset–Liability Management (ALM) framework in R to project assets, liabilities, surplus, and solvency metrics under uncertainty.

***Note: use "knit with parameters" to modify inputs.

The model integrates:

Stochastic asset returns (equities, bonds, cash)

Stochastic liability cash flows (frequency–severity structure)

Correlation between asset and liability risk drivers

Multi-year surplus evolution

Capital adequacy and insolvency probability analysis

Key Features

10–20 year projection horizon

Monte Carlo simulation engine

Dynamic portfolio rebalancing

Correlated asset–liability modelling

Surplus distribution tracking over time

VaR / TVaR at multiple confidence levels

Sensitivity analysis (volatility, correlation, inflation)

Structural stress testing (market crash, inflation shock, catastrophe year)

Optional extensions include:

Copula-based dependency modelling

Yield curve modelling (Vasicek-style dynamics)

Risk-based capital attribution

Portfolio optimisation under surplus constraints

Methodology

Equities: Geometric Brownian Motion

Bonds: Duration-based price sensitivity with stochastic rate shifts

Liabilities: Poisson–Lognormal claim structure

Aggregation: Correlated simulation

Surplus: Assets – Liabilities per simulation path

Risk metrics: VaR, TVaR, probability of ruin

Purpose

This model demonstrates enterprise-level actuarial thinking in:

Strategic asset allocation

Capital adequacy assessment

Risk-return optimisation

Stress testing and ORSA-style scenario analysis

It reflects principles aligned with:

Solvency II ORSA frameworks

Australian Prudential Regulation Authority ICAAP standards

Economic capital modelling in insurance and risk management

This project is intended for educational and demonstration purposes.
