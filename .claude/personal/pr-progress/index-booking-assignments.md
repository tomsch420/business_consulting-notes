## Plan
- Speed up mandate runs (PR #152): assignment index, workbook cache, style_table without rescanning, actuals in one pass.
## Done
- a6faab9: nursing_home 125 s -> 18 s per run, a release 73 s -> ~3 s; 485 passed, 5 skipped; hooks pass.
## Next
- User's review; CI. Ask about renaming for_plan / suggestion_for. Left: opening the bookings workbook (7.5 s), writing planning files (6.7 s).
