## Plan
- real_estate/consistency.py: abstract PortfolioFinding, one subclass per kind (UnitLetTwice, VacantUnit, LeaseEndsBeforeItBegins, DepositAboveCeiling, UnrecognizablePayer, RentChangeBeforeBegin, NoRentAccount), carrying facts only, no text.
- PortfolioCheck(portfolio, day).findings(); units compared by identity; LeaseAgreement.runs_on(day) for vacancy.
- Tests first: tests/test_portfolio_consistency.py, one test per kind plus a clean portfolio with none; round trip of findings.
## Done
- Branch, draft PR, plan item in progress.
## Next
- Failing tests, then the checks.
