# Order-Optimal Baselines for Noise-Limited Model Selection

Code for the paper "Order-Optimal Baselines for Noise-Limited Model Selection".

The repository contains two Jupyter notebooks. The first reproduces Figure 1 and validates the iterated-means predictor dynamics: it runs the greedy residual-reduction procedure on standard normal samples and verifies the n^{-1/2} RMSE decay rate, the shape statistic lower bound, and the corridor condition. The second reproduces Figure 2 and implements the MDL learnability threshold experiment: it fits a sparse Legendre regression candidate against a log-depth iterated-means baseline across a sweep of noise levels, computes description lengths, and estimates the adaptive noise threshold.

## Requirements

numpy, scipy, matplotlib, scikit-learn, pandas

## Usage

Run each notebook from top to bottom. Figures are saved to figs/ as PDF and PNG. No external data required; all experiments use synthetically generated data.
