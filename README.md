# Crypto Auto-Trader

A Python application that periodically scrapes trending cryptocurrency data from the Moralis website and automatically buys tokens based on user-defined thresholds like Hype Score, ROI, FDV, and Coin Age.

## Features

- Scrapes data from the Moralis website every 5 minutes.
- Stores the scraped data in a Pandas DataFrame.
- Saves the data to a CSV file for further analysis.
- Allows users to define thresholds for automatic cryptocurrency purchases based on Hype Score, ROI, FDV, Coin Age, and other metrics.
- Integrates with crypto trading APIs (to be implemented) for automated trading.

## Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/crypto-auto-trader.git
