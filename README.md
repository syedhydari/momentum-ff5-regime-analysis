# Momentum Alpha: FF5 Regime Analysis

Date: December, 2025

## Project Overview

This project examines whether momentum portfolio returns exhibit statistically significant abnormal performance (alpha) after controlling for the Fama-French Five-Factor model. Using monthly U.S. equity data from 2010-2024, we test for both unconditional alpha and regime-dependent effects across market volatility states. 

### Research Questions
1. Do momentum portfolios earn significant alpha after controlling for FF5 factors?
2. Does momentum's effectiveness vary across high vs. low volatility regimes? 

### Key Findings
- Monthly alpha of 0.29% (~3.5% annually) with marginal statistical significance (p=0.074)
- **Significant negative market beta (-0.28)** indicating defensive/contrarian characteristics
- Momentum's defensive properties **strengthen during high-volatility periods**
- FF5 factors explain only 23.7% of momentum variance, suggesting unique return dimensions

## Methodology

- **Data Source:** Kenneth R. French Data Library
- **Sample Period:** January 2010 - December 2024 (180 monthly observations)
- **Models:** 
  - Model A: Standard FF5 factor regression
  - Model B:  Regime-interaction model with volatility-dependent betas
- **Statistical Methods:** OLS regression with Newey-West HAC robust standard errors
- **Regime Definition:** 12-month rolling volatility median split

## Repository Contents

- `Final-Code.rmd` - Complete R Markdown source code with data acquisition, analysis, and reporting
- `Final-Report.pdf` - Compiled academic report with full results and interpretation

## Academic Context

This project was completed for Linear Regression Models at Columbia University in December 2025. The analysis follows established methodologies from:
- Jegadeesh & Titman (1993) - Original momentum documentation
- Fama & French (2015) - Five-factor asset pricing model
- Carhart (1997) - Momentum factor construction

## Authors

Syed Bashir Hydari et al.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
