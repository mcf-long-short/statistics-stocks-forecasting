# Stock returns forecasting

Docs: https://mcf-long-short.github.io/statistics-stocks-forecasting/

## Introduction

The goal of the project is to perform all steps/elements of the empirical analysis with
financial/economic data, with the goal to produce useful forecasts. The project has four essential
phases and several steps within each phase:

1. Data collection and analysis:
2. Building univariate time series model for forecast
3. Building multivariate model for forecast
4. Building volatility model

Stocks which returns we're forecasting is [MSFT](https://finance.yahoo.com/quote/MSFT?p=MSFT&.tsrc=fin-srch). Explanatory
variables (features) we're using are: [S&P500](https://finance.yahoo.com/quote/%5Egspc?ltr=1), [Nasdaq](https://finance.yahoo.com/quote/%5EIXIC/) 
and copetitors like [AAPL](https://finance.yahoo.com/quote/AAPL/), [GOOG](https://finance.yahoo.com/quote/GOOG?p=GOOG&.tsrc=fin-srch), [IBM](https://finance.yahoo.com/quote/IBM/) and [3M](https://finance.yahoo.com/quote/MMM?p=MMM&.tsrc=fin-srch).

This repository represents group project work for course in `Statistics and Financial Data Analysis` for advanced degree [Masters in Computational Finance, Union University](http://mcf.raf.edu.rs/).

### Project phases:

Each of the project phases has detailed description of all the steps, implementation details, intuition for modeling, interpretation of data analysis, modeling, evaluation and statistical test that were performed. Here are the `links for published R notebooks to RPubs`:

- [Data collection](https://rpubs.com/krivi95/783676)
- [Data analysis](https://rpubs.com/krivi95/783678)
- [Building univariate time series model for forecast](https://rpubs.com/krivi95/783506)
- [Building multivariate model for forecast](https://rpubs.com/krivi95/783766)
- [Building volatility model](https://rpubs.com/krivi95/783765)

## Running R markdown notebooks

When you clone the repo you may use [renv](https://rstudio.github.io/renv/articles/renv.html).

To install all the dependencies, run: `renv::init()`.

And when adding new R packages, you can save them in `renv` with `renv::snapshot()`.
