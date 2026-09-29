# Login Test Cases

## Test Objective

Verify that the login functionality works correctly with valid and invalid user credentials.

## Test Environment

- Application: Login System
- Testing Type: Manual Testing
- Browser: Google Chrome
- Operating System: Windows 11

## Test Cases

| Test ID | Test Scenario | Test Steps | Expected Result | Status |
|---|---|---|---|---|
| TC-001 | Login with valid credentials | Enter valid username and password, then click Login | User should be successfully logged in | Pass |
| TC-002 | Login with incorrect password | Enter valid username and incorrect password, then click Login | An error message should be displayed | Pass |
| TC-003 | Login with incorrect username | Enter incorrect username and valid password, then click Login | An error message should be displayed | Pass |
| TC-004 | Login with both fields empty | Leave username and password empty, then click Login | Validation messages should be displayed | Pass |
| TC-005 | Login with empty password | Enter a valid username and leave password empty | Password validation message should be displayed | Pass |
| TC-006 | Login with empty username | Leave username empty and enter a valid password | Username validation message should be displayed | Pass |
| TC-007 | Password should be hidden | Enter a password into the password field | Password characters should be masked | Not Run |
| TC-008 | Login with leading/trailing spaces | Enter credentials with spaces before or after the values | System should handle spaces correctly | Not Run |
