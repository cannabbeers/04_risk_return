
# Module 4 Challenge - UCB FinTech Investing Platform

## User Story and Acceptance Criteria

### `UCB Fintech Capital Advisors NPO` is the 'one-stop shop' online investment solution for retirement investment decions! 

We spared absolutely every expense possible to create this Algorithmic Analysis Dynamo on the cheap with the magic of Financial Technology! 

Since your risk profile indicated that you want the biggest bang for your buck without just 'rolling the dice'...

**the only 'rolling' going on here is calculation of "rolling 21 and 60 day Standard Deviations" and our calculations and visualizations cannot be beat!**

Our bottom rate fees are from the 'Economies of Scope' we gain by using expert crafted code to flush out the most important risk metrics to compare.  

This code will show you how we decide what qualifies as sound, strategic investing by walking through the analysis in stages  our recommendations for fund selection and you'll be sending out postcards soon from your early retirement vacation tour around the world! 

   ### Analyze the Risk - with `returns_daily_df = portfolio_df.pct_change()` from `NumPy` and `std` (standard deviation), from `pandas`
   ### Analyze the Risk-Return Profile - `matplotlib` visualizations of DataFrames built with assistance from `NumPy`and `pandas`
   ### Diversify the Portfolio - `var`,`mean`, and `cov` from `pandas` team up with `matplotlib.pyplot` to flush out the best investments

---
 
### Links to [`Special Text Symbols`](https://symbolsdb.com/text-symbols) for Mathematical Equations Below

+ [Σ uppercase Sigma for 'Summation'](https://usefulshortcuts.com/alt-codes/greek-alt-codes.php) 
+ [𝜎 lowercase sigma for 'Standard Deviation'](https://symbolsdb.com/standard-deviation-symbol)
+ [̄x = Mean](https://symbolsdb.com/mean-symbol)
+ [ß](https://www.freecodecamp.org/news/alt-codes-special-characters-keyboard-symbols-windows-list/)
+ [÷ division](https://www.alt-codes.net///)
+ [× muliplication](https://usefulshortcuts.com/alt-codes/maths-alt-codes.php)
+ [² 'squared' or 'power' of 2](https://theasciicode.com.ar/ascii-table-characters.pdf)
+ [√ 'square root](https://superuser.com/questions/345543/what-is-the-ascii-altnumber-for-the-square-root-symbol-%E2%88%9A-in-windows)     

### We will now walk you through the quantitative analysis used to arrive at our reccomendations based on: 

+ Performance - code calculates the percentage change in NAV prices to determine the returns of each portfolio and the S&P 500

+ Volatility - box plots show quick visualization of the fluctuating NAV - higher volatility equates to higher risk

+ Risk - calculate and reorder each fund and the S&P 500 in order to show lowest to highest risk fund

+ Risk-return profile - formulas calculated for comparison: 
        (Annual Average Return) = (mean of Daily Returns) × (trading days in year)
        (Annualized Standard Deviation) = (Standard Deviation) × (Square Root of 'Trading Days in a Year')
        Sharpe Ratio = (Annual Average Return) ÷ (Annualized Standard Deviation) <-- **measure of risk-adjusted return**

+ Portfolio Diversification - calculate the beta:  

    **Beta = (Covariance of Portfolio) ÷ (Variance of 'S&P' 500)**

        Covariance = Σ [(X - X̄) × (Y - Ȳ)] ÷ (n - 1)
        Variance = Σ (X - X̄)² ÷ (n - 1)
       
### Key `Risk Management Metrics` to be calculated: 

1) [Daily Returns](https://towardsdatascience.com/calculate-and-plot-s-p-500-daily-returns-2ce359e014d6)
2) [Standard Deviation](https://www.investopedia.com/terms/s/standarddeviation.asp)
3) [Sharpe Ratios](https://en.wikipedia.org/wiki/Sharpe_ratio)
4) [Beta](https://en.wikipedia.org/wiki/Beta_(finance))

---

## Code References: 

+ [**linestyles:**   used here in first visualization in'Analyze the Performance' section](https://matplotlib.org/stable/gallery/lines_bars_and_markers/linestyles.html) 
+ [**colormaps:**   used mainly in the 'Analyze the Performance' section](https://matplotlib.org/stable/gallery/color/colormap_reference.html)
+ [**legend:**   used throughout notebook](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.legend.html)
+ [**bar plots:**   used later in 'Analyze the Risk-Return Profile' section](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.figure.html)
+ [**matplotlib: How to easily format y value as percent [%]**   used throughout notebook](https://techoverflow.net/2022/01/30/matplotlib-how-to-easily-format-y-value-as-percent/)
+ [GitHub for 'matplotlib' - **'.ticker'**](https://github.com/matplotlib/matplotlib/blob/v3.7.1/lib/matplotlib/ticker.py#L1476-L1583)
+ [**matplotlib pyplot tutorial**](https://matplotlib.org/stable/tutorials/introductory/pyplot.html)


## Extra Detailed Explainations and Visualizations Included:

Inside the notebook `risk_return_analysis.ipynb` we have answered all your questions and an extra bonus.  There are additional tools implemented from previous lessons to "ZOOM-in" on segments of the timeline to better visualize proof of the reccomendations and answers to challenge questions.  
`.loc` and `.plot` working together again to make sure you can see our focused attention to analyzing the perfect retirement plan for you today! 

---
## Technologies:

The code is written to run in the 'dev' environment we set up in Python version 3.7.1, (now running python version 3.10.9.final.0) on a JupyterLab Notebook (version 3.4.4).

+ Pandas
+ NumPy
+ Matplotlib


## Installation Guide:

Required Libraries - you can check if you have them in your environment quickly once you `dev` environment is activated:

    $ conda list pandas
    $ conda list numpy
    $ conda list matplotlib
    
If any were missing, just call them in with ease with a `pip install`

    $ pip install matplotlib
    $ pip install numpy
    $ pip install pandas
    
## Usage: 

In GitHub, navigate to my repo called `4_quantitative_risk_analysis_rolling_beta`

Open your Terminal or GitBash window

Create a folder using `mkdir` and `clone` the repo in your new directory

Activate your 'dev' environment for python 3.7

Enter `git pull` to import and then launch `Jupyter Lab` from Terminal/Git Bash prompt

Open the jupyter lab notebook: `risk_return_analysis.ipynb` & run the code from the top

---

## Contributors:

Mark Beers: 
[Linked In](https://www.linkedin.com/in/markwbeers/)

---

## License:

MIT License: A short and simple permissive license with conditions only requiring preservation of copyright and license notices. Licensed works, modifications, and larger works may be distributed under different terms and without source code.
