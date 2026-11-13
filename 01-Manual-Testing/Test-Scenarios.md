# HRMS Employee Registration – Test Scenarios

## 1. Overview

This document contains the high-level test scenarios identified for the Employee Registration feature of the HRMS application.

## 2. Test Scenarios

| Scenario ID | Test Scenario | Testing Type | Priority |
|---|---|---|---|
| TS_001 | Verify that the Employee Registration form is accessible. | Functional | High |
| TS_002 | Verify employee registration with valid information. | Positive | High |
| TS_003 | Verify validation of all mandatory fields. | Negative | High |
| TS_004 | Verify employee name field validation. | Negative | Medium |
| TS_005 | Verify email address format validation. | Negative | High |
| TS_006 | Verify registration using an already registered email address. | Negative | High |
| TS_007 | Verify phone number field validation. | Negative | High |
| TS_008 | Verify minimum and maximum phone number length. | Boundary | Medium |
| TS_009 | Verify Date of Joining validation. | Negative | High |
| TS_010 | Verify error messages for invalid input data. | Functional | Medium |
| TS_011 | Verify successful submission and confirmation message. | Positive | High |
| TS_012 | Verify that employee information is saved correctly. | Functional | High |

## 3. Notes and Clarifications

The following business rules must be confirmed before finalizing detailed test cases:

1. Minimum and maximum employee name length.
2. Accepted email address format.
3. Whether duplicate email addresses are allowed.
4. Accepted phone number formats and length.
5. Whether future or past joining dates are allowed.
