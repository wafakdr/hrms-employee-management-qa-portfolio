# BR_001 – Employee Registration Accepts Invalid Email

## 1. Bug Information

| Field | Details |
|---|---|
| Bug ID | BR_001 |
| Bug Title | Employee Registration Accepts Invalid Email |
| Module | Employee Registration |
| Severity | To be determined |
| Priority | To be determined |
| Environment | To be updated |
| Status | Unverified |
| Reported By | QA Tester |
| Reported Date | 13-Nov-2026 |

## 2. Preconditions

- Employee registration page is accessible.
- The user can enter employee details.
- Email validation is expected to be performed.

## 3. Steps to Reproduce

1. Open the Employee Registration page.
2. Enter valid information in all mandatory fields.
3. Enter an invalid email address, such as `wafa@invalid`.
4. Click the Submit or Register button.
5. Observe the application's response.

## 4. Test Data

| Field | Test Data |
|---|---|
| Employee Name | Test Employee |
| Email | wafa@invalid |
| Phone | 9876543210 |
| Joining Date | 16-Nov-2026 |

## 5. Expected Result

The application should reject the invalid email address and display a clear validation message.

## 6. Actual Result

Not yet verified. Update this section only after reproducing the issue.

## 7. Evidence

Screenshot or screen recording to be attached after testing.

## 8. Additional Information

This issue is currently an unverified defect scenario. Confirm the actual application behaviour before reporting it as a confirmed bug.
