Mini Playwright Project
A minimal Playwright setup using the Playwright Test Runner to automate the React TodoMVC application.
Includes a single end‑to‑end test demonstrating task creation, filtering, completion, and cleanup.

1. Install Dependencies
Code
npm install
npx playwright install
2. Run the TodoMVC Test
Code
npx playwright test tests/todo.spec.js
Run all tests:

Code
npx playwright test
Run in UI mode:

Code
npx playwright test --ui
3. What the Test Does
Opens TodoMVC React

Adds multiple todo items

Marks selected items as completed

Switches between All, Active, and Completed filters

Validates visible tasks

Clears completed tasks

4. Project Structure
Code
mini-playwright-project/
│
├── tests/
│   └── todo.spec.js
│
├── playwright.config.js
├── package.json
├── package-lock.json
└── .gitignore
5. Notes
Requires Node.js ≥ 20

Uses @playwright/test as the test runner

Browsers are installed via npx playwright install

No sensitive files are included in the repo

