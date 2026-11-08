## Plan
- Camt052Format(Camt053Format) + reader trying both; real camt.052 from viafintech/camt_parser.
- PortfolioQuestion.ONLINE_BANKING -> OnlineBankingAccess (no PIN); real_estate/online_banking.py: StatementFetch with prompt for PIN/TAN/mechanism, from day after latest statement to yesterday; stand-in FinTS client in tests.
- scripts/fetch_statements.py; FINTS product identifier from environment; skill rule; ORM excludes the fetch module.
## Done
- Branch, draft PR #139.
## Next
- Tests first, then implementation.
