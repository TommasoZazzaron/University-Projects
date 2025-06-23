Overview:
This project explores data-driven methods for robust portfolio construction, focusing on the automatic denoising of variance-covariance matrices. By applying the Marčenko–Pastur distribution, it separates informative from noisy eigenvalues, enhancing the stability and reliability of portfolio allocations.

Project Components

Theoretical Background:
- Portfolio Optimization: Implementation of Minimum Variance and Maximum Sharpe Ratio portfolios using covariance matrix inversions.
- Denoising Theory: Application of spectral decomposition and Marčenko–Pastur density fitting to identify and replace noisy eigenvalues.

Empirical Analysis:
- Eigenvalue Classification: Identification of informative versus noisy eigenvalues using empirical correlation matrix decomposition.
- Matrix Reconstruction: Reconstruction of denoised covariance matrices ensuring numerical stability for reliable portfolio allocations.

Portfolio Allocation:
- Comparative analysis of portfolio performance before and after denoising:
- Equally Weighted Portfolio
- Global Minimum Variance Portfolio (pre- and post-denoising)
- Maximum Sharpe Ratio Portfolio (pre- and post-denoising)
- Out-of-sample performance evaluation (expected returns, variance, Sharpe ratios).

Sensitivity Analysis:
- Investigation of noise growth with increasing asset dimensions.
- Demonstrates the critical need for denoising in high-dimensional asset allocation.
