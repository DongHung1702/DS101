# DS101
# Rainfall Prediction for the Next Day  
**Final Project - Weather Forecasting Using Markov Chains, Monte Carlo Simulation, and Naive Bayes Classifier**

## Overview

This project aims to **predict the likelihood of rainfall on the next day** based on historical weather data using three probabilistic methods:
- **Markov Chains**
- **Monte Carlo Simulation**
- **Naive Bayes Classifier**

The project demonstrates how different probabilistic models can be applied to the same prediction task and compares their performance in terms of accuracy and interpretability.

---

## Problem Statement

Given a dataset of past daily weather observations, the objective is to build models that can predict whether it will rain on the following day. The prediction is made using:

- Transition probabilities (Markov Chains)
- Randomized simulations (Monte Carlo)
- Conditional probabilities (Naive Bayes)

---

## Methods

### 1. Markov Chains
- Models the weather as a **finite state machine** (e.g., Rainy, Sunny, Cloudy).
- Uses **transition probabilities** between states to predict the next day.

### 2. Monte Carlo Simulation
- Simulates multiple possible weather scenarios based on observed probabilities.
- Aggregates simulation outcomes to estimate the probability of rainfall.

### 3. Naive Bayes Classifier
- Applies **Bayes’ theorem** assuming feature independence.
- Classifies the next day’s weather based on observed features (e.g., humidity, temperature).

---

## Technologies

- **Language**: Python 3.x
- **Libraries**: NumPy, pandas, scikit-learn, matplotlib (for visualization)

---

