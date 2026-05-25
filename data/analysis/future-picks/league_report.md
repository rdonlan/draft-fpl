# BMS FPL Future Pick Tracker

A draft-pick ownership page built from the workbook's `Drafting Order` tab, with a reconciliation pass against the trade ledger.

## Best Quick Hits

- **2026 traded picks on the tracker**: 16.
- **2027 traded picks on the tracker**: 2.
- **Most 2026 picks**: Levi with 17 picks.
- **Most 2027 picks**: Levi with 15 picks.
- **Reconciliation flags**: 5 pick-owner mismatches between the Excel tracker and the parsed trade ledger.
- **Workbook count-table flags**: 9 count mismatches between the 2026 count table and the 2026 ownership board.

<details open>
<summary><h2>Manager Pick Portfolio</h2></summary>

Use this as the quick manager-by-manager view: total future picks, net gain/loss versus the standard 13 draft picks, incoming picks, and outgoing picks.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- The standard count is rounds `3rd` through `15th`; rounds `1st` and `2nd` are keeper slots in the workbook.
- **Incoming** means another manager's original pick is currently held by this manager.
- **Outgoing** means this manager's original pick is currently owed to someone else.

</details>

| Year | Manager | Total Picks | Net vs 13 | Incoming | Outgoing | Incoming Picks | Outgoing Picks |
|---|---:|---:|---:|---:|---:|---:|---:|
| 2026 | Levi | 17 | +4 | 5 | 1 | Luke 3rd; Justin 7th; Luke 7th; Justin 8th; Luke 12th | 4th to Ethan |
| 2026 | Dylan | 16 | +3 | 3 | 0 | Justin 3rd; House/Haydo 5th; Donny 10th | - |
| 2026 | Drake | 15 | +2 | 2 | 0 | Donny 4th; Donny 8th | - |
| 2026 | Julius | 15 | +2 | 2 | 0 | Justin 6th; Donny 9th | - |
| 2026 | Ethan | 14 | +1 | 2 | 1 | Levi 4th; Donny 6th | 10th to Donny |
| 2026 | Chabo | 13 | +0 | 0 | 0 | - | - |
| 2026 | House/Haydo | 13 | +0 | 1 | 1 | Justin 10th | 5th to Dylan |
| 2026 | Luke | 10 | -3 | 0 | 3 | - | 3rd to Levi; 7th to Levi; 12th to Levi |
| 2026 | Donny | 9 | -4 | 1 | 5 | Ethan 10th | 4th to Drake; 6th to Ethan; 8th to Drake; 9th to Julius; 10th to Dylan |
| 2026 | Justin | 8 | -5 | 0 | 5 | - | 3rd to Dylan; 6th to Julius; 7th to Levi; 8th to Levi; 10th to House/Haydo |
| 2027 | Levi | 15 | +2 | 2 | 0 | Justin 5th; Justin 6th | - |
| 2027 | Chabo | 13 | +0 | 0 | 0 | - | - |
| 2027 | Donny | 13 | +0 | 0 | 0 | - | - |
| 2027 | Drake | 13 | +0 | 0 | 0 | - | - |
| 2027 | Dylan | 13 | +0 | 0 | 0 | - | - |
| 2027 | Ethan | 13 | +0 | 0 | 0 | - | - |
| 2027 | House/Haydo | 13 | +0 | 0 | 0 | - | - |
| 2027 | Julius | 13 | +0 | 0 | 0 | - | - |
| 2027 | Luke | 13 | +0 | 0 | 0 | - | - |
| 2027 | Justin | 11 | -2 | 0 | 2 | - | 5th to Levi; 6th to Levi |

</details>

<details>
<summary><h2>2026 Pick Board</h2></summary>

Workbook-style board for 2026: each column is the original owner of the pick, and the cell shows whether that pick is still own or owed to another manager.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- `Own` means the original owner still controls that pick.
- `-> Manager` means that original pick is currently owed to the named manager.
- `Keeper` appears for rounds 1 and 2 because those slots are not part of the traded-pick count.

</details>

| Round | Donny | Justin | House/Haydo | Levi | Luke | Julius | Drake | Chabo | Ethan | Dylan |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1st | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 2nd | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 3rd | Own | ->Dylan | Own | Own | ->Levi | Own | Own | Own | Own | Own |
| 4th | ->Drake | Own | Own | ->Ethan | Own | Own | Own | Own | Own | Own |
| 5th | Own | Own | ->Dylan | Own | Own | Own | Own | Own | Own | Own |
| 6th | ->Ethan | ->Julius | Own | Own | Own | Own | Own | Own | Own | Own |
| 7th | Own | ->Levi | Own | Own | ->Levi | Own | Own | Own | Own | Own |
| 8th | ->Drake | ->Levi | Own | Own | Own | Own | Own | Own | Own | Own |
| 9th | ->Julius | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 10th | ->Dylan | ->House/Haydo | Own | Own | Own | Own | Own | Own | ->Donny | Own |
| 11th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 12th | Own | Own | Own | Own | ->Levi | Own | Own | Own | Own | Own |
| 13th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 14th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 15th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |

</details>

<details>
<summary><h2>2027 Pick Board</h2></summary>

Workbook-style board for 2027: each column is the original owner of the pick, and the cell shows whether that pick is still own or owed to another manager.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- `Own` means the original owner still controls that pick.
- `-> Manager` means that original pick is currently owed to the named manager.
- `Keeper` appears for rounds 1 and 2 because those slots are not part of the traded-pick count.

</details>

