## Plan
- core/legal_basis.py: LegalProvision (enum of frozen dataclasses), Authority, LegalBasis.
- core/legal_rule.py: LegalRule (EQL query with inference, conclusions, verbalized).
- Deposit ceiling rule, living space only (commercial no longer flagged).
- Termination grounds: three flat rules over each due date's arrears, letter a) before b) as a declared list; § 569 (3) No. 1 for commercial leases as firm convention.
- Test explain_inference and verbalization of one finding; stop for review before any insolvency rule.
## Done
- Plan restructured (landlord pilot replaces the interest pilot), issue #130 commented; draft PR #140.
## Next
- Tests first, then legal_basis.py.
