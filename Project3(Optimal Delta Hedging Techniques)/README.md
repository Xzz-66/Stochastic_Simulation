# Project 3: Option Pricing and Delta Hedging

This project studies European call option pricing and delta hedging under Black–Scholes and several more realistic extensions.

## Main File

- `Project3.ipynb`

## Overview

The project starts from the classical Black–Scholes framework and then studies how pricing and hedging change when market frictions or model misspecification are introduced.

The main components are:

- Black–Scholes pricing of a European call
- Monte Carlo pricing under geometric Brownian motion
- variance reduction with antithetic sampling
- discrete-time delta hedging
- execution delays modeled with an M/M/1 queue
- jump–diffusion simulation
- Markov-switching volatility simulation

## Methods

The notebook uses:

- Black–Scholes formulas
- Monte Carlo simulation
- antithetic variates
- statistical testing for variance reduction
- simulated hedging experiments
- queue-based delay modeling
- alternative stochastic price models

## Questions explored

- How closely does Monte Carlo pricing match the Black–Scholes benchmark?
- Does antithetic sampling significantly reduce variance?
- How large are hedging errors under discrete rebalancing?
- How do execution delays affect hedge performance?
- What happens when the true stock dynamics include jumps or volatility regimes?

## How to run

Open the notebook and run all cells:

```bash
pip install numpy scipy pandas matplotlib seaborn yfinance
jupyter notebook
