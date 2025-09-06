Swag Labs QA Projects

A collection of manual Quality Assurance (QA) artifacts for the Swag Labs (Sauce Demo) web application. Includes test plan, test cases, bug report template, and summary reports to validate functionality on Google Chrome.

📌 Table of Contents

About

Repository Structure

Installation

Usage

Tools Used

Test Scope

Contributing

License

📖 About

This repository contains manual testing documentation for the Swag Labs Demo App
.

Deliverables include:

✅ Test Plan – scope, objectives, and strategy

✅ Test Cases – detailed positive & negative scenarios

✅ Bug Report Template – structured issue logging

✅ Test Summary Report – execution results & findings

Designed for QA learners and professionals to practice creating, organizing, and maintaining test artifacts.

📂 Repository Structure
SwagLabs-QA/
│-- TestPlan.md              # The overall test plan
│-- TestCases/               # Directory containing feature-based test case tables
│-- BugReportTemplate.md     # Generic bug report template
│-- TestSummaryReport.md     # Final execution summary
│-- README.md                # Project documentation

⚙️ Installation

Clone this repository:

git clone https://github.com/bhupendra-sen/manaual-testing-projects.git
cd manaual-testing-projects


Open the Markdown (.md) or Excel test case files in your preferred tool (VS Code, Excel, Google Sheets).

▶️ Usage

View Test Cases: Open the TestCases/ directory to see test cases organized by feature (Login, Inventory, Cart, Checkout).

Execute Tests:

Open Google Chrome.

Navigate to Swag Labs Demo
.

Follow each test case step, verify the expected result, and log outcomes.

Log Defects: Use the BugReportTemplate.md to record bugs with steps, expected vs. actual result, and severity/priority.

Review Results: After execution, see the TestSummaryReport.md for pass/fail metrics and key findings.

🛠 Tools Used

Browser: Google Chrome (manual execution)

Documentation: Markdown, Excel

Bug Tracking: JIRA / GitHub Issues

Supporting Tools: Screenshots, Chrome DevTools

🎯 Test Scope

This test suite validates core e-commerce flows of Swag Labs, including:

🔑 Login Page – authentication scenarios (valid, invalid, locked user, empty fields)

📦 Inventory Page – product listing, sorting, add/remove to cart

🛒 Cart Page – view, continue shopping, checkout navigation

✅ Checkout Process – Step One (user info), Step Two (overview), Completion (order confirmation)

Each feature is verified through positive and negative test cases.

🤝 Contributing

Contributions are welcome! To contribute:

Fork this repo.

Create a branch:

git checkout -b feature/new-testcases


Add or update test case files.

Commit & push changes.

Open a Pull Request.
