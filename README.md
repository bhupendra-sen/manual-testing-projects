The repository README provides an overview and instructions for the Swag Labs(Sauce Demo) QA projects
.

Overview: This project contains manual test documentation for the Swag Labs (Sauce Demo) web application. It includes the test plan, test cases, bug report template, and summary reports for validating the application’s functionality on Google Chrome.

Project Structure:

TestPlan.md – The overall test plan (this document).

TestCases/ – Directory containing test case tables (organized by feature).

BugReportTemplate.md – Generic bug report template.
TestSummaryReport.md – Final test execution summary.
README.md – This file (project overview and instructions).

How to Execute Tests: To perform testing, open Google Chrome and navigate to https://www.saucedemo.com. Use the test cases in TestCases/ as a guide: follow each step, verify expected results, and record the outcome. For each issue found, submit a bug using the Bug Report Template. No automation is required; this is a manual test suite.

Tools Used: Testing is done manually in Chrome. We use standard tools like screenshots or dev console logs for evidence. Bugs are tracked in JIRA/GitHub issues. Documentation is maintained in Markdown and Excel.

Test Scope: The test suite covers full functional testing of Swag Labs on Chrome, specifically:
Login page (authentication scenarios)
Inventory/product display (item listing, sorting)
Cart page (add/remove items, navigation)
Checkout process (checkout step 1, checkout step 2, completion)

Each feature is validated as per the test cases.
