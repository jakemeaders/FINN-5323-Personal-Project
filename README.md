# FINN-5323-Personal-Project

## Introduction

Welcome to Jacob Meaders' FINN 5323 Personal Project! This project's main goal is to analyze the effectiveness of ESG (Environmental, Social, Governance) stocks at producing stock returns.

## Project Overview

This project's main goal is to investigate whether incorporating ESG criteria into investment decisions leads to better finance performance than traditional investments. Additionally, it will analyze how firms with low ESG risk ratings (AKA ESG firms) perform relative to firms with higher risk ratings (AKA Traditional firms). This will ultimately provide more information for investors and convey if ESG firms perform better or worse than traditional firms.

## How It Works (Briefly)

1. **Download ESG Data**: From 'sp500_esg.csv' file.
2. **Classify Stocks as ESG or Traditional**: For grouping later on in the analysis.
3. **Pick Top 20 Stocks for Each Group**: To reduce the number of companies being analyze for performance purposes.
4. **Download Stock Data**: Using the yfinance package in Python.
5. **Visualization**: To compare average returns of stocks and the groups over the 2-year period covered.
6. **Modeling**: To compare the performance of ESG and Traditional stocks.

## Installation Instructions

Set up this tool on your local system by following these steps:

1. Clone the project repository from GitHub: [https://github.com/jakemeaders/FINN-5323-Personal-Project](https://github.com/jakemeaders/FINN-5323-Personal-Project)
2. Ensure Python 3.11 or later is installed on your system.
3. Install required Python packages: `pip install pandas numpy matplotlib yfinance scipy`
4. Launch the application: `Personal Project.ipynb`

## Required Python Packages

- `pandas`: For data manipulation and analysis.
- `numpy`: For support with large, multi-dimensional arrays and matrices.
- `matplotlib`: For creating static, interactive, and animated visualizations in Python.
- `scipy`: For running t-tests.
- `yfinance`: For retrieving stock data from Yahoo Finance.

## Potential Pitfalls & Challenges

- **Analysis Length**: A longer time-period to analyze would increase the reliability of the results.
- **Group Size**: Only 40 companies total were used in this project, and, similar to analysis length, analyzing more companies would provide more reliable results.
- **Model Simplicity**: The models ran for comparison in this project are relatively simple.
- **Group Granularity**: Creating different groups for each ESG Risk Level would likely improve the comparability across groups, rather than only having 2 groups.

## Future Directions

Conduct further analysis comparing stocks that would be deemed to fit into the ESG criteria and stocks that do not, AKA 'Traditional' stocks.

## License

This project is freely available under the MIT License, permitting broad use and modification.

## Contact

For further information, please reach out to @jakemeaders on Github.

## Author

Jacob Meaders, Master's of Applied Business Analytics Student at the University of Arkansas
