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
| 3    | Verify page title   | "Your Cart" page title is displayed    |
| 4    | Verify cart URL | URL contains "/cart.html" |

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
| 3    | Verify page URL    | URL contains "/inventory.html" |

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
| 3    | Verify checkout page title        | "Checkout: Your Information" title is displayed |
| 4    |Verify checkout URL | URL contains "/checkout-step-one.html"  |

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
- All product details(name, description, price and quantity) are displayed correctly

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
| 2    | Observe cart contents | No products are displayed in the cart |
| 3    | Verify Continue Shopping button| Button is displayed and clickable |

### Expected Result

- Cart page opens successfully in empty state
- No products are displayed in the cart
- Continue Shopping button is available and functional

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_09: Verify Cart Badge Updates Correctly

### Module

Cart

### Priority

High

### Preconditions

- User is logged in successfully
- User is on Products page 

### Steps

| Step | Action                | Expected Result              |
| ---- | --------------------- | ---------------------------- |
| 1    | Add product to cart       | Product is added |
| 2    | Observe cart icon | Cart badge shows 1    |
| 3    | Add another product  | Second product is added |
| 4    | Observe cart badge| Cart badge updates to 2 |
| 5    | Remove product  | Product is removed |
| 6    | Observe cart badge| Cart badge decreases from 2 to 1 |

### Expected Result

- Cart badge reflects correct number of added products at all times

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---
## TC_CART_10: Verify Cart Contents Persist After Navigation

### Module

Cart

### Priority

Medium

### Preconditions

- User is logged in successfully
- At least one  product has been added to the cart

### Steps

| Step | Action                | Expected Result              |
| ---- | --------------------- | ---------------------------- |
| 1    | Open cart page        | Cart page opens successfully |
| 2    | Click Continue Shopping | User is redirected to Products page    |
| 3    | Return to cart page   | Cart page is opened again |
| 4    | Observe cart contents| Previously added products are still present |

### Expected Result

- Cart retains previously added products after navigation between pages

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---
## TC_CART_11: Verify Product Quantity is Displayed Correctly

### Module

Cart

### Priority

Medium

### Preconditions

- User is logged in successfully
- One product has been added to the cart

### Steps

| Step | Action                | Expected Result              |
| ---- | --------------------- | ---------------------------- |
| 1    | Open cart page        | Cart page is displayed |
| 2    | Locate added product| Product is displayed in the cart    |
| 3    | Verify quantity value  | Quantity value is displayed |
| 4    | Verify quantity value equals 1 | Quantity matches the number of added products  |


### Expected Result

- Product quantity is displayed correctly
- Quantity matches the number of added products

### Actual Result

To be filled during test execution.

### Status

Pass / Fail

---

## TC_CART_12: Verify Cart Badge and Cart Contents Match

### Module

Cart

### Priority

Medium

### Preconditions

- User is logged in successfully
- User is on the Products page

### Steps

| Step | Action                | Expected Result              |
| ---- | --------------------- | ---------------------------- |
| 1    | Add first product to cart       | Product is added successfully |
| 2    | Add second product to cart | Product is added successfully    |
| 3    | Observe cart badge  | Cart badge displays value 2 |
| 4    | Open cart page      | Cart page is displayed  |
| 5    | Count products in cart      | Two products are displayed  |
| 6    | Compare cart badge with cart contents | Cart badge value equals the number of products displayed in the cart  |

### Expected Result

- Cart badge displays the correct number of products
- Cart contents match the cart badge value
- No discrepancies are present between pages

### Actual Result

To be filled during test execution.

### Status

Pass / Fail
