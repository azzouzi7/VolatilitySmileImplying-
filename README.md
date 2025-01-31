# Volatility Smile Generation using Heston Model

## Description
This project focuses on generating and visualizing the volatility smile using the **Heston Stochastic Volatility Model**. In the Black-Scholes framework, volatility is assumed to be constant, but real market data exhibits different volatilities for options with different strikes. This phenomenon is known as the **volatility smile**.

In this project:
- We calibrate the **Heston model** using real market data.
- We apply the **Fast Fourier Transform (FFT) method** to compute option prices.
- We compute implied volatilities using **Rooting and Minimize Object Function methods**.
- We compare results between the **Black-Scholes** and **Heston** models to better visualize the volatility smile.

## Prerequisites
Ensure you have the following Python libraries installed:

```bash
pip install numpy pandas scipy matplotlib
```

## Installation
1. Clone this repository:

```bash
git clone https://github.com/your-username/volatility-smile-heston.git
cd volatility-smile-heston
```

## Usage
1. Open and run the Jupyter Notebook:

```bash
jupyter notebook Volatility_generation.ipynb
```

2. Follow the notebook steps to:
   - Load market data
   - Calibrate the **Heston model**
   - Compute option prices using **FFT**
   - Extract and visualize the **volatility smile**

## Results
- The implied volatility surface is plotted to compare the **Black-Scholes** and **Heston** models.
- The project demonstrates that the **Heston model** captures the volatility smile more accurately than Black-Scholes.

## Author
Azzouzi7

