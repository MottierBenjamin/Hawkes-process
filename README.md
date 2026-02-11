# The Hawkes Process: Modeling Self-Exciting Events

This repository contains a comprehensive study of the **Hawkes process**, a class of self-exciting point processes used to model phenomena where past events increase the likelihood of future occurrences.

The core of this project is the Jupyter Notebook: `Hawkes_process.ipynb`.

## Project Overview

The project bridges theoretical foundations with practical implementation, demonstrating how the Hawkes process can be used for modeling clustered events, with a primary focus on **quantitative finance** (modeling order flow in High-Frequency Trading) and **seismology** (modeling earthquake aftershocks).

This notebook is ideal for demonstrating proficiency in stochastic modeling, statistical inference, and mathematical derivation.

## Notebook Structure (`Hawkes_process.ipynb`)

The study is structured into three logical parts for clear understanding:

### 1. Motivation & Real-World Context

* **Earthquakes (Omori's Law):** Illustrating how a main shock triggers a temporal clustering of aftershocks.
* **High-Frequency Trading (HFT):** Explaining how large trades or market volatility can trigger a cascade of subsequent trades, leading to event clustering in time series data.

### 2. Theoretical Foundations

* **Formal Definition:** Defining the Hawkes process via its **conditional intensity function** $\lambda(t)$.
* **Key Derivations:** Mathematical derivation of the necessary conditions for **stationarity** and the **unconditional intensity** $\mathbb{E}[\lambda(t)]$.
* **Exponential Kernel:** Focusing on the widely used **exponential decay kernel** $\phi(t) = \alpha e^{-\beta t}$.


## Technical Requirements

To run and reproduce the analysis in the Jupyter Notebook, you will need the following Python libraries:

* `Python 3.x`
* `jupyter` or `jupyterlab`
* `numpy`
* `pandas`
* `matplotlib`
* `HawkesPyLib` (A dedicated library for Hawkes process modeling)

You can install the required packages using pip:

```bash
pip install numpy pandas matplotlib jupyterlab HawkesPyLib
