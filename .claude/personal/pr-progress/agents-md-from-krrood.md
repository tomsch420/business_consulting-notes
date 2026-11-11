## Plan
- Adopt krrood's agent instructions: repo rules in root `agent_rules.py`, generated `AGENTS.md`, `CLAUDE.md` = `@AGENTS.md` + descriptive prose.
## Done
- Draft PR #147 (06060ea). Tests against cram2 main 2616c8a1e8: agent_instructions+answered_file 8 passed, operator_workspace 25 passed. krrood check clean on staged lines.
- User chose: no Co-Authored-By (krrood rule), tests a few modules at a time, hooks format+check+agents-md.
## Next
- User's review; CI. Local test venv's krrood is 288 commits behind cram main: test_agent_instructions needs it updated.
