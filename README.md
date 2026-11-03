# End-to-End UI & API Automation Testing Framework

An automation testing framework built using **Playwright and JavaScript** to perform end-to-end UI testing and API testing. The project focuses on validating application functionality, identifying defects, and ensuring application reliability through reusable automated test cases.

## Overview

This framework combines UI and API automation testing to validate application behaviour across different testing scenarios.

It is designed to demonstrate practical QA automation concepts, including:
- End-to-end UI testing
- REST API testing
- Functional and regression testing
- Page Object Model (POM)
- Test assertions and validations
- Automated test reporting
- Continuous Integration and Continuous Deployment (CI/CD)

## Tech Stack

| Technology | Purpose |
|---|---|
| JavaScript | Programming language |
| Playwright | UI and API automation |
| Node.js | Runtime environment |
| Playwright Test | Test execution and assertions |
| HTML Reporter | Test execution reports |
| Git & GitHub | Version control |
| GitHub Actions | CI/CD automation |

## Key Features

### 1. UI Automation Testing
- Automated browser-based testing using Playwright.
- Validation of application navigation and user interactions.
- Login and form validation scenarios.
- Positive and negative test scenarios.
- Reusable page objects following the Page Object Model (POM).

### 2. API Automation Testing
- Automated testing of REST API endpoints.
- Validation of HTTP response status codes.
- Request and response body verification.
- Positive and negative API test scenarios.
- Validation of API functionality across different HTTP methods.

### 3. Regression Testing
- Reusable automated test cases.
- Validation of existing functionality after application changes.
- Structured test execution for identifying unexpected failures.

### 4. Test Reporting
- HTML test reports.
- Execution status and failure details.
- Test results for debugging and analysis.

### 5. CI/CD Integration
- GitHub Actions workflow for automated test execution.
- Integration with GitHub repositories.
- Test execution triggered through configured push and pull request events.

## Project Structure

```text
End-to-End-UI-API-Automation-Testing-Framework/
│
├── tests/
│   ├── ui/
│   │   └── UI test cases
│   │
│   └── api/
│       └── API test cases
│
├── pages/
│   └── Page Object Model classes
│
├── fixtures/
│   └── Reusable test fixtures
│
├── utils/
│   └── Helper functions
│
├── .github/
│   └── workflows/
│       └── playwright.yml
│
├── playwright.config.js
├── package.json
├── .gitignore
└── README.md
```

*The structure may vary depending on the final implementation.*

## Installation & Setup

### Prerequisites

- Node.js (LTS version recommended)
- npm
- Git

### 1. Clone the Repository

```bash
git clone https://github.com/munshimanasvi24/End-to-End-UI-API-Automation-Testing-Framework.git
```

### 2. Navigate to the Project Directory

```bash
cd End-to-End-UI-API-Automation-Testing-Framework
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Install Playwright Browsers

```bash
npx playwright install
```

## Running Tests

### Run All Tests

```bash
npx playwright test
```

### Run UI Tests

```bash
npx playwright test tests/ui
```

### Run API Tests

```bash
npx playwright test tests/api
```

### Run Tests in Headed Mode

```bash
npx playwright test --headed
```

### Run Tests in Debug Mode

```bash
npx playwright test --debug
```

### Generate and View HTML Report

```bash
npx playwright show-report
```

*Commands should be adjusted if your project uses different test folder names or npm scripts.*

## Testing Coverage

| Testing Area | Scenarios |
|---|---|
| UI Testing | Navigation, user interactions, login and form validation |
| API Testing | GET, POST, PUT and DELETE requests |
| Functional Testing | Expected application behaviour |
| Negative Testing | Invalid inputs and unsuccessful requests |
| Regression Testing | Revalidation of existing functionality |
| Reporting | Test execution results and failure analysis |

## CI/CD Pipeline

The project uses GitHub Actions to automate test execution.

The configured workflow can:
- Trigger automated tests on code pushes.
- Execute tests on pull requests.
- Install project dependencies.
- Run the Playwright test suite.
- Generate test execution results.

## Skills Demonstrated

- JavaScript
- Playwright Automation
- UI Testing
- REST API Testing
- Functional Testing
- Regression Testing
- Page Object Model (POM)
- Test Case Design
- Assertions and Validations
- HTML Test Reporting
- Git & GitHub
- GitHub Actions
- CI/CD Fundamentals
- Debugging and Defect Identification

## Future Enhancements

- Cross-browser testing across Chromium, Firefox and WebKit.
- Parallel test execution.
- API schema validation.
- Test data management.
- Environment-based configuration.
- Enhanced test reporting and failure analysis.
- Integration with additional CI/CD tools.

## Author

**Manasvi Munshi**

GitHub: [@munshimanasvi24](https://github.com/munshimanasvi24)

LinkedIn: [Manasvi Munshi](https://www.linkedin.com/in/manasvimunshi/)
