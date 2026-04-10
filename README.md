# EQUITY PORTFOLIO-OPTIMIZATION
PORTFOLIO-OPTIMIZATION
Quantitative framework for constructing optimal investment portfolios using Modern Portfolio Theory (MPT) and Python.

📌 Project Overview
This project implements the Mean-Variance Optimization framework to construct and analyze optimal equity portfolios. Using historical market data for five major U.S. equities—Apple (AAPL), NVIDIA (NVDA), Tesla (TSLA), Baker Hughes (BKR), and CSX Corp (CSX)—the analysis calculates key risk-return metrics to identify the most efficient asset allocations.

The study explores the trade-offs between risk and reward, identifying the Global Minimum Variance (GMV) portfolio and the Tangency (Maximum Sharpe Ratio) portfolio.

🚀 Key Features
Data Acquisition: Automated financial data retrieval using yfinance.

Risk-Return Analysis: Calculation of annualized expected returns, variance-covariance matrices, and correlation heatmaps.

Optimization: Construction of the Efficient Frontier and Capital Market Line (CML).

Performance Metrics: Evaluation using Sharpe Ratio, Treynor Ratio, and Jensen’s Alpha.

Visualization: Interactive and static plots for portfolio distributions and performance tracking.

📊 Visualizations & Results
Note: To display these, ensure you have saved your notebook plots as images in an images/ folder in your repository.

1. The Efficient Frontier
The core of MPT, illustrating the set of optimal portfolios that offer the highest expected return for a defined level of risk.

2. Asset Correlation Heatmap
Understanding the relationship between different sectors (Tech, Energy, Transportation) to maximize diversification benefits.

3. Portfolio Performance vs. Benchmark
Comparison of the optimized Tangency portfolio against an equal-weighted benchmark and the S&P 500.

🛠️ Tech Stack
Language: Python

Libraries: * Pandas & NumPy: Data manipulation and matrix calculations.

Matplotlib & Seaborn: Data visualization.

SciPy.optimize: Portfolio weight optimization.

yfinance: Real-time market data.

📈 Results Summary
Tangency Portfolio: Achieved the highest risk-adjusted return, heavily influenced by high-momentum stocks like NVDA.

GMV Portfolio: Successfully minimized volatility by diversifying across lower-correlation sectors.

Alpha Generation: Positive Jensen’s Alpha indicates the strategy successfully captured value beyond market expectations.

📂 Repository Structure
portfolio_optimization.ipynb: The primary Python notebook containing the full analysis.

data/: Directory containing historical price CSVs and processed log returns.

report/: Comprehensive PDF report detailing the mathematical framework and conclusions.
Author:Tharani Umesha
