# Cypress-Exercise-Lab

**Developed at devCodeCamp**

A hands-on lab building end-to-end (E2E) test scripts with Cypress. This project focuses on automating user flows, verifying application behavior, and ensuring quality through browser-based E2E testing.

---

## Features

- End-to-end (E2E) automated testing
- Simulates real user actions (navigation, input, clicks, assertions)
- Modern test structure using Cypress test runner
- Easy-to-read scripts for robust and maintainable tests

---

## Technologies Used

- Cypress.io

---

## Installation

1. **Clone the repository:**
    ```
    git clone https://github.com/thompsonmikej/Cypress-Exercise-Lab.git
    cd Cypress-Exercise-Lab
    ```
2. **Install dependencies:**
    ```
    npm install
    ```

3. **Start Cypress Test Runner:**
    ```
    npx cypress open
    ```
    - Select your test file from the Cypress interface, or run tests from the command line using `npx cypress run`.

---

## Usage

- Write or modify tests in the `cypress/e2e/` directory.
- Tests typically include:
    - Visiting a page (`cy.visit()`)
    - Querying and interacting with elements (`cy.get()`, `.click()`, `.type()`)
    - Asserting the expected outcomes (`.should()`, `.contains()`).
- View results and debug directly in the Cypress Test Runner window.

---

## Challenges & Lessons Learned

- Learned the process of authoring and running E2E tests, covering setup, action, and validation phases.
- Experienced how Cypress scripts mirror real user behavior, providing reliable quality assurance.
- Improved skills in structuring, debugging, and maintaining automated tests in a modern web dev workflow.

---

## Future Improvements

- Expand coverage to include complex user workflows and edge cases.
- Integrate tests into Continuous Integration (CI) pipelines for automated deployments.
- Experiment with advanced Cypress features such as custom commands and fixtures.

## Author

Feel free to reach out or connect:

**Michael Thompson**  
https://www.linkedin.com/in/thompsonmikej  
