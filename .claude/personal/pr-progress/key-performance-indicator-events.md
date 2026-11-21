## Plan
- #160: KPI events (manifesto's bold KPIs) in a per-machine SQLite EventDatabase, migrated by one Migration class per change; git checks on CI.
## Done
- Branch commit pushed; draft PR #160. Local tests + pre-commit hooks pass.
## Next
- CI result (first run with fetch-depth 0 and alembic); user's review.
- Follow-ups outside this PR: record events from the hooks/review script, root path for the file, KPI queries, shipping events off the machines.
