## Plan
- ClaimSettlement records each payment (ClaimPayment: transaction, amount) so arrears on a past due date can be told.
- real_estate/arrears.py: ArrearsStatus.of_ledger(ledger, cut_off): overdue rent claims with days late, total owed, unpaid deposit instalments, termination ground (§ 543 (2) Nr. 3 a/b with § 569 (3) Nr. 1).
- PortfolioMonitoring(portfolio, statements, day).report(): statuses, receipt findings, totals.
## Done
- Branch, draft PR #136, item in progress.
## Next
- Tests first.
