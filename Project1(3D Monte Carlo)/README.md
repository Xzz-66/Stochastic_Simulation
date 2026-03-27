# Project 1: Monte Carlo Geometry

This project studies the intersection volume of a sphere and a torus using Monte Carlo integration.

## Main File

- `Project1.ipynb`

## Overview

The project considers a 3D setting with a sphere and a torus and estimates their intersection volume under several scenarios.

The main tasks are:

- estimate the intersection volume for two centered sphere–torus cases
- compare estimates under uniform random sampling
- replace random sampling with a deterministic logistic-map sequence
- study an off-center torus shifted along the z-axis
- test a mixed sampling idea using a large box and a smaller local box

## Methods

The notebook uses:

- Monte Carlo integration
- repeated simulation for estimate variability
- bounding-box sampling
- deterministic logistic-map sampling
- graphical cross-sections for illustration

## Questions explored

- How does the estimated intersection volume differ across the two parameter settings?
- How stable are the Monte Carlo estimates across repeated runs?
- Does a deterministic sequence behave like valid Monte Carlo sampling?
- Does a mixture proposal help when the torus is shifted away from the origin?

## How to run

Open the notebook and run all cells:

```bash
pip install numpy scipy matplotlib
jupyter notebook
