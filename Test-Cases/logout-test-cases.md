# Logout Test Cases

## TC_LOGOUT_01: Verify Menu Button Opens Successfully

### Module 

Logout

### Priority

Medium

### Preconditions

- User is logged in successfully
- User is on the Products page

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Locate Menu Button      | Menu Button is displayed       |
| 2    | Click Menu Button       | Side Menu opens                |
| 3    | Observe menu options    | All available menu options are displayed     |

### Expected Result

- Menu Button is displayed
- Menu opens successfully
- Menu options are visible

### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---

## TC_LOGOUT_02: Verify Logout Option is Displayed in Side Menu

### Module 

Logout

### Priority

Medium

### Preconditions

- User is logged in successfully

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Open side menu          | Menu  is displayed             |
| 2    | Locate Logout option    | Logout option is visible       |
| 3    | Verify Logout option    | Logout option is readable and available     |

### Expected Result

- Logout option is displayed correctly

### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---
## TC_LOGOUT_03: Verify Successful Logout

### Module 

Logout

### Priority

High

### Preconditions

- User is logged in successfully

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Open side menu          | Menu is displayed              |
| 2    | Click Logout option     | Logout request is submitted    |
| 3    | Observe page            | Login page is displayed        |
| 4    | Verify URL              | URL contains "/"               |

### Expected Result

- User is logged out successfully
- Login page is displayed
- Login page URL is displayed


### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---

## TC_LOGOUT_04: Verify User is Redirected to Login Page After Logout

### Module 

Logout

### Priority

High

### Preconditions

- User is logged in successfully

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Open side menu          | Menu is displayed              |
| 2    | Click Logout option     | Logout request is submitted    |
| 3    | Verify page URL         | URL contains "/"               |
| 4    | Observe page            | Login page is displayed        |

### Expected Result

- User is redirected to Login page after logout
- Login page URL is displayed


### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---

## TC_LOGOUT_05: Verify Protected Pages Cannot Be Accessed After Logout

### Module 

Logout

### Priority

High

### Preconditions

- User has logged out successfully

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Logout from the application | Login page is displayed    |
| 2    | Enter "/inventory.html" in the browser address bar       | Access request is sent |
| 3    | Observe page            | User remains on Login page     |
| 4    | Verify access          | Products page is not accessible|

### Expected Result

- Logged out user cannot access protected pages
- User remains on the Login page
- Products page is not accessible without authentication


### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---

## TC_LOGOUT_06: Verify Browser Back Button After Logout

### Module 

Logout

### Priority

Medium

### Preconditions

- User is logged in successfully
- User is on Products page

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Open side menu    | Menu is displayed    |
| 2    | Click Logout option     | User is logged out |
| 3    | Observe the page        | Login page is displayed successfully     |
| 4    | Click browser Back button  | Browser attempts to open the previous page |
| 5    | Observe the result        | User remains on Login page or is redirected to the Login page     |
| 6    | Verify access            | Product page is not accessible |


### Expected Result

- Logged out user cannot return to protected pages using browser Back button
- User remains unauthenticated
- Products page is not accessible after logout

### Actual Result

To be filled during test execution.

### Status

Pass / Fail