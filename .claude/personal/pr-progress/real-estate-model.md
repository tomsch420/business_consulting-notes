## Plan
- BankWorkingDayOfMonth(position=3) in payment_calendar.py: rent due date, § 556b (1) BGB.
- real_estate/portfolio.py: UnitKind, RentalUnit, Building, Property, Portfolio (landlord, optional rent account, properties, leases).
- real_estate/lease.py: RentComponentKind, RentComponent (net Money, ValueAddedTax rate, RATE_0 default: RO5), RentChange (whole rent from a date), SecurityDeposit, LeaseAgreement (units, tenants, further_payers: RO4, begin/end, rent, changes, deposit, due date), rent_due_in(year, month) gross.
- Tests first: tests/test_real_estate_model.py, database round trip, Portfolio in the every-field-mapped test.
- Left out against the earlier sketch: land register entry and notice period, which no later item uses.
## Done
- Branch, draft PR #132, plan item in progress.
## Next
- Failing tests, then the model.
