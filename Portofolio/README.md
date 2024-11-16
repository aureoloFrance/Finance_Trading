# Modern Portfolio Theory (MPT)

## Introduction

Modern Portfolio Theory (MPT) is an investment framework designed to optimize the expected return of a portfolio while managing risk. It achieves this by carefully determining the proportions of different assets within a portfolio. 

A **portfolio** is a collection of investments, such as stocks, bonds, commodities, real estate, and more. MPT asserts that the expected return of an investment is directly proportional to the level of risk taken. Therefore, investors should construct their portfolios based on their risk tolerance and investment horizon.

This repository contains Python code to calculate the **expected returns**, **volatility (risk)**, and perform **portfolio optimization** using MPT principles. It includes tools for data acquisition, calculations, visualizations, and performance testing.

---

## Features

1. **Retrieve Historical Data**: 
   - Use the `pandas_datareader` library to fetch historical financial data.
   
2. **Calculate Portfolio Metrics**:
   - Compute daily and annualized **returns**.
   - Create the **covariance matrix** to measure asset correlations.

3. **Optimize Portfolios**:
   - Maximize returns for a given risk level or minimize risk for a given return using **scipy**.

4. **Visualizations**:
   - Plot the **Efficient Frontier**, showcasing optimal risk-return combinations.
   - Highlight the maximum Sharpe ratio portfolio and the minimum volatility portfolio.

5. **Investment Strategy Testing**:
   - Evaluate how different portfolio allocations perform over time.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/ModernPortfolioTheory.git
   cd ModernPortfolioTheory

