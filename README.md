### Retirement Model README
# Overview
This Retirement Model is designed to project the number of years to retirement based on various financial parameters. It accounts for salary changes due to cost of living adjustments and promotions, and it simulates wealth accumulation over time with a constant savings rate and investment returns. The model also incorporates Monte Carlo simulations to assess the probabilities of different retirement timelines under varying inputs.

# Components
The model is divided into the following sections:

# Setup
Inputs
Salaries
Wealths
Retirement
Results Summary
Sensitivity Analysis
Monte Carlo Simulations
Each section is explained in detail below.

# Setup
This section handles all necessary imports and preliminary configurations required to run the model. Ensure you have the following Python libraries installed:

numpy
pandas
matplotlib
dataclasses

# Monte Carlo Simulations
Monte Carlo simulations evaluate the effect of input variability on the model's outcomes. This involves running multiple iterations with inputs drawn from normal distributions, defined by their means (from the existing inputs) and standard deviations.

# Summary: 
Savings rate seems to have the greatest impact. A one standard deviation (7%) increase in savings rate decreases years to retirement by 3.7 years. Cost of living raises are the least impactful with a one standard deviation increase (0.5%) in cost of living raises only decreasing years to retirement by 0.9 years.
