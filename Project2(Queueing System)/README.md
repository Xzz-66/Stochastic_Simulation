# Project 2: Airport Queue Simulation

This project models a single airport security screening lane using discrete-event simulation.

## Main File

- `Project2.ipynb`

## Overview

The project uses passenger traffic data to estimate the arrival rate for a representative lane during September, then simulates queueing behavior under different operating conditions.

The main tasks are:

- estimate the arrival rate from airport passenger data
- build a discrete-event simulator for one screening lane
- validate the simulator against the Pollaczek–Khintchine formula in a stable M/G/1 setting
- compare operational interventions with repeated simulation
- use hypothesis testing to evaluate whether interventions improve waiting time

## Scenarios

The project compares:

- **Baseline:** one server, current variability
- **Option A:** two servers
- **Option B:** one server with reduced service-time variability

## Methods

The notebook uses:

- discrete-event simulation
- Poisson arrivals
- truncated normal service times
- repeated replications
- confidence intervals and hypothesis testing
- queueing-theory validation

## Questions explored

- Does the simulator match theoretical waiting-time results in a stable test case?
- How severe is waiting time under the estimated peak-month arrival rate?
- Is adding a second server more effective than reducing service-time variability?
- Which intervention should be recommended?

## How to run

Open the notebook and run all cells:

```bash
pip install numpy scipy pandas matplotlib seaborn simpy
jupyter notebook
