
# Module 4 Challenge - UCB FinTech Investing Platform

## User Story and Acceptance Criteria

### `UCB Fintech Capital Advisors NPO` is the 'one-stop shop' online investment solution for retirement investment decions! 

We spared absolutely every expense possible to create this Algorithmic Analysis Dynamo on the cheap with the magic of Financial Technology! 

Since your risk profile indicated that you want the biggest bang for your buck without just 'rolling the dice'...

**the only 'rolling' going on here is calculation of "rolling 21 and 60 day Standard Deviations" and our calculations and visualizations cannot be beat!**

Our bottom rate fees are from the 'Economies of Scope' we gain by using expert crafted code to flush out the most important risk metrics to compare.

## We will now walk you through the quantitative analysis used to arrive at our reccomendations based on: 

+ Performance
+ Volatility
+ Risk
+ Risk-return profile
+ Portfolio Diversification

## Key `Risk Management Metrics` to be calculated: 

1) Daily Returns
2) Standard Deviations
3) Sharpe Ratios
4) Betas

## Detailed Explainations and Visualizations Included:

Inside the notebook `risk_return_analysis.ipynb` there are additional tools implemented from previous lessons to "ZOOM-in" on segments of the timeline to better visualize proof of the reccomendations and answers to challenge questions.

## Technologies

The code is written to run in the 'dev' environment we set up in Python version 3.7.1, (now running python version 3.10.9.final.0) on a JupyterLab Notebook (version 3.4.4).

+ Pandas
+ NumPy
+ Matplotlib

## Code References: 

+ [**linestyles:**   used here in first visualization in'Analyze the Performance' section](https://matplotlib.org/stable/gallery/lines_bars_and_markers/linestyles.html) 
+ [**colormaps:**   used mainly in the 'Analyze the Performance' section](https://matplotlib.org/stable/gallery/color/colormap_reference.html)
+ [**legend:**   used throughout notebook](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.legend.html)
+ [**bar plots:**   used later in 'Analyze the Risk-Return Profile' section](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.figure.html)
+ [**matplotlib: How to easily format y value as percent [%]**   used throughout notebook](https://techoverflow.net/2022/01/30/matplotlib-how-to-easily-format-y-value-as-percent/)
+ [GitHub for 'matplotlib' - **'.ticker'**](https://github.com/matplotlib/matplotlib/blob/v3.7.1/lib/matplotlib/ticker.py#L1476-L1583)

## Installation Guide

Required Libraries - you can check if you have them in your environment quickly once you `dev` environment is activated:

    $ conda list pandas
    $ conda list numpy
    $ conda list matplotlib
    
If any were missing, just call them in with ease with a `pip install`

    $ pip install matplotlib


