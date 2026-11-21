## Plan
- #160: KPI events in a per-machine SQLite EventDatabase, migrated by one Migration class per change (starts_from_commit on main); git checks on CI.
## Done
- ec5de66: review round 1 - events/, migrations/ (history, exceptions, versions/), orm/model.py, starts_from_commit + test. All 5 threads answered, left open.
## Next
- CI result; user's next review.
- Maybe: CI regenerates the ORM at starts_from_commit to check each migration's difference.
- Outside this PR: record events from hooks/review script, root path for the file, KPI queries, shipping events off the machines.
