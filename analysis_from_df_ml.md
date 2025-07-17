# Credit Score Analysis from Merged DataFrame

### Score Distribution

![Score Histogram](../score_dist_from_df_ml.png)

#### Bin Counts:
- **0-99**: 0 wallets
- **100-199**: 4 wallets
- **200-299**: 0 wallets
- **300-399**: 17 wallets
- **400-499**: 189 wallets
- **500-599**: 11030 wallets
- **600-699**: 32752 wallets
- **700-799**: 10737 wallets
- **800-899**: 26628 wallets
- **900-999**: 17104 wallets
- **1000-1099**: 1539 wallets

---

### Behavior of Low Score Wallets (Score < 400)
- avg_borrow: 3186262698764055.50
- avg_repay: 0.00
- avg_deposit: 725227830211972608.00
- avg_redeem: 0.00
- repay_to_borrow_ratio: 0.00
- liquidation_ratio: 0.57
- %_borrow: 23.81
- %_repay: 0.00
- %_deposit: 19.05
- %_redeemunderlying: 0.00
- %_liquidationcall: 57.14

---

### Behavior of High Score Wallets (Score >= 800)
- avg_borrow: 2213433231354511228928.00
- avg_repay: 2160392469531207401472.00
- avg_deposit: 3122274127575018635264.00
- avg_redeem: 2866016284249423347712.00
- repay_to_borrow_ratio: 0.98
- liquidation_ratio: 0.00
- %_borrow: 17.69
- %_repay: 15.99
- %_deposit: 45.00
- %_redeemunderlying: 21.20
- %_liquidationcall: 0.12

---

_Generated from `df_features` or DataFrame._
