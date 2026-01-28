# AutomationExercise – Authentication Test Cases

This repository contains **manual test cases** for the **Authentication feature (Register, Login, Logout)** of the AutomationExercise web application.

Test cases are created based on **actual UI flow and system behavior** observed on the application.

---

## Application Information
- Application: AutomationExercise
- URL: https://automationexercise.com
- Module: Authentication (Register, Login, Logout)
- Test Type: Manual Testing

---

## Test Case Organization
Test cases are grouped using a simple and consistent structure:

- **TS.Auth.001** – Register
- **TS.Auth.002** – Login
- **TS.Auth.003** – Logout  
- Test Case ID format: `TS.Auth.XXX.XXX`

Each test case contains:
- Pre-condition
- Test data
- Test steps
- Expected result (test case level)
- Actual result
- Status (Pass / Fail)
- Remarks

---

## Test Coverage
### Register
- Successful user registration
- Mandatory field validation
- Existing email validation
- Invalid email format handling
- Optional field behavior
- Account deletion flow

### Login
- Successful login
- Invalid credential handling
- Empty field validation
- Session behavior after refresh or navigation

### Logout
- Successful logout
- Session invalidation
- Access behavior after logout
- Direct URL access behavior

---

## Test Case File
The test cases are documented in an Excel file:

- **Google Drive**:  
  _[Paste your Google Drive link here]_

- **File name**:  
  `TC_AutomationExercise_Auth_FINAL_TSAuth_Numbering.xlsx`

---

## Notes
- Expected results are written according to **actual messages and navigation flow** shown by the application.
- Examples of system messages used in validation:
  - `ACCOUNT CREATED!`
  - `Email Address already exist!`
  - `Your email or password is incorrect!`
  - `Logged in as <username>`
  - `ACCOUNT DELETED!`
