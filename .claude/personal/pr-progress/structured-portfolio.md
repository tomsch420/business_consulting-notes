## Plan
- business_consulting/real_estate/structured_portfolio.py: PortfolioPhase, PortfolioQuestion (Enum of frozen wording), StructuredPortfolio(statements_directory) → PortfolioRun (portfolio, cut-off, findings, arrears); UnansweredPortfolioQuestion in core/exceptions.
- Portfolio.deposit_account (RO3); matching reads its credits, which pay deposit instalments only.
- SourceDocumentRoot: portfolios/<name>/{portfolio.py, statements/, portfolio.sqlite}; mandate_directory_names skips portfolios.
- liquidity_planning_sources/portfolio_module.py: load, run, store in portfolio.sqlite; scripts/run_portfolio.py.
- End-to-end test: two buildings, three leases, DK example statement.
## Done
- Branch, draft PR #137, item in progress.
## Next
- Tests first.
