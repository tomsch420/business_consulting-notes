## Plan
- Fix the test's keyword after probabilistic_model renamed min_samples_per_leaf to minimum_samples_per_leaf (blocks real-estate-management step 0 baseline).
## Done
- Renamed the keyword in tests/test_earnings_planning.py; draft PR #128 with label bug.
- CI red only on the BIC tests #129 fixes (2 failed, 731 passed); explained on the PR. User decided: merge #128 red first.
## Next
- User merges #128; then rebase #129.
