StockML
=======

Research using machine learning to pick stocks

## Initial Research

* VIX - Fear Index
* IBM
* BAC - Bank of America
* AGNC - REIT
* GSPC - S&P 500
* VTI - Vanguard Total Stock Market Index

## Instructions

1. Download quote files from yahoo (1/2/1990 - Present) Note that training set will begin on 1/2/1992 with a 20 yr window
2. Rename file to ticker.csv
3. python parse.py ticker.csv

## Notes
* TradeCost = 6.95 / trade (+ $0.75/option contract in the case of options) Per ShareBuilder
* Profit = Range * NumShares - 2 * TradeCost
* Minimum Number of Shares to Break Event: NumShares = (2 * TradeCost)/Range
* Minimum investment to realize gain: MinInvestment = (2 * TradeCost)/Range * BuyPrice
