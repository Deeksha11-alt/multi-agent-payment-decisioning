# multi-agent-payment-decisioning

## Research question
How can autonomous AI agents collaboratively make payment decisions that
balance fraud risk, authorization, customer outcomes, compliance, and
profitability, and how can such decisions be evaluated and governed?

## Approach
Simulation of specialized agents (fraud, authorization, customer,
compliance, profitability) plus a coordinator, compared against
single-model and rules-plus-model baselines.

## Data
Public fraud datasets (e.g., IEEE-CIS). Authorization behavior is simulated.

## Evaluation
Pareto trade-offs across fraud loss, approval rate, false-decline cost,
compliance violations, and profit.

## Limitations
Public data lacks real issuer/acquirer authorization outcomes; results are
indicative, not real-world validated.

## Status
Day 1: repo setup and EDA.
