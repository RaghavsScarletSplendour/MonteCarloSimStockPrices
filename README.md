# Monte Carlo Stock Price Simulation

## Project Description

This project involves simulating stock price movements using the Monte Carlo method. It aims to provide an understanding of potential future movements of a stock's price based on historical data, thereby assisting in investment decision-making.

## Prerequisites

This project requires a basic understanding of Python programming and statistics. Familiarity with financial markets is helpful but not necessary. Ensure you have Python and the necessary libraries installed before starting.

## Youtube Tutorial
<img width="251" alt="Screenshot 2024-03-21 at 13 28 21" src="https://github.com/RaghavsScarletSplendour/MonteCarloSimStockPrices/assets/72269666/f2cf2c45-ef13-4905-8ccd-ff89b65e5731">



[![YouTube Channel](https://img.shields.io/badge/YouTube-Subscribe-red?logo=youtube)](https://www.youtube.com/channel/yourchannelid)


## Getting Started

To dive into the world of stock price simulation with Monte Carlo methods, clone this repository and follow the interactive Jupyter Notebook:

```bash
git clone https://github.com/RaghavsScarletSplendour/MonteCarloSimStockPrices.git
cd MonteCarloSimStockPrices
jupyter notebook
```
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

### Backtesting Results

The expected price for 2 days later is: 138.75097515539002

The 95% confidence interval for the price 2 days later is: (130.7107075477952, 146.91774464512181)

The 98% confidence interval for the price 2 days later is: (129.26542805865614, 148.45331385834814)

The actual closing price for Google on the 29th of Feburary was: 138.08

## Author

Raghav Bajoria
