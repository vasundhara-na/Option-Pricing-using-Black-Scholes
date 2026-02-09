# Option Pricing using Black Scholes 

## Overview
This project implements the Black Scholes option pricing model and applies it to real equity market data. Using the stock prices, the project estimates volatility, prices European call options, computes option Greeks, and calibrates implied volatility via numerical methods.
The goal is to bridge theoretical option pricing models with practical real-market implementation.

## Key Components
- Downloaded real stock price data using Yahoo Finance,
- Estimated volatility using log returns,
- Implemented Black-Scholes pricing for European call options,
- Computed analytical Greeks (Delta, Gamma, Vega, Theta, Rho),
- Visualized option price sensitivity to stock price and volatility,
- Calibrated implied volatility by inverting the Black–Scholes model using numerical root-finding 

## Asset details
Underlying asset: Apple Inc. stock (AAPL)
- Reason: liquid stock, reliable dat, actively traded options

## Tools and Libraries
- Python
- NumPy
- Pandas
- SciPy
- Matplotlib
- yfinance       

## Option Greeks (Risk Sensitivities)
- Delta
- Gamma
- Vega
- Theta
- Rho
(Primarily for call options, with put Greeks derived via put–call parity)

## File Description
`Option Pricing using Black Scholes.ipynb`: Full implementation and analysis
