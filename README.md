# README

## Overview

This repository contains code and data files for the analysis and testing of the Lexical Ratio (LR) metric. The repository is organized into three main code files, each serving a specific purpose in showcasing the capabilities of LR, analyzing its relationship with other metrics, and testing its performance on real-world data. For any questions and issues contact Faraz Mohseni at (farazmohseni15@gmail.com)

## Repository Contents


### 1. Relationship Analysis
The `Refression and Correlation" code file assesses how the Lexical Ratio (LR) relates to other three diversification metrics: Markowitz, DR_SD (Diversification Ratio based on Standard Deviation) and DR_VaR (Diversification Ratio based on Value at Risk). This analysis provides insights into how LR compares with and complements these existing metrics.

The `Conditional Relationship Analysis` code file is our conditional non-parametric analysis using the Azadkia-Chaterjee method.
### 2. Robustness testing
use the file `Robsutness analysis` to access the k-fold robustness analysis outlined in the paper.
### 3. Optimization Testing
The `Optimization_testing` code file offers optimization results and out-of-sample testing for various metrics, including LR. This section focuses on applying the LR metric to real-world portfolio data, optimizing the portfolios, and testing their performance against other metrics in an out-of-sample framework.

## Data
Data for the S&P 500 is created using the code in Data set creation. The API key is modified in this code. The file `Data Set Creation` and `Random generator` were used for portfolio creations.
The `news_data.csv` file contains the data used in the analysis. This data includes headlines and news content from 2018 to July 1st, 2024, for S&P 500 along with VIX news. The news data is utilized in the calculation of the Lexical Ratio and other related metrics. It is a large file and can be accessed at: https://drive.google.com/file/d/14L6Hzm68KQ8IrQ0JOrB1Rf8UHbWGSiLN/view?usp=sharing

The ticker list is stored in sp500_tickers.txt.
### Portfolios
The `portfolios` folder contains text files representing different portfolios. These files include ticker symbols for the assets in each portfolio and are used in the simulations and testing conducted in the code files.


## Usage
1. **Relationship Analysis.ipynb**: Use the two relevant files to assess how LR relates to DR_SD and DR_VaR, providing a comparative analysis of these metrics.
2. **Robustness analysis.ipynb**: Use this file to asses the robustness of metric using CV
3. **Real-World Testing.ipynb**: Execute the `Optimization Testing` code file to perform optimization and out-of-sample testing on real-world portfolio data, comparing LR with other metrics.
Make sure the `portfolios` and `news_data` folders are correctly placed in the repository structure for the code files to function properly.
4. **LR Time series.ipynb**: Use this file to create plots of optmized LR values over optimization intervals.
