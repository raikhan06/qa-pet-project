# Test Plan

## Project: SauceDemo Testing  

Author: Tazhibaeva Raikhan 
Version: 1.0  
Date: 29 May 2026


# 1. Objective

The purpose of testing is to verify the main functionality of the SauceDemo website and ensure that the application works correctly for end users.
Main areas of testing include:
- Login functionality
- Product catalog
- Shopping cart
- Checkout process
- Logout functionality


# 2. Scope of Testing

## Features to be tested

- Login functionality
- Product catalog page
- Sorting priducts
- Add/remove products from cart
- Shopping cart functionality
- Checkout process
- Logout functionality
- Error message validation
- Basic UI verification

## Features not to be tested

- Performance testing
- Security testing
- Mobile responsiveness
- Payment gateway integration
- API testing


# 3. Test Approach and Strategy 

Testing will be performed manually using prepared test cases and checklists.
The following testing types will be used:
- Functional Testing
- UI Testing
- Positive Testing
- Negative Testing
- Regression Testing
- End-to-End Testing

The main focus areas include:
- Verification of core business functionality
- Validation of positive and negative scenarios
- UI consistency checks
- Verification of error messages
- End-to-end user flow testing

Testing will be executed using Google Chrome browser on Windows 10.

# 4. Test Environment

| Parameter | Value |
|---|---|
| Website | https://www.saucedemo.com |
| Browser | Google Chrome |
| OS | Windows 10 |
| Tool for documentation | VS Code |
| Repository | GitHub |


# 5. Test Data

## Valid user

- Username: standard_user
- Password: secret_sauce

## Locket user (negative login)

- Username: locked_out_user
- Password: secret_sauce

## Problem user (UI/functional issues )

- Username: problem_user
- Password: secret_sauce

## Performance user (slow response simulation )

- Username: performance_glitch_user
- Password: secret_sauce

## Error user (unstable behavior )

- Username: error_user
- Password: secret_sauce

## Visual user (UI rendering issues )

- Username: visual_user
- Password: secret_sauce

## Invalid inputs

- Invalid username
- Invalid password
- Empty fields


# 6. Entry Criteria

Testing will start after:
- The website becomes available
- The test cases and checklists are prepared
- Test environment is ready


# 7. Exit Criteria

Testing will be considered complete after:
- All test cases are executed
- All discovered defects are reported
- Bug reports are prepared
- Test results are documented


# 8. Deliverables

The following documents will be created during testing:
- Test Plan
- Checklists
- Test Cases
- Bug Reports
- Screenshots
- Test Summary Report


# 9. Roles and Responsibilities

| Role | Responsibility |
|---|---|
| QA Engineer | Test planning, test execution, bug reporting |
| Developer | Bug fixing |
| Project Owner | Requirement clarification |


# 10. Bug Severity Levels

| Severity | Description |
|---|---|
| Critical | Application crash or inability to continue testing |
| Major | Main functionality does not work |
| Minor | Small UI or functional issue |
| Trivial | Cosmetic issue |


# 11. Bug Priority Levels

| Priority | Description |
|---|---|
| High | Requires immediate fix |
| Medium | Should be fixed soon |
| Low | Can be fixed later |


# 12. Suspension Criteria

Testing may be suspended if:
- The website becomes unavailable
- Critical defects block further testing
- Test environment issues occur


# 13. Assumptions and Dependencies

- Stable internet connection is available
- Test website is accessible
- Valid test credentials are provided
- Browser is updated to the latest version


# 14. Risks

Possible risks include:
- Changes in the test website
- Unstable internet connection
- Limited test environment
- Unexpected website behavior during testing



# 17. Conclusion

Testing will help evaluate the stability, usability, and correctness of the main functionality of the SauceDemo website. 

The testing process will also help identify defects and improve the overall quality of the application.