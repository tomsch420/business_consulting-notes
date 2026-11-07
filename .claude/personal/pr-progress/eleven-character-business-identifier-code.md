## Plan
- Write a business identifier code out in eleven characters; schwifty 2026.11.0 drops the XXX branch (blocks real-estate-management step 0 baseline).
## Done
- InternationalBankAccountNumber.business_identifier_code appends XXX when the registry gives no branch; draft PR #129 with label bug.
- #128 merged; rebased onto main at 095e04a, pushed 07a532f, converted back to draft. Both fixed test files pass locally.
## Next
- CI on 07a532f; once merged, mark step 0 of real-estate-management done and start R1.
