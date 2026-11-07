## Plan
- real_estate/rent_claims.py: LeaseClaim (abstract), RentClaim (month Period, parts by component, pro rata by day), DepositInstalment (§ 551 (2) BGB).
- LeaseAgreement.claims_between(begin, end): claims due in that time, by due date.
## Done
- Implemented and pushed (b0793b5 + format revert); full suite 870 passed; PR #134 description lists the decisions.
## Next
- CI and review on #134. Then R5 rent-receipts-matching, stacked on rent-claims.
