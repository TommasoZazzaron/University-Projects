Overview:
This project outlines a volatility-driven trading strategy focused on NVIDIA's stock, leveraging its high volatility, market leadership in AI, and liquid options market. The strategy aims to generate profit by actively managing volatility exposure through complex derivative structures.

Trading Strategy:
- Positions Sold:
  - Double Knock-In Barrier Call Options (1 and 3-month maturities)
  - Down-and-In Digital Barrier Put Options (1-month maturity)

- Positions Purchased:
  - Strangle Options (1 and 3-month maturities)
  - Strip Options (1-month maturity)

Risk and Hedging:
- Vega Positive: Profits from high volatility scenarios.
- Gamma Neutral: Limited exposure to small price movements.
- Delta Neutral: Hedged against directional price risks.

Monte Carlo Modeling:
- Heston Model: Implemented for dynamic modeling of underlying asset price and volatility, calibrated using Euler discretization and Cholesky decomposition techniques.

Risk Management and Limit:
- Value at Risk (VaR) assessed at 95% confidence.
- Sensitivity analyses performed for changes in market factors (price, volatility).

Stress Test Scenarios:
Analyzed scenarios include:
- Significant volatility increases (e.g., DeepSeek AI announcements, US-China trade war).
- Substantial volatility decreases (e.g., NVIDIA maturing as a stable company).
