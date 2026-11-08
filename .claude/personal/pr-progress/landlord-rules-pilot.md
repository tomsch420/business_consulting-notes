## Plan
- Pilot done; stop for the user's review before any insolvency rule moves (interest-from-filing-rule next).
## Done
- Plan restructured (landlord pilot replaces the interest pilot), issue #130 commented; draft PR #140.
- fe80b21: legal_basis.py, legal_rule.py; DepositCeilingRule (living space only); three termination ground rules in declared order, commercial threshold as firm convention; process doc. 950 tests passed.
- c4c65bd: renamed DueDateArrears.all_of/at to of_each_due_date/at_end_of_due_date (review threads, replied).
## Next
- Four review threads on predicates (StillOwed etc. need not be predicates; class holding a query) left unaddressed by the user's choice.
- User's review of #140. Open: legal_basis rendered by repr in verbalization (german-clause-verbalization); mixed leases not weighed in LetsLivingSpace; plan site build fails (reusable workflow not found in basstler).
