# Linear Regression in Finance

In this project, I applied **Linear Regression** to the financial domain, incrementally adding factors to the regression model to:
- Enhance its explanatory power
- Identify the key variables contributing to the prediction of the target variable (**Apple’s monthly risk premium**)

The goal is to evaluate how different factors influence Apple’s risk premium and determine the most significant contributors.

## Models Applied

- **CAPM Regression**
  - Regression on the **market’s monthly risk premium**
  - Tests the validity of the **Capital Asset Pricing Model (CAPM)** as a no-arbitrage model for stock returns

- **Fama–French Three-Factor Model**
  - Regression on:
    - **Market Risk Premium**
    - **SMB** (Small Minus Big)
    - **HML** (High Minus Low)
  - Assesses the model’s explanatory power in asset pricing

- **Fama–French Five-Factor Model**
  - Extends the three-factor model by including:
    - **RMW** (Robust Minus Weak)
    - **CMA** (Conservative Minus Aggressive)

- **Extended Five-Factor Model with Sector Portfolios**
  - Builds on the five-factor model by adding **monthly returns of stock portfolios clustered by sector**
  - Evaluates the impact of sector-based diversification on explanatory ability
