**Overview**
This project applies Modern Portfolio Theory (MPT) to construct an optimal portfolio by balancing risk and return using historical stock data (Apple, Microsoft, Google, Amazon). The model identifies the asset allocation that maximizes the Sharpe Ratio and visualizes the Efficient Frontier.

**Objectives**
Analyze historical stock price data
Calculate returns, volatility, and covariance
Optimize portfolio allocation for maximum risk-adjusted return
Visualize risk-return trade-offs using the Efficient Frontier

**Tools & Technologies**
Python
Pandas
NumPy
Matplotlib
SciPy
Data Source: Yahoo Finance

**Methodology**
Collected historical stock data
Calculated daily returns and covariance matrix
Applied mean-variance optimization
Maximized Sharpe Ratio using numerical optimization
Simulated multiple portfolios to generate the Efficient Frontier

**Results**
Expected Return: 38.82%
Risk (Volatility): 23.27%
Optimal allocation heavily weighted towards GOOGL

**Key Insights**
Diversification reduces overall portfolio risk
Higher returns come with higher volatility
Optimal portfolios lie on the Efficient Frontier
Data-driven allocation improves investment decisions



**Graph**

<img width="275" height="197" alt="image" src="https://github.com/user-attachments/assets/09431e9e-2c0c-45c1-bb00-d2290ae66aff" />
<img width="917" height="581" alt="image" src="https://github.com/user-attachments/assets/5efe30e1-0140-40b2-92c9-4a6dac4cac75" />


**Conclusions**

The optimized portfolio achieved an **expected annual return of ~38.8%** with a **volatility of ~23.3%**, indicating a strong risk-return trade-off.
The allocation is heavily weighted toward **GOOGL (51%)**, suggesting it contributed significantly to maximizing the Sharpe ratio in this dataset.
Diversification across multiple tech stocks helped reduce overall portfolio risk compared to holding a single asset.
The Efficient Frontier demonstrates that higher returns are associated with higher volatility, consistent with Modern Portfolio Theory.
The optimal portfolio lies on the upper boundary of the Efficient Frontier, confirming it delivers the best possible return for its level of risk.
Lower-weight allocations (e.g., MSFT at 9%) indicate comparatively lower contribution to risk-adjusted performance during the selected time period.
The results highlight the importance of data-driven asset allocation rather than equal weighting.


**Author**
Alroy Fernandes

LinkedIn: linkedin.com/in/alroy-fernandes-ab0335153/
GitHub: (your profile)
