# Matrix-Factorization-for-Time-Series-Forecasting

## Context
In this case study, we will be using the [Electricity Load dataset](https://archive.ics.uci.edu/ml/datasets/ElectricityLoadDiagrams20112014#) from UCI Machine Learning Repository. The dataset describes the 15-minutes load for 370 different clients in kW. Each column represents one client. The dataset has electricity consumption for these 370 houses every 15 mins starting from `2011-01-01`, till `2015-01-01`. Some clients are created after 2011. In these cases, consumption was considered zero.

## Problem statement
We need to build a forecasting model to forecast the electricity load of different clients (i.e., forecasting multiple time series at once) for a certain period in the future.

## About the algorithm
This algorithm is known as `Multivariate Singular Spectrum Analysis (mSSA)`. This is a matrix factorization based method that can help in -
- Time-series forecasting and
- Time series imputation

The python library to use this algorithm is not currently present in PyPi. The code repository is present in this GitHub repository: https://github.com/AbdullahO/mSSA. So we will be using a different way to install the library on your local machine. Below we have provided the steps to follow to install this library.
