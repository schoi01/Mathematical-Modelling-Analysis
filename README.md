# Mathematical-Modelling-Analysis

This repository contains three distinct modeling and analysis projects conducted as part of course assignments at the University of British Columbia. Each project explores different modeling techniques—differential equations, Monte Carlo simulations, and linear regression—applied to real-world data scenarios.

## Overview
**1. [Greenhouse Gas Concentration Modelling](https://github.com/schoi01/Mathematical-Modelling-Analysis/tree/main/greenhouse-gas-model)**

This project constructs a mathematical model to predict the atmospheric concentration of four greenhouse gases ($CO_2$, $CH_4$, $N_2O$, and $H_2O$) over time, accounting for various emission sources and chemical breakdown processes.
- Methodology: The project utilizes Ordinary Differential Equations (ODEs) and a nondimensionalization procedure.
- Key Findings: The model demonstrates how the breakdown of methane ($CH_4$) in the presence of oxygen ($O_2$) leads to an increase in $CO_2$ and $H_2O$ concentrations. The analysis confirms that methane and nitrous oxide reach steady states, while water vapour and carbon dioxide show linearly increasing trends.

**2. [Café Income and Customer Frequency Simulation](https://github.com/schoi01/Mathematical-Modelling-Analysis/tree/main/loafe-cafe-income)**

This project models the total annual income for "Loafe Café" by simulating daily customer frequency based on weather variables: temperature, precipitation, and humidity.
- Methodology: The approach employs Monte Carlo simulations and Gaussian Kernel Density Estimation (KDE) to model weather-dependent customer behaviour.
- Key Findings: The model projects a stable, approximately normal distribution of annual customer volume, with a mean of approximately $95,000$ customers per year. Annual income projections were calculated based on fixed average spending scenarios of $10, $15, and $20 per customer.

**3. [Sleep Duration Linear Regression Model](https://github.com/schoi01/Mathematical-Modelling-Analysis/tree/main/sleep-quality-model)**

This project builds a linear regression model to predict the total number of hours slept based on three predictors: physical activity, stress level, and quality of sleep.
- Methodology: The study uses Ordinary Least Squares (OLS) regression. It further improves the model by applying a squared transformation to the "Stress" and "Quality" variables to better capture nonlinear relationships.
- Key Findings: The transformation resulted in a higher adjusted $R^2$ (increasing from $0.783$ to $0.799$) and a substantial reduction in the condition number, indicating improved fit and reduced multicollinearity.

## Technical Stack
All analyses were performed using Python with the following core libraries:
- Data Analysis: ``pandas``, ``numpy``, ``statsmodels``
- Numerical Methods: ``scipy`` (integrate, stats)
- Visualization: ``matplotlib.pyplot``

## Repository Structure
Each assignment directory contains:
- ``Modelling Assignment X.ipynb`` & ``Modelling Assignment X.pdf``: Detailed project reports containing problem statements, assumptions, mathematical formulations, and results.
- Relevant data files.
