# HRMS Employee Registration – Test Cases

## TC_001 – Verify Employee Registration with Valid Information

| Field | Details |
|---|---|
| Test Case ID | TC_001 |
| Test Scenario ID | TS_002 |
| Test Case Title | Verify employee registration with valid information |
| Module | Employee Registration |
| Priority | High |
| Test Type | Positive Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Name: John Smith; Email: john.smith@example.com; Phone: 9876543210; Joining Date: 2026-11-16 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter a valid employee name. 3. Enter a valid email address. 4. Enter a valid phone number. 5. Select a valid joining date. 6. Click the Submit/Register button. |
| Expected Result | Employee should be registered successfully, and an appropriate confirmation message should be displayed. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |



## TC_002 – Verify Mandatory Field Validation

| Field | Details |
|---|---|
| Test Case ID | TC_002 |
| Test Scenario ID | TS_003 |
| Test Case Title | Verify mandatory field validation |
| Module | Employee Registration |
| Priority | High |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Leave all mandatory fields empty. |
| Test Steps | 1. Open the Employee Registration form. 2. Leave all mandatory fields empty. 3. Click the Submit/Register button. |
| Expected Result | The system should prevent employee registration and display appropriate validation messages for all mandatory fields. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |

## TC_003 – Verify Email Address Format Validation

| Field | Details |
|---|---|
| Test Case ID | TC_003 |
| Test Scenario ID | TS_005 |
| Test Case Title | Verify email address format validation |
| Module | Employee Registration |
| Priority | High |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Employee Name: John Smith; Email: john123; Phone: 9876543210; Joining Date: 2026-11-16 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter a valid employee name. 3. Enter an invalid email address (john123). 4. Enter a valid phone number. 5. Enter a valid joining date. 6. Click Submit/Register. |
| Expected Result | The system should reject the invalid email address, display an appropriate validation message, and prevent employee registration. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |

