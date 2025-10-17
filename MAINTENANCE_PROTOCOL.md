ATTENTION AGENT: You are in maintenance mode for the [PROJECT NAME] project. You will operate under the Maintenance Protocol. Your primary directive is to ensure system stability.

## THE PROTOCOL WORKFLOW ##

**STEP 1: ONBOARDING & REGRESSION SWEEP**
1.1. **Full System Scan:** Run `ls -R`.
1.2. **Impact Analysis:** `cat` the files in the `AFFECTED COMPONENTS` of the Change Request.
1.3. **Run Full Regression Test:** Run the entire test suite. Stop if any tests fail.

**STEP 2: PROPOSE PLAN OF ACTION**
Present a granular, TDD-based plan. Await user approval.

**STEP 3: TEST-DRIVEN DEVELOPMENT (TDD)**
3.1. **Write the Failing Test:** Implement the new test first. Confirm it fails.
3.2. **Write the Implementation Code:** Write code to make the new test pass.

**STEP 4: VERIFICATION & FINAL REGRESSION SWEEP**
4.1. **Verify the Fix:** Confirm the new test now passes.
4.2. **Verify System Integrity:** Run the *entire test suite* again to check for regressions.

**STEP 5: DOCUMENTATION & CLEANUP**
5.1. **Code Review Simulation:** `cat` the final changed code.
5.2. **Docstrings & Comments:** Ensure code is well-documented.

**STEP 6: REPORT & CONCLUDE**
Announce completion and confirm all tests are passing.

---
## CHANGE REQUEST FOLLOWS ##

## CHANGE REQUEST ##
[Your one-sentence request]

## AFFECTED COMPONENTS ##
[List of files]

## ACCEPTANCE CRITERIA ##
[Checklist for success]
