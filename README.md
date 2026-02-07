# Black Scholes Option Pricing with Real Market Data

## Overview
This project implements the Black–Scholes option pricing model and applies it to real equity market data. Using historical stock prices, the project estimates volatility, prices European call options, computes option Greeks, and calibrates implied volatility via numerical methods.
The goal is to bridge theoretical derivatives pricing models with practical financial engineering implementation.

## Key Components
Downloaded real stock price data using Yahoo Finance, Estimated historical volatility using log returns, Implemented Black–Scholes pricing for European call options, Computed analytical Greeks (Delta, Gamma, Vega, Theta, Rho), Visualized option price sensitivity to stock price and volatility, Calibrated implied volatility by inverting the Black–Scholes model using numerical root-finding

## Tools and Libraries
Python
NumPy
Pandas
SciPy
Matplotlib
yfinance 

## File Description
`Black_Scholes_Option_Pricing_Model.ipynb`: Full implementation and analysis
