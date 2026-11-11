## Plan
- Make the package work with krrood 26.10 from cram2 main (#145): pass keyword-only arguments by name.
## Done
- Draft PR #146 (bug label, f88c36f): all call sites and overrides fixed. Against cram2 main 2616c8a1e8: 958 passed, 8 skipped. Against old 26.7 checkout: 7 fail (the overrides), expected.
## Next
- User's review; CI on the PR. Operator installation: rerun update_installation.sh after merge.
