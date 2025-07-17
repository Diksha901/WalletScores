# Credit Score Analysis from Merged DataFrame

### Score Distribution

![Score Histogram](../score_dist_from_df.png)

#### Bin Counts:
- **0-99**: 4 wallets
- **100-199**: 0 wallets
- **200-299**: 0 wallets
- **300-399**: 13 wallets
- **400-499**: 249 wallets
- **500-599**: 10609 wallets
- **600-699**: 16118 wallets
- **700-799**: 13073 wallets
- **800-899**: 40570 wallets
- **900-999**: 15682 wallets
- **1000-1099**: 3682 wallets

---

### Behavior of Low Score Wallets (Score < 400)
- borrow: 0.24 times per wallet
- liquidationcall: 0.59 times per wallet
- deposit: 0.18 times per wallet

---

### Behavior of High Score Wallets (Score >= 800)
- deposit: 0.34 times per wallet
- borrow: 0.13 times per wallet
- repay: 0.12 times per wallet
- redeemunderlying: 0.40 times per wallet
- liquidationcall: 0.00 times per wallet

---

_Generated from `merged_data.json` or DataFrame._
