# Nasdaq-100 Portfolio Analysis using Markowitz Portfolio Theory

## Introduction

This project explores the Nasdaq-100 stock index using the Markowitz Portfolio Theory. The Nasdaq-100, comprising 100 of the largest non-financial companies listed on the Nasdaq Stock Market, is analyzed for its risk and return characteristics. The Markowitz Portfolio Theory, a seminal investment strategy developed by Harry Markowitz, is employed to provide insights into portfolio optimization and asset allocation.

## Data Sources

The project utilizes the holdings information of the iShares NASDAQ-100 ETF to identify the companies within the index. Stock price data is downloaded from Yahoo Finance using the yfinance library.

## Analysis Steps

1. **Data Preprocessing:** Filter the Nasdaq-100 companies and download their stock price data.
2. **Calculate Logarithmic Returns:** Compute the logarithmic returns for each holding.
3. **Covariance Matrix Analysis:** Examine the symmetry, invertibility, and positive definiteness of the covariance matrix.
4. **Correlation Analysis:** Investigate strong correlations among holdings.
5. **Diversification Analysis:** Assess the level of diversification in terms of sectorial and country risk.
6. **Portfolio Concentration Analysis:** Analyze the concentration of weights within the portfolio.

## Results and Conclusions

The analysis reveals insights into the Nasdaq-100's risk profile, emphasizing the presence of strong correlations, lack of diversification, and concentration in specific sectors and companies. The conclusion underscores the importance of additional diversification strategies for effective risk management.
