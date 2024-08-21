# Deep-RL-to-optimise-stock-trading-strategy
This project is designed to generate trading signals based on various technical indicators such as EMA (Exponential Moving Average), MACD (Moving Average Convergence Divergence), RSI (Relative Strength Index), and Bollinger Bands. The code reads stock data from a CSV file, calculates the necessary technical indicators, and outputs buy/sell signals based on predefined conditions.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)

## Overview

This project applies technical indicators to stock price data and generates buy/sell signals when certain conditions are met. The signals are based on a combination of EMA crossovers, MACD trends, RSI values, and Bollinger Bands. The output is a CSV file containing the signals.

## Features

- **Technical Indicators**: Includes EMA, MACD, RSI, Bollinger Bands, VWAP, Stochastic, ATR, and Supertrend.
- **Buy/Sell Signals**: Generates signals based on the combination of technical indicators.
- **CSV Output**: Saves the generated signals to a CSV file for further analysis.

## Installation

### Prerequisites

- Python 3.x
- Required Python libraries: `pandas`, `numpy`

You can install the necessary dependencies using pip:

```bash
pip install pandas numpy
