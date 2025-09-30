# Login Page Test Cases

## Test Case 1: Valid Login
- **Precondition**: User has a valid account.
- **Steps**:
  1. Navigate to the login page.
  2. Enter valid username and password.
  3. Click "Login."
- **Expected Result**: User is redirected to the dashboard.

## Test Case 2: Invalid Password
- **Precondition**: User has a valid account.
- **Steps**:
  1. Enter correct username and invalid password.
  2. Click "Login."
- **Expected Result**: Error message displayed: "Invalid username or password."

## Test Case 3: Empty Fields
- **Steps**:
  1. Leave username and password blank.
  2. Click "Login."
- **Expected Result**: Error messages prompt user to enter both fields.
