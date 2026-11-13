# HRMS Employee Registration – Test Plan

## 1. Project Overview

**Project Name:** HRMS Employee Management System

**Feature Under Test:** Employee Registration

**Document Type:** Software Test Plan

**Testing Type:** Manual Testing

**Project Description:**

This project focuses on testing the Employee Registration feature of a fictional Human Resource Management System (HRMS).

The feature allows administrators to register new employees by entering their personal and employment information.

The purpose of this testing activity is to verify that the registration form works correctly, validates user inputs, prevents invalid data, and provides appropriate error messages.
## 2. Testing Objectives

The main objectives of testing the Employee Registration feature are:

1. Verify that users can register employees with valid information.
2. Verify that mandatory fields cannot be left empty.
3. Verify that email addresses follow the required format.
4. Verify that phone numbers follow the defined validation rules.
5. Verify that duplicate employee email addresses are handled correctly.
6. Verify that joining dates follow the defined business rules.
7. Verify that appropriate error messages are displayed for invalid inputs.
8. Ensure that valid employee information is saved successfully.

   ## 3. Scope of Testing

### 3.1 In Scope

The following areas will be tested:

1. Employee registration form accessibility.
2. Mandatory field validation.
3. Employee name input validation.
4. Email address format validation.
5. Phone number validation.
6. Date of Joining validation.
7. Error messages for invalid inputs.
8. Successful employee registration.
9. Duplicate employee email handling.
10. Data submission and confirmation messages.

### 3.2 Out of Scope

The following areas are excluded from this testing phase:

1. Employee login and authentication.
2. Attendance management.
3. Leave management.
4. Payroll processing.
5. Employee profile editing and deletion.
6. Performance management.

   ## 4. Test Approach

The Employee Registration feature will be tested using a combination of manual testing techniques.

### 4.1 Testing Techniques

1. **Positive Testing:** Verify that the form accepts valid employee information.
2. **Negative Testing:** Verify that the form rejects invalid or missing information.
3. **Boundary Value Analysis:** Test minimum and maximum input limits, such as phone number length.
4. **Equivalence Partitioning:** Divide input data into valid and invalid groups and test representative values.
5. **Exploratory Testing:** Explore the form to identify unexpected behaviour and potential defects.

### 4.2 Test Execution

1. Review the available requirements and identify unclear business rules.
2. Prepare test scenarios and test cases.
3. Execute test cases using different input combinations.
4. Record actual results and compare them with expected results.
5. Report defects with clear steps to reproduce.
6. Retest fixed defects and perform regression testing where applicable.
 ## 5. Test Environment

### 5.1 Hardware and Software

- **Operating System:** Windows 11


- **Browser:** Google Chrome
- **Testing Type:** Manual Testing
- **Test Application:** Fictional HRMS Employee Management System
- **Test Data:** Sample employee information created specifically for testing.

### 5.2 Testing Tools

- **GitHub:** To maintain and publish testing documentation.
- **Microsoft Excel / Google Sheets:** To prepare and track test cases.
- **Jira:** To document and track defects (if available).
- **Browser Developer Tools:** To inspect browser behaviour when required.

### 5.3 Test Data

Only fictional employee information will be used during testing. No real personal or confidential employee data will be included.

## 6. Entry and Exit Criteria

### 6.1 Entry Criteria

Testing can begin when:

1. The Employee Registration requirements are available.
2. The test scenarios and test cases are prepared.
3. The test environment is ready.
4. Valid and invalid test data is available.
5. The application is accessible for testing.

### 6.2 Exit Criteria

Testing can be considered complete when:

1. All planned test cases have been executed.
2. All critical and high-priority defects have been reported.
3. Failed test cases have been documented.
4. Fixed defects have been retested.
5. No unresolved critical defects remain, or remaining issues are formally documented.
6. A test summary report has been prepared.

   ## 7. Test Deliverables

The following deliverables will be prepared during the Employee Registration testing process:

1. **Test Plan:** Document describing the testing scope, objectives, approach, and schedule.
2. **Test Scenarios:** High-level conditions or functionalities to be tested.
3. **Test Cases:** Detailed steps, test data, and expected results.
4. **Test Data:** Valid, invalid, and boundary data used during testing.
5. **Defect Reports:** Records of identified bugs, including steps to reproduce, actual results, and expected results.
6. **Test Execution Report:** Summary of passed, failed, and blocked test cases.
7. **Test Summary Report:** Final overview of testing activities, results, and outstanding defects.

   ## 8. Test Execution and Reporting

### 8.1 Test Execution

1. Execute test cases according to the defined test scenarios.
2. Enter the required test data for each test case.
3. Compare actual results with expected results.
4. Mark each test case as Pass, Fail, or Blocked.
5. Record screenshots or other evidence where required.

### 8.2 Defect Reporting

When a defect is identified:

1. Create a defect report with a clear title and description.
2. Provide steps to reproduce the issue.
3. Mention the expected and actual results.
4. Assign an appropriate severity and priority.
5. Attach screenshots or supporting evidence.
6. Track the defect until it is fixed and retested.

### 8.3 Test Reporting

A test execution report will include:

- Total number of test cases.
- Number of passed test cases.
- Number of failed test cases.
- Number of blocked test cases.
- Open and closed defects.
- Overall testing status.

  ## 9. Risks and Mitigation

The following risks may affect the testing of the Employee Registration feature:

| Risk | Mitigation |
|---|---|
| Requirements are unclear or incomplete. | Clarify requirements with the relevant stakeholders before testing. |
| Test environment is unavailable. | Report the issue and coordinate with the technical team. |
| Test data is insufficient. | Prepare valid, invalid, and boundary test data in advance. |
| Defects are discovered during testing. | Document defects with clear steps, expected results, and actual results. |
| Fixed defects introduce new issues. | Perform regression testing after bug fixes. |
| Testing is delayed due to unexpected issues. | Prioritize critical test cases and communicate delays. |

## 10. Test Schedule

The following schedule outlines the estimated timeline for testing the Employee Registration feature.

| Testing Activity | Estimated Duration |
|---|---|
| Requirement Analysis | 1 Day |
| Test Scenario Preparation | 1 Day |
| Test Case Design | 2 Days |
| Test Environment Setup | 1 Day |
| Test Execution | 2 Days |
| Defect Reporting and Retesting | 2 Days |
| Regression Testing | 1 Day |
| Test Summary Report Preparation | 1 Day |

**Total Estimated Duration:** 11 Working Days.

Note: The schedule is an estimate and may change depending on application readiness, defect severity, and testing progress.
