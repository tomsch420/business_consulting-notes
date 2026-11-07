## Plan
- real_estate/rent_ledger.py: rent account credits from BankStatements; payer via PartyRegister seeded with lease payers; partial match → finding.
- Allocation: month named in remittance first, then oldest open claim (§ 366 (2) BGB), across all the payer's leases (RO1).
- RentLedger per lease: ClaimSettlement per claim (Settlement shape), credit left over; unmatched receipts as findings.
## Done
- Branch, draft PR #135, item in progress.
## Next
- Tests on DK camt.053 examples, then the module.
