# Market-Risk-Project-

First, I will present all the files of the project.
- All Dataset.csv are files for the project
- __TAUCH Lukas PERRIN Romuald MARKET RISK.Rmd__ is the program file so program in __RMarkdown__
- [Download and save this file to see the rendering in HTML form](TAUCH-Lukas-PERRIN-Romuald-MARKET-RISK.html)

Here are the __stages__ of the project and the __questions__ we asked ourselves and the __interpretations__ (written in the code)

# VaR 

From the time series of the daily prices of the stock Natixis between January 2015 and December 2016,
provided with the dataset, estimate a historical VaR on price returns at a one-day horizon for a given
probability level (this probability is a parameter which must be changed easily). You must base your
VaR on a non-parametric distribution (Epanechnikov Kernel). 

# Analyse returns using a specif method in the field of the EVT 

- Determine the extremal index using the block or run de-clustering, for the two tails of the
distributions
- Propose an adaptation of the EVT VaR which takes into account the dependence of the returns.

# Model Almgren Chriss

-  Estimate all the parameters of the model of Almgren and Chriss. Is this model well specified?
-  In the framework of Almgren and Chriss, what is your liquidation strategy (we recall that you can
only make transactions once every hour).

# Haar Wavelets and Hurst exponent

- With Haar wavelets and the dataset provided with this tutorial, determine the multiresolution
correlation between all the pairs
- Calculate the Hurst exponent of GBPEUR, SEKEUR, and CADEUR. Determine their annualized
volatility using the daily volatility and Hurst exponents
