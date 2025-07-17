# Wallet Credit Scoring (Aave V2)

This project assigns a **credit score (0–1000)** to wallets interacting with Aave V2 based on their transaction history. It uses behavioral patterns and financial ratios to assess risk.

## Features Used
- **Repayment Behavior**: repay-to-borrow ratio
- **Risk Indicators**: % of transactions that are liquidations
- **Deposit Commitment**: Total value deposited
- **Engagement**: Active days vs. total span

## Scoring Logic(Heuristic College)
The credit score is computed using a weighted sum:
- 30%: Repay-to-Borrow Ratio
- 30%: (1 - Liquidation Ratio)
- 20%: Log of total deposit
- 20%: Active Days / Span of Activity

Each score is capped between 0 and 1000.

## Random Forest Regressor 
- Extracted Features using the dataframe and then fitted the model
- We predict the score between 0 to 1000 using these features . 
## Classification Of Behavior 
- Low Score behavior V/s High Score behavior
- Also as whale , bot etc . 
