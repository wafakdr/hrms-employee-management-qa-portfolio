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

## TC_004 – Verify Phone Number Format Validation

| Field | Details |
|---|---|
| Test Case ID | TC_004 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify phone number format validation |
| Module | Employee Registration |
| Priority | High |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Name: John Smith; Email: john.smith@example.com; Phone: 12345ABC; Joining Date: 2026-11-16 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter a valid employee name. 3. Enter a valid email address. 4. Enter an invalid phone number (12345ABC). 5. Enter a valid joining date. 6. Click Submit/Register. |
| Expected Result | The system should reject the invalid phone number and display an appropriate validation message. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |

---

## TC_005 – Verify Duplicate Email Address Validation

| Field | Details |
|---|---|
| Test Case ID | TC_005 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify duplicate email address validation |
| Module | Employee Registration |
| Priority | High |
| Test Type | Negative Testing |
| Preconditions | An employee with the test email address already exists in the system. |
| Test Data | Name: Jane Smith; Email: existing.employee@example.com; Phone: 9876543211; Joining Date: 2026-11-16 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter valid employee details. 3. Enter an email address that is already registered. 4. Complete all other mandatory fields. 5. Click Submit/Register. |
| Expected Result | If unique email addresses are required, the system should prevent duplicate registration and display an appropriate error message. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |
| Remarks | Confirm the duplicate email business rule. |

---

## TC_006 – Verify Employee Name Validation

| Field | Details |
|---|---|
| Test Case ID | TC_006 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify employee name validation |
| Module | Employee Registration |
| Priority | Medium |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Name: 123456; Email: john.smith@example.com; Phone: 9876543210; Joining Date: 2026-11-16 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter numbers only in the employee name field. 3. Enter valid information in the remaining mandatory fields. 4. Click Submit/Register. |
| Expected Result | If numeric-only employee names are not allowed, the system should reject the input and display an appropriate validation message. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |
| Remarks | Confirm the permitted employee name characters. |

---

## TC_007 – Verify Mandatory Joining Date Validation

| Field | Details |
|---|---|
| Test Case ID | TC_007 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify mandatory joining date validation |
| Module | Employee Registration |
| Priority | High |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Valid employee name, email and phone number; Joining Date: Empty |
| Test Steps | 1. Open the Employee Registration form. 2. Enter a valid employee name. 3. Enter a valid email address. 4. Enter a valid phone number. 5. Leave the joining date field empty. 6. Click Submit/Register. |
| Expected Result | The system should prevent registration and display an appropriate validation message for the missing joining date. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |

---

## TC_008 – Verify Past Joining Date Validation

| Field | Details |
|---|---|
| Test Case ID | TC_008 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify past joining date validation |
| Module | Employee Registration |
| Priority | Medium |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Name: John Smith; Email: john.smith@example.com; Phone: 9876543210; Joining Date: 2026-11-12 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter a valid employee name. 3. Enter a valid email address. 4. Enter a valid phone number. 5. Select a past joining date (2026-11-12). 6. Click Submit/Register. |
| Expected Result | If past joining dates are not permitted, the system should reject the date and display an appropriate validation message. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |
| Remarks | Confirm whether past joining dates are permitted. |

## TC_009 – Verify Individual Mandatory Field Validation

| Field | Details |
|---|---|
| Test Case ID | TC_009 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify individual mandatory field validation |
| Module | Employee Registration |
| Priority | High |
| Test Type | Negative Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Leave one mandatory field empty at a time while providing valid values for the other fields. |
| Test Steps | 1. Open the Employee Registration form. 2. Enter valid information in all mandatory fields except Employee Name. 3. Click Submit. 4. Repeat the test by leaving Email Address empty. 5. Repeat for Phone Number and Date of Joining. |
| Expected Result | Registration should be prevented whenever an individual mandatory field is empty. An appropriate validation message should identify the missing field. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |

---

## TC_010 – Verify Employee Data Persistence

| Field | Details |
|---|---|
| Test Case ID | TC_010 |
| Test Scenario ID | To be assigned |
| Test Case Title | Verify employee data persistence after registration |
| Module | Employee Registration |
| Priority | High |
| Test Type | Positive Testing |
| Preconditions | Admin user is logged in and Employee Registration form is accessible. |
| Test Data | Name: Test Employee; Email: test.employee@example.com; Phone: 9876543210; Joining Date: 2026-11-16 |
| Test Steps | 1. Open the Employee Registration form. 2. Enter valid employee details. 3. Click Submit/Register. 4. Navigate to the employee list or employee details page. 5. Search for the newly registered employee. 6. Compare the displayed information with the submitted data. |
| Expected Result | The employee record should be saved successfully. The employee list or details page should display the same information that was submitted. |
| Actual Result | To be updated during test execution. |
| Status | Not Executed |
