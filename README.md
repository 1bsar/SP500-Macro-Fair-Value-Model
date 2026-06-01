# S&P 500 Macro Fair Value Model

Macro valuation model estimating S&P 500 fair value using earnings, liquidity, interest rates, and inflation.

The model uses historical monthly data from 2005–2026 and applies a log-linear regression framework to estimate a fair value level for the S&P 500. It compares the model-implied fair value against the actual index level to calculate an overvaluation or undervaluation gap.

Core inputs:
- S&P 500 trailing operating EPS
- M2 money supply
- Fed Funds Rate
- CPI year-over-year inflation

The model is intended as a macro valuation framework, not a short-term trading signal or price target.

Key limitations:
- The model is regime-dependent.
- Historical fit does not guarantee future accuracy.
- EPS data is partially interpolated.
- The Fed Funds coefficient should be interpreted cautiously due to historical-period effects.

Not financial advice.
