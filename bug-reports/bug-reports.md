# Bug Reports

## BUG-001 — Login fails when credentials contain leading/trailing spaces

### Summary

The login system rejects otherwise valid credentials when leading or trailing spaces are entered.

### Severity

Medium

### Priority

Medium

### Environment

- Application: SauceDemo
- Browser: Google Chrome
- Operating System: Windows 11
- Testing Type: Manual Testing

### Preconditions

A valid SauceDemo username and password are available.

### Steps to Reproduce

1. Open the SauceDemo login page.
2. Enter a valid username with leading/trailing spaces.
3. Enter a valid password with leading/trailing spaces.
4. Click **Login**.

### Test Data

**Username:**
`  standard_user  `

**Password:**
`  secret_sauce  `

### Expected Result

The system should ignore leading and trailing spaces and successfully authenticate the user.

### Actual Result

The system rejects the credentials and displays:

`Epic sadface: Username and password do not match any user in this service`

### Status

Open

### Related Test Case

TC-008 — Login with leading/trailing spaces
