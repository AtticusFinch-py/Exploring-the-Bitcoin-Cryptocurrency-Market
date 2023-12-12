## Cryptocurrency Analysis Project

## Overview

This project involves the analysis of cryptocurrency data using Python and pandas. The dataset was obtained from the CoinMarketCap API on December 6, 2017, and covers various aspects of cryptocurrencies, including market capitalization, volatility, and categorization based on market cap.

**Disclaimer:** The cryptocurrency market is highly volatile, and investing in cryptocurrencies involves risks. This analysis is for educational purposes only and should not be considered as financial advice.

## Project Structure

### 1. Bitcoin and Cryptocurrencies: Full dataset, filtering, and reproducibility

- Utilizes the CoinMarketCap API data from December 6, 2017.
- Imports data using pandas and performs basic filtering.

### 2. Discard the cryptocurrencies without a market capitalization

- Filters out cryptocurrencies with no market capitalization.
- Prepares the data for further analysis.

### 3. How big is Bitcoin compared with the rest of the cryptocurrencies?

- Plots the market capitalization for the top 10 cryptocurrencies.
- Visualizes the dominance of Bitcoin in the market.

### 4. Making the plot easier to read and more informative

- Enhances the readability of the market capitalization plot.
- Uses log10 scale and color grouping for improved visualization.

### 5. What is going on?! Volatility in cryptocurrencies

- Explores the volatility of cryptocurrencies using percentage changes.
- Analyzes the 24 hours and 7 days percentage change data.

### 6. Well, we can already see that things are a bit crazy

- Plots the top 10 biggest gainers and losers in market capitalization.
- Highlights the extreme volatility in the cryptocurrency market.

### 7. Ok, those are... interesting. Let's check the weekly Series too.

- Expands the analysis to weekly percentage changes.
- Identifies the top gainers and losers over the week.

### 8. How small is small?

- Classifies cryptocurrencies based on market capitalization size.
- Differentiates between "biggish," "micro," and "nano" market caps.

### 9. Most coins are tiny

- Provides insights into the distribution of cryptocurrencies based on market cap.

## Usage

1. Ensure you have Python and the required libraries installed.
2. Run the provided Jupyter Notebook to perform the analysis.

**Note:** Update the dataset path if needed and exercise caution when interpreting the results.

## Disclaimer

This project is for educational purposes only. Always conduct thorough research before making any financial decisions related to cryptocurrencies.
