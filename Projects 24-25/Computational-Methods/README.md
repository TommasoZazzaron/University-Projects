Overview:
This project provides a detailed analysis and no-arbitrage pricing of exotic derivatives through computational methods. It utilizes advanced numerical techniques, including Monte Carlo simulations, lattice methods, and PDE-schemes, to price various types of put options under complex asset price dynamics.

Project Structure

Preliminary Analysis & Parameter Estimation:
- Analysis of underlying asset price dynamics using stochastic differential equations (SDE).
- Parameter estimation via Maximum Likelihood Estimation (MLE), confirming asset dynamics align closely with a generalized geometric Brownian motion.

European Put Option Pricing:
- Monte Carlo Simulations: Estimation of put option prices using path simulations and discounted payoff calculations.
- Lattice Methodologies: Application of recombining lattices through invertible function simulation to manage non-constant volatility.
- PDE Scheme: Numerical discretization of the PDE governing asset prices and derivative valuation to estimate option prices accurately.

American and Barrier Option Pricing:
- American Put Option: Pricing through lattice methods and PDE schemes, accounting for optimal early-exercise strategy.
- Down-and-Out Barrier Put Option: Pricing through Monte Carlo simulation, incorporating barrier conditions and path dependency.

Technical Highlights:
- Implementation of robust numerical methods to handle non-linear asset price dynamics.
- Comprehensive comparison of numerical techniques with convergence analysis and confidence intervals.
