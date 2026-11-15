## Plan
- Speed up mandate runs (PR #152): assignment index, workbook cache, style_table without rescanning, actuals in one pass.
## Done
- a6faab9: nursing_home 125 s -> 18 s per run, a release 73 s -> ~3 s; 485 passed, 5 skipped; hooks pass. a7ab995 renamed for_plan -> from_plan, suggestion_for -> suggested_position.
## Next
- User's review; CI. Left: opening the bookings workbook (7.5 s), writing planning files (6.7 s).
