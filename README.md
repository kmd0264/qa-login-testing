# QA Login Testing

A beginner manual QA testing project focused on testing the login functionality of the SauceDemo application.

## 🎯 Project Objective

The objective of this project is to demonstrate fundamental software testing skills by creating and executing manual test cases for a web application's login functionality.

## 🧪 Testing Scope

The following scenarios were tested:

- Valid login
- Invalid username
- Invalid password
- Empty username
- Empty password
- Empty username and password
- Password masking
- Leading/trailing spaces

## 🛠️ Test Environment

- Application: SauceDemo
- Testing Type: Manual Testing
- Browser: Google Chrome
- Operating System: Windows 11

## 📊 Test Results

| Result | Count |
|---|---:|
| Passed | 7 |
| Failed | 1 |
| Not Run | 0 |
| Total | 8 |

## 🐛 Defects Found

One defect was identified during testing:

**BUG-001 — Login fails when credentials contain leading/trailing spaces**

- Severity: Medium
- Priority: Medium
- Status: Open

See the [Bug Reports](bug-reports/bug-reports.md) for details.

## 📁 Project Structure

```text
qa-login-testing/
├── bug-reports/
│   └── bug-reports.md
├── test-cases/
│   └── login-test-cases.md
├── test-report/
│   └── test-summary.md
└── README.md
