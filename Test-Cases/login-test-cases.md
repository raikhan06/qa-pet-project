# Login Test Cases

## TC_LOGIN_01: Successful Login with Valid Credentials

### Module 

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page
- Valid test credentials are available

### Test Data

- Username: standard_user
- Password: secret_sauce

### Steps

| Step | Action                                      | Expected Result                             |
| ---- | ------------------------------------------- | ------------------------------------------- |
| 1    | Open https://www.saucedemo.com              | Login page is displayed                     |
| 2    | Enter "standard_user" in the Username field | Username is entered successfully            |
| 3    | Enter "secret_sauce" in the Password field  | Password is entered successfully and masked |
| 4 | Click the Login button | User is redirected to the Products page |
| 5    | Observe Products page                       | Product catalog is displayed successfully   |

### Expected Result

- User is logged in successfully
- Products page is displayed
- Product catalog is accessible

### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---


## TC_LOGIN_02: Login with Invalid Username

### Module

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page.

### Test Data

- Username: invalid_user
- Password: secret_sauce

### Steps

| Step | Action                                     | Expected Result                  |
| ---- | ------------------------------------------ | -------------------------------- |
| 1    | Open https://www.saucedemo.com             | Login page is displayed          |
| 2    | Enter "invalid_user" in the Username field | Username is entered successfully |
| 3    | Enter "secret_sauce" in the Password field | Password is entered successfully and masked |
| 4    | Click the Login button                     | Login request is submitted       |
| 5    | Observe the result                         | User remains on the Login page   |
| 6    | Verify error message                       | Error message is displayed       |

### Expected Result

- Login is not successful
- User remains on the Login page
- Error message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---


## TC_LOGIN_03: Login with invalid password

### Module 

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page
- Valid test credentials are available

### Test Data

- Username: standard_user
- Password: invalid_password

### Steps

| Step | Action                                         | Expected Result                  |
| ---- | ---------------------------------------------- | -------------------------------- |
| 1    | Open https://www.saucedemo.com                 | Login page is displayed          |
| 2    | Enter "standard_user" in the Username field    | Username is entered successfully |
| 3    | Enter "invalid_password" in the Password field | Password is entered successfully and masked |
| 4    | Click the Login button                         | Login request is submitted       |
| 5    | Observe the result                             | User remains on the Login page   |
| 6    | Verify error message                           | Error message is displayed       |

### Expected Result

- Login is not successful
- User remains on the Login page
- Error message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail
---


## TC_LOGIN_04: Login with Invalid Username and Password

### Module

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page.

### Test Data

- Username: invalid_user
- Password: invalid_password

### Steps

| Step | Action                 | Expected Result                  |
| ---- | ---------------------- | -------------------------------- |
| 1    | Open https://www.saucedemo.com  | Login page is displayed          |
| 2    | Enter "invalid_user" in the Username field | Username is entered successfully |
| 3    | Enter "invalid_password" in the Password field | Password is entered successfully |
| 4    | Click Login button     | Login request is submitted       |
| 5    | Observe the result     | User remains on Login page       |
| 6    | Verify error message   | Error message is displayed       |

### Expected Result

- Login is not successful
- User remains on the Login page
- Appropriate error message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_LOGIN_05: Login with Empty Username

### Module

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page.

### Test Data

- Username: <empty>
- Password: secret_sauce

### Steps

| Step | Action                     | Expected Result                              |
| ---- | -------------------------- | -------------------------------------------- |
| 1    | Open https://www.saucedemo.com      | Login page is displayed                      |
| 2    | Leave Username field empty | Username field remains empty                 |
| 3    | Enter valid password in the Password field  | Password is entered successfully and masked             |
| 4    | Click Login button         | Login request is submitted                   |
| 5    | Verify result              | User remains on Login page                   |
| 6    | Verify error message       | Epic sadface: Username is required |

### Expected Result

- Login is not successful
- User remains on the Login page
- Username required error message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_LOGIN_06: Login with Empty Password

### Module

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page.

### Test Data

- Username: standard_user
- Password: <empty>

### Steps

| Step | Action                     | Expected Result                              |
| ---- | -------------------------- | -------------------------------------------- |
| 1    | Open https://www.saucedemo.com      | Login page is displayed                      |
| 2    | Enter valid username in the Username field   | Username is entered successfully             |
| 3    | Leave Password field empty | Password field remains empty                 |
| 4    | Click Login button         | Login request is submitted                   |
| 5    | Verify result              | User remains on Login page                   |
| 6    | Verify error message       | Password required error message is displayed |

### Expected Result

- Login is not successful
- User remains on the Login page
- Password required error message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_LOGIN_07: Login with Empty Username and Password

### Module

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page

### Test Data

- Username: <empty>
- Password: <empty>

### Steps

| Step | Action                     | Expected Result                              |
| ---- | -------------------------- | -------------------------------------------- |
| 1    | Open https://www.saucedemo.com      | Login page is displayed                      |
| 2    | Leave Username field empty | Username field remains empty                 |
| 3    | Leave Password field empty | Password field remains empty                 |
| 4    | Click Login button         | Login request is submitted                   |
| 5    | Verify result              | User remains on Login page                   |
| 6    | Verify error message       | Username required error message is displayed |

### Expected Result

- Login is not successful
- User remains on the Login page
- Username required error message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail
---


## TC_LOGIN_08: Login with Locked Out User

### Module

Login

### Priority

High

### Preconditions

- User is on the SauceDemo login page.

### Test Data

- Username: locked_out_user
- Password: secret_sauce

### Steps

| Step | Action                  | Expected Result                            |
| ---- | ----------------------- | ------------------------------------------ |
| 1    | Open https://www.saucedemo.com   | Login page is displayed                    |
| 2    | Enter "locked_out_user" in the Username field | Username is entered successfully           |
| 3    | Enter "secret_sauce" in the Password field     | Password is entered successfully and masked       |
| 4    | Click Login button      | Login request is submitted                 |
| 5    | Observe the page after login attempt        | User remains on Login page                 |
| 6    | Observe the displayed error message    | Locked out user error message is displayed |

### Expected Result

- Login is not successful
- User remains on the Login page
- Error message indicating the user is locked out is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_LOGIN_09: Password Masking Verification

### Module

Login

### Priority

Medium

### Preconditions

- User is on the SauceDemo login page.

### Steps

| Step | Action                     | Expected Result                  |
| ---- | -------------------------- | -------------------------------- |
| 1    | Open https://www.saucedemo.com      | Login page is displayed          |
| 2    | Click Password field       | Cursor appears in Password field |
| 3    | Enter "secret_sauce" in the Password field   | Password is entered              |
| 4    | Observe entered characters | Characters are masked            |

### Expected Result

- Password characters are not visible
- Entered password is not visible in plain text

### Actual Result

To be filled during test execution

### Status

Pass / Fail

