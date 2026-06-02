# Cart Test Cases

## TC_CART_01: Verify Cart Page Opens Successfully

### Module

Cart

### Priority

High

### Preconditions

* User is logged in successfully.
* At least one product has been added to the cart.

### Steps

| Step | Action              | Expected Result                     |
| ---- | ------------------- | ----------------------------------- |
| 1    | Click the cart icon | Cart page opens                     |
| 2    | Observe the page    | Cart page is displayed successfully |
| 3    | Verify page title   | "Your Cart" section is displayed    |

### Expected Result

* Cart page opens successfully.
* User can view cart contents.

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_02: Verify Added Product is Displayed in Cart

### Module

Cart

### Priority

High

### Preconditions

* User is logged in successfully.
* One product has been added to the cart.

### Steps

| Step | Action                 | Expected Result                |
| ---- | ---------------------- | ------------------------------ |
| 1    | Click the cart icon    | Cart page opens                |
| 2    | Locate added product   | Product is displayed in cart   |
| 3    | Verify product details | Product information is visible |

### Expected Result

* Added product is displayed in the cart.
* Product information matches the selected product.

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_03: Verify Multiple Products are Displayed in Cart

### Module

Cart

### Priority

High

### Preconditions

* User is logged in successfully.
* Multiple products have been added to the cart.

### Steps

| Step | Action                               | Expected Result                          |
| ---- | ------------------------------------ | ---------------------------------------- |
| 1    | Open cart page                       | Cart page is displayed                   |
| 2    | Verify cart contents                 | All selected products are displayed      |
| 3    | Compare products with selected items | Products match previously selected items |

### Expected Result

* All selected products are displayed in the cart.
* No products are missing.

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_04: Verify Product Can Be Removed from Cart

### Module

Cart

### Priority

High

### Preconditions

* User is logged in successfully.
* At least one product exists in the cart.

### Steps

| Step | Action                  | Expected Result                        |
| ---- | ----------------------- | -------------------------------------- |
| 1    | Open cart page          | Cart page is displayed                 |
| 2    | Click the Remove button | Product is removed                     |
| 3    | Verify cart contents    | Removed product is no longer displayed |

### Expected Result

* Product is removed successfully.
* Cart contents are updated correctly.

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_05: Verify Continue Shopping Functionality

### Module

Cart

### Priority

Medium

### Preconditions

* User is on the Cart page.

### Steps

| Step | Action                             | Expected Result            |
| ---- | ---------------------------------- | -------------------------- |
| 1    | Click the Continue Shopping button | User is redirected         |
| 2    | Observe the page                   | Products page is displayed |

### Expected Result

* User is redirected to the Products page.

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_06: Verify Checkout Button Functionality

### Module

Cart

### Priority

High

### Preconditions

* User is on the Cart page.
* At least one product exists in the cart.

### Steps

| Step | Action                    | Expected Result                        |
| ---- | ------------------------- | -------------------------------------- |
| 1    | Click the Checkout button | Checkout page opens                    |
| 2    | Observe the page          | Checkout information form is displayed |

### Expected Result

* User is redirected to the Checkout page.

### Actual Result

To be filled during test execution.

### Status

Pass / Fail
