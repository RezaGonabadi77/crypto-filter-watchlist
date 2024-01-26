# Crypto Market Analysis Tool

## Overview

This Python script is designed to watch the crypto market and analyze historical price data for the top N cryptocurrencies symbols. It utilizes the CCXT library for accessing market data from the Binance exchange, pandas for data manipulation, and Plotly for interactive chart visualization.

The script provides insights into the market by detecting volume changes, significant price movements, Engulfing patterns, and Pin Bar patterns. Engulfing patterns and Pin Bars are highlighted on a candlestick chart for better visualization.

## Prerequisites

Before running the script, ensure you have the required Python packages installed. You can install them using the following command:

pip install ccxt pandas plotly

## Usage

1. Clone the repository:

git clone [https://github.com/RezaGonabadi77/crypto-filter-watchlist.git](https://github.com/RezaGonabadi77/crypto-filter-watchlist.git)

3. Open the Jupyter Notebook:

jupyter notebook

4. Run the script within the notebook.

## Configuration

- **Exchange Selection:** You can change the exchange by modifying the `exchange` variable in the script.
- **Timeframe:** Adjust the timeframe for historical data by modifying the `timeframe` variable.
- **Pin Bar Intensity Wick:** Fine-tune the Pin Bar pattern detection by modifying the `pinbar_intensity_wick` variable.

## Results

The script generates an interactive candlestick chart using Plotly, highlighting Engulfing patterns and Pin Bars with arrows. The chart provides a visual representation of potential market trends based on historical data.

## Examples

For a quick demonstration, refer to the provided Jupyter Notebook file (`crypto-engulfing-pinbar-chart.ipynb`) in this repository.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## Acknowledgments

- [CCXT Library](https://github.com/ccxt/ccxt)
- [Plotly](https://github.com/plotly/plotly.py)
- [Pandas](https://github.com/pandas-dev/pandas)

## Contact

For any inquiries, reach out gonabadyreza@gmail.com
