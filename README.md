# Effective Investment Portfolio Project

The **Effective Investment Portfolio** project aims to develop a diversified and optimized investment portfolio using advanced data-driven methods. This multi-stage approach includes clustering analysis, portfolio optimization, Monte Carlo simulations, and backtesting using Exponentially Weighted Moving Average (EWMA). The project demonstrates the application of statistical modeling, optimization, and risk assessment techniques to enhance portfolio performance.

---

## Key Stages of the Project

### 1. Clustering Analysis

**Objective**: To categorize 50 selected assets based on return profiles and volatility, facilitating diversification.

**Methodology**:
- Applied the K-means clustering algorithm to group assets based on their risk-return characteristics.
- Used the Elbow Method to determine the optimal number of clusters, balancing simplicity and effectiveness.
- Visualized asset clusters with scatter plots, providing insights into inter-group characteristics and relationships.

**Outcome**: Identified clusters of assets with similar behaviors, laying the groundwork for diversified portfolio construction by selecting representatives from each cluster.

---

### 2. Portfolio Construction and Optimization (Including Monte Carlo Simulation)

**Objective**: To construct and optimize portfolios using representative assets from identified clusters, focusing on balancing risk and maximizing returns.

**Methodology**:
- **Monte Carlo Simulation**:
  - Generated thousands of random portfolios with varying allocations to simulate potential risk-return combinations.
  - Calculated expected returns, volatility, and the Sharpe ratio for each simulated portfolio to understand the distribution of possible outcomes.
  - Visualized the distribution of portfolio outcomes to aid in selecting the optimal portfolio.
- **Optimization**:
  - Applied Modern Portfolio Theory (MPT) principles to identify the efficient frontier, selecting portfolios that maximize expected return for given risk levels.
  - Optimized asset weights to maximize the Sharpe ratio, focusing on maximizing risk-adjusted returns.

**Outcome**: Created optimized portfolios leveraging Monte Carlo simulations to validate and enhance the robustness of the optimization process, ensuring comprehensive risk assessment and optimal asset allocation.

---

### 3. Backtesting with Exponentially Weighted Moving Average (EWMA)

**Objective**: To evaluate the stability and adaptability of the optimized portfolios through historical data simulation.

**Methodology**:
- Implemented backtesting using historical price data to simulate portfolio performance over time.
- Modeled time-varying volatility with EWMA, capturing the dynamic nature of financial markets.
- Analyzed key performance metrics, including cumulative returns, drawdowns, and volatility.

**Outcome**: Validated the portfolios' effectiveness, demonstrating consistent performance and adaptability to varying market conditions.

---

## Achieved Results

By integrating clustering, Monte Carlo simulations, portfolio optimization, and comprehensive backtesting, the project successfully:

- Identified asset clusters, facilitating strategic diversification.
- Constructed and optimized portfolios tailored to different risk tolerance levels, using simulations for robust validation.
- Demonstrated portfolio resilience through backtesting, confirming robust and consistent performance.

This approach illustrates a systematic application of data analytics, optimization techniques, and risk management strategies, providing practical insights into investment portfolio design and management.
