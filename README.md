# SP-500-Stock-Pricing-Prediction

# NFT Trading Strategy Simulation

This project contains a Python script designed to simulate a trading strategy for Non-Fungible Tokens (NFTs) using historical data. The script utilizes the Zipline library, a Pythonic algorithmic trading library, to backtest the strategy against historical NFT market data.

## Overview

The trading strategy implemented in this script is based on a simple moving average (SMA) crossover logic. The strategy analyzes the price of a given NFT asset and makes buy or sell decisions based on its current price relative to its historical average.

## Key Features

- **Data Handling**: The script includes functionality to load and preprocess NFT market data from a CSV file (`NFT-USD.csv`).
- **Trading Logic**: A straightforward trading strategy is implemented, which executes buy orders when the current NFT price is below its 20-day average and sells when the price is above.
- **Performance Recording**: The script records the performance of the trading strategy over the specified period for further analysis.

## Requirements

- Python 3.x
- Pandas: For data manipulation and analysis.
- Zipline: An open-source algorithmic trading simulator.
- Pytz: For timezone calculations.

## Setup and Execution

1. **Install Dependencies**:
   Ensure that Python 3.x is installed on your system. You can then install the required Python libraries using pip:
   ```
   pip install pandas zipline pytz
   ```

2. **Data Preparation**:
   Place your NFT market data file (`NFT-USD.csv`) in the same directory as the script. The data file should contain historical price data for the NFT asset.

3. **Running the Simulation**:
   Execute the script in a Python environment:
   ```
   python PricePrediction.py
   ```
   This will run the trading simulation over the defined period using the provided NFT market data.





