ATTENTION AGENT: You have completed the initial build of the new "Automated Shot Director" and "Visual Storyboard" UI.

We will now begin the validation phase. You will operate under the **User Acceptance Testing (UAT) Protocol**. Your new role is a two-person "Red Team" (Senior QA Analyst, Domain Expert) whose sole purpose is to find flaws in the implementation you just created.

## THE UAT WORKFLOW ##

You will follow this workflow to generate a definitive Bug Report.

**STEP 1: DEFINE USER STORIES & TEST CASES**
Generate a list of user stories and the specific, interactive test cases required to validate the new Step 6 workflow. The primary user story is: "As a video creator, I want to click the 'Generate Visual Storyboard' button and see a complete, visually populated storyboard that I can then review and refine."

**STEP 2: EXECUTE TESTS WITH MCP**
For each test case, you will use the Chrome DevTools MCP to perform the actions. You must focus on the **visual output**. Narrate your actions and your observations in detail. **Take a screenshot of the Visual Storyboard after generation.**

**STEP 3: EVALUATE USABILITY & DESIGN**
As the Domain Expert, you will provide a critical review.
*   **Core Functionality:** Does the storyboard actually contain *images* or *video thumbnails*, or just text descriptions?
*   **User Effort:** Did the "single click" successfully automate the visual creation, or is the user still required to do manual work?
*   **Completeness:** Is the feature "developer complete" or truly "user ready"?

**STEP 4: COMPILE THE BUG REPORT**
Synthesize all your findings into a single, structured Bug Report. The report must have a section for "Critical Functional Bugs." Be brutally honest about the state of the visual generation.

**STEP 5: PROPOSE A REMEDIATION PLAN**
Based on the bug report, you will generate a new, final, hyper-granular `MAINTENANCE_PROTOCOL` plan to fix every single issue you discovered. The primary goal of the remediation plan will be to **fully implement the backend image and video generation logic** and connect it to the new UI.

---
## UAT DIRECTIVE ##

Begin now. Embody the Red Team personas. Perform Step 1: Define User Stories & Test Cases for the new Visual Storyboard feature. Pay extremely close attention to whether actual visual assets are generated and displayed.
