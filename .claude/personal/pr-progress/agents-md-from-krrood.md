## Plan
- Adopt krrood's agent instructions: repo rules as `Section`s in root `agent_rules.py`, `krrood agents-md` writes `AGENTS.md`, `CLAUDE.md` = `@AGENTS.md` + descriptive prose.
- User's choices: follow krrood on Co-Authored-By (use "Made with AI assistance"), and on running tests a few modules at a time; pre-commit hooks krrood-format, krrood-check, krrood-agents-md.
## Done
- Branch agents-md-from-krrood from main 7170e9a.
## Next
- Test that AGENTS.md is current (first); agent_rules.py; regenerate; slim CLAUDE.md; operator skill pointer to AGENTS.md; .pre-commit-config.yaml; requirements; draft PR.
