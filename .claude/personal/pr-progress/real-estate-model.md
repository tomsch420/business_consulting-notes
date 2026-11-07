## Plan
- Model in real_estate/units.py, lease.py, portfolio.py; BankWorkingDayOfMonth in payment_calendar.py; RO4 further_payers and RO5 tax rate per component as options.
## Done
- Model and tests pushed; full suite 848 passed at 98af2fb.
- Review: PostalAddress replaces address str; CadastralParcel (Gemarkung, Flur, Flurstücksnummer, area) listed on Property, area() sums them (4ff9ff0); both threads answered, left open.
## Next
- CI and review on #132; after merge, R3 and R4 can both start from main.
