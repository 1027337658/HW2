# ------------------------------
# Overview
# ------------------------------
# This repository demonstrates a simple Bayesian Beta-Binomial workflow. 
# It includes three main questions (Q1, Q2, Q3):
#
# 1) Q1: Posterior derivation (Beta(9,15)) from a Beta(2,2) prior and 7 successes out of 20 Bernoulli trials. 
#        Also computes the posterior mean.
#
# 2) Q2: Visualizes the Beta(2,2) prior vs. the Beta(9,15) posterior in a single plot.
# 
# 3) Q3: Uses the posterior Beta(9,15) to generate posterior predictive simulations for future Bernoulli trials,
#        plots the histogram of simulated success counts.

# ------------------------------
# Requirements
# ------------------------------
# Python 3.8+
# NumPy
# Matplotlib
# SciPy

# ------------------------------
# Summary
# ------------------------------
# - Q1 Posterior: Beta(9,15), Posterior Mean ≈ 0.375
# - Q2 Plot: Beta(2,2) vs. Beta(9,15)
# - Q3 Posterior Predictive: ~37-38 successes on average out of 100 future trials
