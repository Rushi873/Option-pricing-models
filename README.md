# Option Pricing Models Repository

This repository contains several Jupyter Notebook files implementing various financial models and calculations. Below is a detailed overview of each notebook:

## Black_Scholes_Merton_Model.ipynb
This notebook implements the Black-Scholes-Merton model, a widely used formula for pricing European options. It calculates the call and put option prices as well as option Greeks such as delta, gamma, theta, vega, and rho. Understanding these metrics is crucial for option traders to assess risk and potential profitability.

## HestonModel.ipynb
The Heston model is a stochastic volatility model commonly used in finance to capture the dynamics of asset prices. This notebook provides an implementation of the Heston model, which allows for more realistic modeling of volatility compared to the constant volatility assumption in the Black-Scholes model.

## IV_calculation.ipynb
Implied volatility is a key parameter in option pricing models as it represents the market's expectation of future volatility. This notebook utilizes the Newton-Raphson method to calculate implied volatility, enabling traders to gauge market sentiment and assess the relative pricing of options.

## LSTM_model.ipynb
Long Short-Term Memory (LSTM) networks are a type of recurrent neural network (RNN) well-suited for time series forecasting tasks. In this notebook, LSTM networks are applied to forecast stock prices, providing traders and investors with valuable insights into potential future price movements.

## Modified_Black_Scholes.ipynb
The Black-Scholes-Merton model is a foundational options pricing model, but it relies on simplifying assumptions such as no dividend payout and constant risk-free interest rates. This notebook introduces modifications to the Black-Scholes formula to account for dividend payouts and use bond yields as risk-free interest rates, offering a more accurate pricing model for options.

## Monte_Carlo_simulation.ipynb
Monte Carlo simulations are a powerful tool for estimating the value of options and other derivatives by simulating thousands or millions of possible future outcomes. This notebook demonstrates how Monte Carlo simulations can be used to estimate call and put option prices, providing traders with a range of potential outcomes and their probabilities.

### Modified Black Scholes Model
This section elaborates on the modifications made to the Black-Scholes option pricing formula to incorporate dividend payouts and bond yields as risk-free interest rates. By adjusting the formula, the model provides more accurate pricing for options, enhancing decision-making for traders and investors.

### Implied Volatility Calculation
The process of calculating implied volatility using the Newton-Raphson method is explained in detail. Implied volatility reflects the market's expectation of future volatility and plays a crucial role in options pricing. By accurately calculating implied volatility, traders can better assess the relative value of options and make informed trading decisions.

These financial models and calculations serve as valuable tools for pricing options, forecasting stock prices, and gaining insights into market dynamics, empowering traders and investors to make informed decisions.
