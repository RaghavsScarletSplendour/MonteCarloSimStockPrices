# Monte Carlo Stock Price Simulation

## Project Description

This project involves simulating stock price movements using the Monte Carlo method. It aims to provide an understanding of potential future movements of a stock's price based on historical data, thereby assisting in investment decision-making.

## What is Monte Carlo?

The Monte Carlo method is a statistical technique that allows for the simulation of a wide range of possible outcomes in a process that cannot easily be predicted due to the intervention of random variables. It is widely used in finance, engineering, and science to model the probability of different outcomes in a process that cannot easily be predicted due to the complexity of the variables involved.

## Visualization

Visualization plays a crucial role in this project, enabling the interpretation of simulated stock price trajectories over time. Through graphical representation, users can visually assess the range of potential future stock prices, which is facilitated by plotting the outcomes of the Monte Carlo simulations.
![image](https://github.com/RaghavsScarletSplendour/MonteCarloSimStockPrices/assets/72269666/9cc287fc-872f-4ca8-bd4d-28be76dc1e10)


## Live Testing

The project also includes a live testing component, where the Monte Carlo simulation was applied to predict the future stock price of Google. For this demonstration, we utilized data from the past four years, aiming to forecast the stock price two days into the future from the 27th of February, 2024, thus targeting the 29th of February, 2024, as our prediction date.

### Methodology

The simulation aimed to forecast the price for the 29th of February, 2024, using the following steps:

Data Extraction: Prices for the end of the second forecasted day were extracted from the simulation results, focusing on the last row of the dataset, as it represents the culmination of the two-day prediction interval.
Statistical Analysis: The 95% confidence interval was calculated to understand the range within which the stock price is expected to lie with a high degree of certainty.
Mean Price Calculation: The mean (expected) price was computed to provide a single value forecast as the most likely outcome of the simulation.
Results

The simulation produced the following insights for Google stock's price prediction for the 29th of February, 2024:

**Expected Price: The expected stock price two days later was calculated to be approximately $138.09.**
95% Confidence Interval: The price is expected to fall within $132.39 and $143.74 with a 95% level of confidence.
Additional intervals and a refined forecast suggested slight variations in expected price and confidence intervals, highlighting the model's sensitivity to statistical parameters.
Backtesting Results

Backtesting was intended to validate the simulation model against the actual market performance. However, the specific outcome of this backtesting process, including the actual closing price of Google stock on the 29th of February, and the comparison of predicted versus actual values, remains to be detailed. This section will underscore the model's accuracy and reliability in real-world scenarios, offering critical insights into its efficacy for stock price prediction.

## Author

Raghav Bajoria
