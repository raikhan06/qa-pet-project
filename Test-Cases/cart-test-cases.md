# Cart Test Cases

## TC_CART_01: Verify Cart Page Opens Successfully

### Module

Cart

### Priority

High

### Preconditions

- User is logged in successfully
- At least one product has been added to the cart

### Steps

| Step | Action              | Expected Result                     |
| ---- | ------------------- | ----------------------------------- |
| 1    | Click the cart icon | Cart page opens                     |
| 2    | Observe the page    | Cart page is displayed successfully |
| 3    | Verify page title   | "Your Cart" section is displayed    |
| 4    | Verify cart URL   | Cart page URL is displayed correctly   |

### Expected Result

- Cart page opens successfully
- User can view cart contents

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CART_02: Verify Added Product is Displayed in Cart

### Module

Cart

### Priority

High

### Preconditions

- User is logged in successfully
- One product has been added to the cart

### Steps

| Step | Action                 | Expected Result                |
| ---- | ---------------------- | ------------------------------ |
| 1    | Click the cart icon    | Cart page opens                |
| 2    | Locate added product   | Product is displayed in cart   |
| 3    | Verify product name    | Product name is displayed correctly |
| 4    | Verify product description   | Product description is displayed correctly     |
| 5    | Verify product price         | Product price is displayed correctly   |
| 6    | Verify product image         | Product image is displayed correctly       |

### Expected Result

- Added product is displayed in the cart
- Product information matches the selected product

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_CART_03: Verify Multiple Products are Displayed in Cart

### Module

Cart

### Priority

High

### Preconditions

- User is logged in successfully
- Multiple products have been added to the cart

### Steps

| Step | Action                               | Expected Result                          |
| ---- | ------------------------------------ | ---------------------------------------- |
| 1    | Open cart page                       | Cart page is displayed                   |
| 2    | Verify cart contents                 | All selected products are displayed      |
| 3    | Verify displayed products | Products match previously selected products |

### Expected Result

- All selected products are displayed in the cart
- No products are missing

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

- User is logged in successfully
- At least one product exists in the cart

### Steps

| Step | Action                  | Expected Result                        |
| ---- | ----------------------- | -------------------------------------- |
| 1    | Open cart page          | Cart page is displayed                 |
| 2    | Click the Remove button | Product is removed                     |
| 3    | Verify cart contents    | Removed product is no longer displayed |
| 4    | Verify cart badge    | Cart badge count decreases by 1 |

### Expected Result

- Product is removed successfully
- Cart contents are updated correctly

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

- User is on the Cart page

### Steps

| Step | Action                             | Expected Result            |
| ---- | ---------------------------------- | -------------------------- |
| 1    | Click the Continue Shopping button | User is redirected to the Products page        |
| 2    | Observe the page                   | Products page is displayed |

### Expected Result

- User is redirected to the Products page

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

- User is on the Cart page
- At least one product exists in the cart

### Steps

| Step | Action                    | Expected Result                        |
| ---- | ------------------------- | -------------------------------------- |
| 1    | Click the Checkout button | Checkout page opens                    |
| 2    | Observe the page          | Checkout information form is displayed |
| 3    | Verify checkout page title        | Checkout information page is displayed |

### Expected Result

- User is redirected to the Checkout page

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_07: Verify Product Information is Displayed Correctly in Cart

### Module

Cart

### Priority

Medium

### Preconditions

- User is logged in successfully
- Product has been added to the cart

### Steps

| Step | Action                     | Expected Result                  |
| ---- | -------------------------- | -------------------------------- |
| 1    | Open cart page             | Cart page is displayed           |
| 2    | Verify product name        | Product name is displayed correctly       |
| 3    | Verify product description | Product description is displayed correctly|
| 4    | Verify product price       | Product price is displayed correctly      |
| 5    | Verify product quantity      | Product quantity is displayed correctly      |

### Expected Result

- Product information in cart matches the selected product from Products page
- All product details(name, description, price, quantity) are displayed correctly

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_08: Verify Empty Cart State

### Module

Cart

### Priority

Medium

### Preconditions

- User is logged in successfully
- No products are added to the cart

### Steps

| Step | Action                | Expected Result              |
| ---- | --------------------- | ---------------------------- |
| 1    | Open cart page        | Cart page opens successfully |
| 2    | Observe cart contents | No products are displayed    |
| 3    | Verify cart message/state | Empty cart state is shown(no items message or empty list) |
| 3    | Verify Continue Shopping button| Button is displayed and clickable |

### Expected Result

- Cart page opens successfully in empty state
- No products are displayed
- User can continue shopping via Continue Shopping button

### Actual Result

To be filled during test execution.

### Status

Pass / Fail


