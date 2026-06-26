# CHECKOUT Test Cases

## TC_CHECKOUT_01: Verify Checkout Information Page Opens Successfully

### Module

Checkout

### Priority

High

### Preconditions

- User is logged in successfully
- At least one product has been added to the cart
- User is on the Cart page

### Steps

| Step | Action                   | Expected Result                                 |
| ---- | ------------------------ | ----------------------------------------------- |
| 1    | Click Checkout button    | Checkout Information page opens                 |
| 2    | Verify page title        | "Checkout: Your Information" title is displayed |
| 3    | Verify First Name field  | Field is displayed                              |
| 4    | Verify Last Name field   | Field is displayed                              |
| 5    | Verify Postal Code field | Field is displayed                              |
| 6    | Verify page URL          | URL contains "/checkout-step-one.html"          |

### Expected Result

- Checkout Information page opens successfully
- All required fields are displayed
- Correct URL is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_02: Verify Checkout with Valid Information

### Module

Checkout

### Priority

High

### Preconditions

- User is on Checkout Information page

### Test Data

- First Name: John
- Last Name: Smith
- Postal Code: 10001

### Steps

| Step | Action                  | Expected Result               |
| ---- | ----------------------- | ----------------------------- |
| 1    | Enter valid First Name  | Value is entered successfully |
| 2    | Enter valid Last Name   | Value is entered successfully |
| 3    | Enter valid Postal Code | Value is entered successfully |
| 4    | Click Continue button   | Information is submitted      |
| 5    | Observe result          | Checkout Overview page opens  |

### Expected Result

- User proceeds to Checkout Overview page successfully

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_03: Verify Checkout with Empty First Name

### Module

Checkout

### Priority

High

### Preconditions

- User is on Checkout Information page

### Steps

| Step | Action                       | Expected Result                               |
| ---- | ---------------------------- | --------------------------------------------- |
| 1    | Leave First Name field empty | Field remains empty                           |
| 2    | Enter valid Last Name        | Value is entered                              |
| 3    | Enter valid Postal Code      | Value is entered                              |
| 4    | Click Continue button        | Validation is triggered                       |
| 5    | Verify error message         | "Error: First Name is required" message is displayed |

### Expected Result

- User remains on Checkout Information page
- Error message "Error: First Name is required" is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_04: Verify Checkout with Empty Last Name

### Module

Checkout

### Priority 

High

### Preconditions

- User is on Checkout Information page

### Steps

| Step | Action                      | Expected Result                              |
| ---- | --------------------------- | -------------------------------------------- |
| 1    | Enter valid First Name      | Value is entered                             |
| 2    | Leave Last Name field empty | Field remains empty                          |
| 3    | Enter valid Postal Code     | Value is entered                             |
| 4    | Click Continue button       | Validation is triggered                      |
| 5    | Verify error message        | "Error: Last Name is required" message is displayed |

### Expected Result

- User remains on Checkout Information page
- Error message "Error: Last Name is required" is displayed


### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_05: Verify Checkout with Empty Postal Code

### Module

Checkout

### Priority 

High

### Preconditions

- User is on Checkout Infirmation page

### Steps

| Step | Action                        | Expected Result                                |
| ---- | ----------------------------- | ---------------------------------------------- |
| 1    | Enter valid First Name        | Value is entered                               |
| 2    | Enter valid Last Name         | Value is entered                               |
| 3    | Leave Postal Code field empty | Field remains empty                            |
| 4    | Click Continue button         | Validation is triggered                        |
| 5    | Verify error message          | "Error: Postal Code is required" message is displayed |

### Expected Result

- User remains on Checkout Information page
- Error message "Error: Postal Code is required" is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

# TC_CHECKOUT_06: Verify Error Message Display for Required Fields

### Module

Checkout

### Priority

Medium

### Preconditions

- User is on Checkout Information page

### Steps

| Step | Action                           | Expected Result           |
| ---- | -------------------------------- | ------------------------- |
| 1    | Leave all fields empty           | Fields remain empty       |
| 2    | Click Continue button            | Validation is triggered   |
| 3    | Verify error message visibility  | Error message is visible  |
| 4    | Verify error message readability | Error message is readable |

### Expected Result

- Error message is displayed
- Error message is readable
- User remains on Checkout Information page

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CHECKOUT_07: Verify Cancel Button Functionality

### Module

Checkout

### Priority

Medium

### Preconditions

- User is on Checkout Information page

### Steps

| Step | Action                  | Expected Result           |
| ---- | ----------------------- | ------------------------- |
| 1    | Click Cancel button     | User is redirected        |
| 2    | Verify destination page | Cart page is displayed    |
| 3    | Verify URL              | URL contains "/cart.html" |

### Expected Result

- User returns to Cart page successfully

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CHECKOUT_08: Verify Checkout Overview Page Opens Successfully

### Module

Checkout

### Priority

High

### Preconditions

- User completed Checkout Information successfully

### Steps

