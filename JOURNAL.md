## Week 7 — Issue selection

**Issue link:** https://github.com/ascherj/pathreview/issues/109

**Issue title:** Test coverage for core/services/review_service.py is below 40%
 #109

**Tier:** [ ] Tier 1  [X] Tier 2  [ ] Tier 3

**Problem summary:**
The review service handles the app's core review process, but most of it isn't tested — coverage is under 40%. To fix this, I'll write unit tests in tests/unit/test_review_service.py that cover the main scenarios: when things work correctly, when part of the process fails, and when it all fails. This will make the service more reliable and easier to maintain.

**Reasoning:**
This is a Tier 2 issue, which fits since I wanted a bit more challenge than a Tier 1 fix. I found review_service.py and tests/unit/test_review_service.py, read through the existing service logic and test structure, and feel confident I understand the main execution paths (success, partial failure, full failure) well enough to write tests without getting stuck. Several other students have also claimed this issue, but since claims are non-exclusive and grading is based on my own work, I'm comfortable with that, and I don't see any blockers. I'm estimating 5-7 hours which fits within the Week 8-9 window.

**Branch name:** test/109-review-service-coverage

**Setup confirmation:** [Yes ] App runs locally at localhost:5173

**Cohort ledger:** [Yes ] Issue added to cohort ledger