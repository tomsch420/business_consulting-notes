## Plan
- Write a business identifier code out in eleven characters; schwifty 2026.11.0 drops the XXX branch (blocks real-estate-management step 0 baseline).
## Done
- InternationalBankAccountNumber.business_identifier_code appends XXX when the registry gives no branch; draft PR #129 with label bug.
- CI red only on the JPT test #128 fixes (1 failed, 732 passed); explained on the PR.
## Next
- Once #128 is merged: rebase onto main, push, confirm CI green, keep as draft.
