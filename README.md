# Retirement Income Monte Carlo Simulation

This project utilizes Monte Carlo simulation to estimate the probability of meeting retirement income goals. It helps investors assess the likelihood that their investment portfolio will generate enough income for retirement.

## Problem Statement

As an investor planning for retirement, it is crucial to understand the probability of your investment portfolio providing enough income during your retirement years. This project aims to estimate the likelihood of meeting or exceeding your desired retirement income based on the performance of your portfolio, inflation rates, and retirement expenses.

## Methodology

1. Generate Random Samples: Random samples are generated for key variables such as stock returns, bond returns, inflation rates, and retirement expenses. These samples are based on assumed mean and standard deviation values for each variable.

2. Perform Simulations: The simulation model calculates the future value of the investment portfolio based on the generated returns and investment strategy. It projects the income generated by the portfolio during retirement, considering withdrawal rates and adjusting for inflation.

3. Estimate Probability of Meeting Goals: The simulations are run multiple times, and the proportion of runs where the projected retirement income meets or exceeds the desired income level is calculated. This provides an estimate of the probability of meeting retirement income goals.

4. Visualize Results: The distribution of retirement incomes is visualized using a histogram. This helps in understanding the spread and likelihood of achieving the desired income level.

## Usage

To run the simulation and analyze the retirement income probabilities:

1. Ensure you have the required libraries installed (numpy, pandas, and matplotlib).

2. Run the `monte_carlo_simulation.ipynb` Jupyter notebook file.

3. The code will generate random samples for the key variables, perform the simulations, estimate the probability of meeting retirement income goals, and display a histogram of retirement incomes.

## Results

The simulation provides insights into the likelihood of meeting or exceeding retirement income goals based on the given assumptions. The estimated probability of meeting the desired income level helps investors make informed decisions and adjustments to their investment strategies and retirement plans.

## Disclaimer

This simulation is based on assumptions and random samples. It is important to note that actual investment performance may vary, and the results should be interpreted with caution. The simulation is intended for educational and informational purposes only and should not be considered as financial advice.
