README - Dataset Information

The dataset used in this project is not included in the repository due to its large size.

Dataset Details:
----------------
- Rows: ~44,975
- Columns: 396
- Data Type: Wallet-level LP (Liquidity Provider) scoring data

Contents:
----------
Each row represents a wallet, containing:
1. Top-level fields: _id, wallet_id, aggregated_lp_score
2. Category breakdown fields:
   - lp_category_breakdown.stable-stable
   - lp_category_breakdown.stable-volatile
   - lp_category_breakdown.volatile-volatile
3. Up to 13 pool-level slots per wallet (lp_scores[0..12]), each including:
   - Pool metadata: pool_id, pool_name, fee_tier, tokens, TVL
   - Activity metrics: deposits, withdrawals, holding times, liquidity retained
   - Scoring metrics: deposit_volume_score, withdrawal_score, frequency_score, 
     liquidity_retention_score, volatility_score, time_score, and total_score

Reason for Exclusion:
----------------------
The dataset is too large to upload directly with the project files. 
It should be placed manually into the `dataset/` folder as:
    dataset/dex-temp-db.score_v4.csv

Source:
--------
Provided by the internship assignment (LP Score v4 validation task).

