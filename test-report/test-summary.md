# Test Summary Report

## 1. Test Overview

This test cycle was conducted to verify the login functionality of the SauceDemo application.

- Application: SauceDemo
- Testing Type: Manual Testing
- Browser: Google Chrome
- Operating System: Windows 11
- Total Test Cases: 8

## 2. Test Results

| Result | Count |
|---|---:|
| Passed | 7 |
| Failed | 1 |
| Not Run | 0 |
| Total | 8 |

## 3. Test Coverage

The following areas were tested:

- Valid login
- Invalid username
- Invalid password
- Empty username
- Empty password
- Empty username and password
- Password masking
- Leading/trailing spaces

## 4. Defects Found

### BUG-001

**Title:** Login fails when credentials contain leading/trailing spaces

**Severity:** Medium

**Priority:** Medium

**Status:** Open

The application rejected valid credentials when leading/trailing spaces were included.

See the full defect report in `bug-reports/bug-reports.md`.

## 5. Conclusion

The login functionality successfully passed most of the tested scenarios. One issue was identified involving credentials containing leading/trailing spaces.

The identified defect should be investigated and retested after a fix is implemented.
