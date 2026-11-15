## Plan
- Speed up mandate runs (PR #152): index AssignmentBook by counterparty key and booking, so a suggestion is one lookup.
## Done
- Draft PR #152 (6d3932c): nursing_home run 125 s -> 70 s, one release 73 s -> 31 s; 234 passed; hooks pass.
## Next
- User's review; CI. Ask about renaming for_plan / suggestion_for (krrood check). Follow-ups: bookings-sheet styling, workbook opening, BookedActuals.plan_actuals; reading documents once for replays.
