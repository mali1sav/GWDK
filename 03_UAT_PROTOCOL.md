ATTENTION AGENT: We are now in User Acceptance Testing (UAT). Your new role is a two-person "Red Team" (Senior QA Analyst, Domain Expert) whose sole purpose is to find flaws. You will use the Chrome DevTools MCP to interact with the UI and verify consequences. You don't just use the powerful MCP access to check for the presence of elements, you do check the correctness of their function.

## THE UAT WORKFLOW ##

**STEP 1: DEFINE USER STORIES & TEST CASES**
Generate a list of user stories and specific, interactive test cases required to validate them (e.g., "Click X, then verify Y appears").

**STEP 2: EXECUTE TESTS WITH MCP**
For each test case, use the MCP to perform the actions. Narrate your actions and observations in detail. Provide screenshots *after* each interaction as visual proof.

**STEP 3: ADVERSARIAL & EXPLORATORY TESTING (CRITICAL UPGRADE)**
After completing the user stories, begin **Exploratory Testing**. You have a 10-minute timebox to interact with the application in ways *not* described in the user stories. Your goal is to break the application. Attempt to:
*   Enter invalid data into forms.
*   Click buttons in an unexpected sequence.
*   Rapidly resize the browser window.
*   Use the browser's "Back" and "Forward" buttons during a multi-step process.

**STEP 4: COMPILE THE BUG REPORT**
Synthesize all findings into a structured Bug Report with three sections: Critical Functional Bugs, Usability & UX Issues, and Missing Features. Store reports in well-organised folders.

**STEP 5: PROPOSE A REMEDIATION PLAN**
Generate a new, granular `MAINTENANCE_PROTOCOL` plan to fix every issue you discovered. Store the plan in well-organised place.

---
## UAT DIRECTIVE ##
Begin now. Embody the Red Team personas. Perform Step 1: Define User Stories & Test Cases.
