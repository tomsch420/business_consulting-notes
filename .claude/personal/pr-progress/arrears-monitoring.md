## Plan
- real_estate/arrears.py: ArrearsStatus (overdue, days late, total, deposit instalments, termination ground a/b with lapse), PortfolioMonitoring → PortfolioArrears.
- ClaimSettlement keeps ClaimPayments; outstanding_on(day).
## Done
- Implemented and pushed (a590bfa); full suite 893 passed; PR #136 description lists decisions and open points.
## Next
- CI and review on #136. Open: § 366 (2) order rent vs deposit (R5). Then R7 structured-portfolio (needs R3 and R6 merged).
