# econ3916-lab05-monte-carlo

# Monte Carlo Engine -- Probability & Simulation

## Objective

In this lab, I used Monte Carlo simulations to understand probability, conditional probability, and financial risk.

## Methodology

- Simulated 10,000 coin flips and plotted the running share of heads.
- Simulated 10,000 Monty Hall games to compare staying and switching strategies.
- Simulated disease screening for 100,000 people with 1% prevalence, 95% sensitivity, and 90% specificity.
- Calculated Value at Risk (VaR) and Expected Shortfall (ES) for a $1,000,000 portfolio.
- Estimated pi using Monte Carlo simulation and examined how the error changes as the sample size increases.
- Compared an AI-generated VaR and ES function with my own calculations.

## Key Findings

- **Monty Hall:** Switching won 6,694 out of 10,000 games (66.94%), showing that switching is better than staying.
- **Disease Screening:** About 8.62% of positive tests came from people who were actually sick.
- **Financial Risk:** The 95% VaR was $19,494, and the 95% ES was $24,230 for a $1,000,000 portfolio.
- **Monte Carlo Accuracy:** The estimated log-log slope was -0.532, close to the theoretical value of -0.5. This shows that simulation error decreases as the sample size increases.
- **AI Verification:** The AI-generated function matched my own VaR and ES calculations.