| Step | Action                             | Expected Result                         |
| ---- | ---------------------------------- | --------------------------------------- |
| 1    | Complete Checkout Information form | Form is submitted                       |
| 2    | Observe page                       | Checkout Overview page opens            |
| 3    | Verify page title                  | "Checkout: Overview" title is displayed |
| 4    | Verify URL                         | URL contains "/checkout-step-two.html"  |

### Expected Result

- Checkout Overview page is displayed successfully

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_09: Verify Product Information is Displayed Correctly in Checkout Overview

### Module

Checkout

### Priority

High

### Preconditions

- User is on Checkout Overview page

### Steps

| Step | Action                     | Expected Result                  |
| ---- | -------------------------- | -------------------------------- |
| 1    | Verify product name        | Product name is displayed        |
| 2    | Verify product description | Product description is displayed |
| 3    | Verify product price       | Product price is displayed       |
| 4    | Verify quantity            | Product quantity is displayed    |
| 5    | Verify information consistency   | Displayed information matches products previously added to the cart    |

### Expected Result

- Product information matches the selected product

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_10: Verify Total Price Calculation

### Module

Checkout

### Priority

High

### Preconditions

- User is on Checkout Overview page

### Steps

| Step | Action                   | Expected Result                     |
| ---- | ------------------------ | ----------------------------------- |
| 1    | Review item total        | Item total is displayed             |
| 2    | Review tax amount        | Tax amount is displayed             |
| 3    | Review total amount      | Total amount is displayed           |
| 4    | Calculate Item Total + Tax | Calculated amount matches displayed total |

### Expected Result

- Total amount equals Item Total + Tax

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_11: Verify Finish Button Functionality

### Module

Checkout

### Priority

High

### Preconditions

- User is on Checkout Overview page

### Steps

| Step | Action              | Expected Result              |
| ---- | ------------------- | ---------------------------- |
| 1    | Click Finish button | User proceeds to Checkout Complete page  |
| 2    | Observe result      | Checkout Complete page opens |
| 3    | Verify URL          | URL contains "/checkout-complete.html" |

### Expected Result

- User is redirected to Checkout Complete page

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_12: Verify Successful Order Completion

### Module

Checkout

### Priority

High

### Preconditions

- User completed checkout process

### Steps

| Step | Action                    | Expected Result                        |
| ---- | ------------------------- | -------------------------------------- |
| 1    | Complete checkout process | Checkout Complete page opens           |
| 2    | Verify success message    | Success message is displayed           |
| 3    | Verify confirmation text  | Order confirmation text is displayed   |
| 4    | Verify success icon/image | Success icon is displayed |
| 5    | Verify URL                | URL contains "/checkout-complete.html" |



### Expected Result

- Order is completed successfully
- Confirmation message is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_13: Verify Back Home Button Functionality

### Module

Checkout

### Priority

Medium

### Preconditions

- User is on Checkout Complete page

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Click Back Home button  | User is redirected             |
| 2    | Verify destination page | Products page is displayed     |
| 3    | Verify URL              | URL contains "/inventory.html" |

### Expected Result

- User returns to Products page successfully

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_14: Verify Cancel Button Functionality on Checkout Overview Page

### Module

Checkout

### Priority

Medium

### Preconditions

- At least one product has been added to the cart
- Checkout Information form has been completed successfully
- User is on the Checkout Overview page

### Steps

| Step | Action                  | Expected Result                |
| ---- | ----------------------- | ------------------------------ |
| 1    | Verify Cancel button is displayed | Cancel button is visible             |
| 2    | Click Cancel button               | Redirect action is initiated     |
| 3    | Observe destination page          | Products page is displayed |
| 4    | Verify page title | "Products" title is displayed             |
| 5    | Verify URL                        | URL contains “/inventory.html”     |

### Expected Result

- User is redirected to the Products page
- Products page is displayed successfully
- Correct URL is displayed

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CHECKOUT_15: Verify Checkout Information is Retained After Validation Error

### Module

Checkout

### Priority

Medium

### Preconditions

- At least one product has been added to the cart
- User is on the Checkout Information page

### Test Data

- First Name: John
- Last Name: Smith
- Postal Code: Empty

### Steps

| Step | Action                               | Expected Result                                |
| ---- | ------------------------------------ | ---------------------------------------------- |
| 1    | Enter "John" in the First Name field | Value is entered successfully                  |
| 2    | Enter "Smith" in the Last Name field | Value is entered successfully                  |
| 3    | Leave the Postal Code field empty    | Postal Code field remains empty                |
| 4    | Click the Continue button            | Validation is triggered                        |
| 5    | Verify error message                 | "Error: Postal Code is required" message is displayed |
| 6    | Verify First Name field value        | Previously entered value is retained           |
| 7    | Verify Last Name field value         | Previously entered value is retained           |
| 8    | Verify Postal Code field value       | Field remains empty                            |

### Expected Result

- Validation error is displayed for the empty Postal Code field
- User remains on the Checkout Information page
- Previously entered First Name and Last Name values are preserved
- User does not need to re-enter valid information

### Actual Result

To be filled during test execution

### Status

Pass / Fail

