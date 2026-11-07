## Plan
- real_estate/rent_ledger.py: RentReceiptMatching → RentBook (RentLedger per lease with ClaimSettlement per claim, credit; findings UnrecognizedPayer / PartlyRecognizedPayer).
## Done
- Implemented and pushed (70890a6); full suite 883 passed; PR #135 description lists decisions and open points (returned direct debits, foreign currency).
## Next
- CI and review on #135. Then R6 arrears-monitoring from main once merged.
