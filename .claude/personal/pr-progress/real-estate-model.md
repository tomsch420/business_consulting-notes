## Plan
- Model in real_estate/units.py, lease.py, portfolio.py; BankWorkingDayOfMonth in payment_calendar.py; RO4 further_payers and RO5 tax rate per component as options.
## Done
- Model and tests pushed (98af2fb); full suite 848 passed. PR #132 description lists the decisions: a rent change states the whole rent, rent_due_in is the whole month (proration in R4), rent_account optional, land register entry and notice period left out.
## Next
- CI and review on #132; after merge, R3 portfolio-consistency-checks and R4 rent-claims can both start from main.
