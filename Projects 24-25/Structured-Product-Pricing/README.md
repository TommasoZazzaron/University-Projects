Overview:
This project evaluates a Capped Bonus Certificate issued by Vontobel Financial Products Ltd., linked to the S&P MidCap 400 Index. It includes quantitative pricing, payoff analysis, risk factor evaluation, and replicating strategy formulation.

Project Components

Payoff Analysis:
- Detailed breakdown of the certificate’s payoff structure, including bonus, barrier, and cap mechanisms.
- Conditions determining investor payoff based on barrier breaches and underlying performance.

Replicating Strategy:
- Decomposition of the certificate payoff into three financial instruments:
  - Zero-Coupon Bond
  - Short position in European put options
  - Long position in down-and-out put options
- Demonstrates the implicit financial structure and risk exposure.

Risk Factors Analysis:
- Detailed evaluation from the issuer's perspective, covering:
  - Underlying Asset: Delta and Gamma sensitivities.
  - Volatility Risk: Impact of implied volatility and volatility skew.
  - Time Decay: Theta risk management.
  - Interest Rate and Dividend Risks: Sensitivity to fluctuations in rates and dividend yields.
  - Model Risk: Analysis of modeling inaccuracies and assumptions.

Pricing Models:
- Heston Model Attempt: Initial approach with stochastic volatility modeling; challenges due to data scarcity.
- Black-Scholes Model: Practical implementation including volatility and dividend yield proxies; valuation using analytical formulas.

Sensitivity Analysis:
Computation and interpretation of Greeks to understand exposure to market changes:
- Delta, Gamma, Vega, Theta, Rho, Volga, and Vanna.
