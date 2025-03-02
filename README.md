# Risk Analysis for Retail Investors

This project aims to assist retail investors in understanding their risk by analyzing their investment portfolios. The analysis includes data collection, risk metrics calculation, performance evaluation, and visualization.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Data Collection](#data-collection)
- [Risk Metrics Calculation](#risk-metrics-calculation)
- [Performance Evaluation](#performance-evaluation)
- [Visualization](#visualization)
- [Results](#results)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/yourrepository.git
    cd yourrepository
    ```

2. Install the required packages:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. Open the Jupyter notebook:
    ```sh
    jupyter notebook Risk_Analysis.ipynb
    ```

2. Run the cells in the notebook to perform risk analysis on the investment portfolio.

## Project Structure

- `Risk_Analysis.ipynb`: The main Jupyter notebook containing the code for data collection, risk metrics calculation, performance evaluation, and visualization.
- `requirements.txt`: The list of required packages.
- `README.md`: This README file.

## Data Collection

Financial data is collected using the `yfinance` library. The `get_data` function fetches historical adjusted closing prices for the specified assets.

## Risk Metrics Calculation

The notebook calculates various risk metrics, including:
- **Volatility**: Measures the dispersion of returns for a given security or market index.
- **Correlation**: Measures the relationship between the returns of different assets.
- **Value at Risk (VaR)**: Estimates the potential loss in value of a portfolio over a defined period for a given confidence interval.
- **Sharpe Ratio**: Measures the risk-adjusted return of the portfolio.

## Performance Evaluation

The performance of the portfolio is evaluated using metrics such as cumulative returns, daily returns, and volatility. The Sharpe ratio is also calculated to assess the risk-adjusted return of the portfolio.

## Visualization

The notebook provides various visualizations, including:
- Correlation heatmap
- Portfolio volatility
- Benchmark volatility
- Portfolio performance compared to benchmarks

## Results

The notebook provides detailed analysis and visualizations of the portfolio's risk and performance. It also compares the portfolio's performance with benchmarks.

## Example Output

```plaintext
Portfolio Daily Volatility: 3.66%
Portfolio Weekly Volatility: 8.18%
Portfolio Monthly Volatility: 16.76%
Portfolio Quarterly Volatility: 29.03%
Portfolio Annual Volatility: 58.07%
Benchmark Daily Volatility: 0.79%
Benchmark Weekly Volatility: 1.77%
Benchmark Monthly Volatility: 3.64%
Benchmark Quarterly Volatility: 6.30%
Benchmark Annual Volatility: 12.59%
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