| Round | Donny | Justin | House/Haydo | Levi | Luke | Julius | Drake | Chabo | Ethan | Dylan |
|---|---:|---:|---:|---:|---:|---:|---:|---:|---:|---:|
| 1st | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 2nd | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper | Keeper |
| 3rd | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 4th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 5th | Own | ->Levi | Own | Own | Own | Own | Own | Own | Own | Own |
| 6th | Own | ->Levi | Own | Own | Own | Own | Own | Own | Own | Own |
| 7th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 8th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 9th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 10th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 11th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 12th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 13th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 14th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |
| 15th | Own | Own | Own | Own | Own | Own | Own | Own | Own | Own |

</details>

<details>
<summary><h2>Traded Pick Detail</h2></summary>

A compact list of every future pick currently marked as owed to someone other than its original owner.

| Year | Round | Original Owner | Current Holder | Workbook Cell |
|---|---:|---:|---:|---:|
| 2026 | 3rd | Justin | Dylan | OWED TO DYLAN |
| 2026 | 3rd | Luke | Levi | OWED TO LEVI |
| 2026 | 4th | Donny | Drake | OWED TO DRAKE |
| 2026 | 4th | Levi | Ethan | OWED TO ETHAN |
| 2026 | 5th | House/Haydo | Dylan | OWED TO DYLAN |
| 2026 | 6th | Donny | Ethan | OWED TO ETHAN |
| 2026 | 6th | Justin | Julius | OWED TO JULIUS |
| 2026 | 7th | Justin | Levi | OWED TO LEVI |
| 2026 | 7th | Luke | Levi | OWED TO LEVI |
| 2026 | 8th | Donny | Drake | OWED TO DRAKE |
| 2026 | 8th | Justin | Levi | OWED TO LEVI |
| 2026 | 9th | Donny | Julius | OWED TO JULIUS |
| 2026 | 10th | Donny | Dylan | OWED TO DYLAN |
| 2026 | 10th | Ethan | Donny | OWED TO DONNY |
| 2026 | 10th | Justin | House/Haydo | OWED TO HOUSE/HAYDO |
| 2026 | 12th | Luke | Levi | OWED TO LEVI |
| 2027 | 5th | Justin | Levi | OWED TO LEVI |
| 2027 | 6th | Justin | Levi | OWED TO LEVI |

</details>

<details>
<summary><h2>Trade Ledger Reconciliation</h2></summary>

This checks the workbook tracker against future-pick movements parsed from the trade ledger and calls out anything that does not line up.

<details class="notes">
<summary>Definitions and calculation notes</summary>

- For 2024-25 trade rows, only explicitly labeled `2026` or `2027` picks are treated as future picks; unlabeled picks are assumed to belong to the already-completed 2025 draft.
- For 2025-26 rows after Draft Day, unlabeled pick assets are treated as 2026 future picks unless the asset explicitly says 2027.
- In pass-through cases where a manager held more than one pick in the same round, the parser tries to use the non-own pick first and records that assumption below.
- Multi-team trade rows do not state exactly which counterparty receives each asset, so those recipient assumptions are listed separately.

</details>

| Issue | Year | Round | Original Owner | Tracker Holder | Ledger Holder | Ledger Evidence | Notes |
|---|---:|---:|---:|---:|---:|---:|---:|
| Tracker-only move | 2026 | 3rd | Justin | Dylan | Justin | No future-pick movement found in parsed trade ledger | - |
| Ledger-only move | 2026 | 3rd | Levi | Levi | Dylan | Postseason: Levi -> Dylan | - |
| Tracker-only move | 2026 | 10th | Justin | House/Haydo | Justin | No future-pick movement found in parsed trade ledger | - |
| Ledger-only move | 2026 | 10th | Levi | Levi | House/Haydo | Postseason: Levi -> House/Haydo | - |
| Ledger-only move | 2026 | 12th | Donny | Donny | Dylan | Draft Day: Donny -> Dylan | - |

</details>

<details>
<summary><h2>Reconciliation Assumptions</h2></summary>

These are not necessarily errors; they are the trade-ledger rows where the parser had to infer pass-through ownership or a recipient.

| Year | Round | Original Owner | Sender | Recipient | Timing | Assumption | Asset |
|---|---:|---:|---:|---:|---:|---:|---:|
| 2026 | 5th | House/Haydo | House/Haydo | Levi | Postseason | multi-team trade; recipient inferred as Levi | 2026 5th-round pick |
| 2026 | 5th | House/Haydo | Levi | Dylan | Postseason | original owner inferred from a pass-through pick currently held by sender; sender held 2 5th-round picks | 2026 5th-round pick |

</details>

<details>
<summary><h2>Workbook Count Check</h2></summary>

This verifies the workbook's 2026 count table against the ownership board above.

| Year | Round | Manager | Workbook Count | Calculated Count | Workbook Row |
|---|---:|---:|---:|---:|---:|
| 2026 | 3 | Levi | 1 | 2 | 23 |
| 2026 | 3 | Luke | 1 | 0 | 23 |
| 2026 | 4 | Ethan | 1 | 2 | 24 |
| 2026 | 7 | Luke | 1 | 0 | 27 |
| 2026 | 10 | Dylan | 1 | 2 | 30 |
| 2026 | 12 | Ethan | 2 | 1 | 32 |
| 2026 | Total | Levi | 15 | 17 | 36 |
| 2026 | Total | Luke | 13 | 10 | 36 |
| 2026 | Total | Dylan | 15 | 16 | 36 |

</details>

<details>
<summary><h2>Output Files</h2></summary>

- `future_pick_portfolio.csv`
- `future_pick_matrix.csv`
- `future_pick_traded_detail.csv`
- `future_pick_reconciliation.csv`
- `future_pick_count_audit.csv`
- `future_pick_movements.csv`
</details>
