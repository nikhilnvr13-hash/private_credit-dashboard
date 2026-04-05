# Private Credit Market Dashboard

## Overview
An automated financial dashboard designed to monitor private credit market conditions using proxies and credit risk indicators.

## Features
- Automated data pipeline using Python
- Integration with Yahoo Finance and FRED API
- Weekly updates using scheduled scripts
- Interactive Tableau dashboard for visulaization

## Data Sources
- Yahoo Finance (HYG, SRLN, BX , APO, ARES, KKR)
- FRED (High Yield Spread)

## Metrics Tracked
-High Yield Spread (credit risk indicator)
- Loan ETF performance
- High Yield Bond ETF (HYG)
- Private Credit firms performance

## Tools Used
- Python (pandas, yfinance, fredapi)
- Excel (data storage and intermediate processing)
- Tableau (dashboard visualization)

## How It Works
1.Python script fetches market data
2.Extracts latest weekly values
3.Updates Excel dashboard immediately
4.Tableau reads updated data for visualization

## Author 
Nikhil Venkatareddy
