# Product Test Cases

## TC_PRODUCT_01: Verify Product Catalog is Displayed

### Module 

Products

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
| 2    | Enter valid username and password   | Username and password are entered successfully            |
| 3    | Click the Login button  | User is redirected to the Products page |
| 4    | Observe the Products page | Products page is displayed successfully |
| 5    | Verify product catalog section          | Product catalog is visible   |
| 6    | Verify all products are displayed       | Product items are displayed in the catalog   |

### Expected Result

- Product catalog is displayed
- All available products are visible
- Product items are displayed correctly

### Actual Result

To be filled during test execution.

### Status

Pass / Fail
---


## TC_PRODUCT_02: Verify Product Information is Displayed Correctly

### Module

Products

### Priority

High

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                                     | Expected Result                  |
| ---- | ------------------------------------------ | -------------------------------- |
| 1    | Observe product cards on Products page         | Product cards are displayed         |
| 2    | Observe the product list | Product items are displayed correctly  |
| 3    | Verify product names    | Product names are displayed correctly |
| 4    | Verify product descriptions     | Product descriptions are displayed  correctly     |
| 5    | Verify product prices             | Product prices are displayed correctly   |
| 6    | Verify product images             | Product images are displayed correctly       |
| 7    | Verify Add to Cart button         | Add to Cart button is displayed  correctly       |

### Expected Result

- Product information is displayed correctly
- Product name, description, price and image are visible
- Add to Cart button is available

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---


## TC_PRODUCT_03: Verify Add to Cart Button Functionality

### Module 

Products

### Priority

High

### Preconditions

- User is logged in
- Products page is open

### Steps


| Step | Action                         | Expected Result                 |
| ---- | ------------------------------ | ------------------------------- |
| 1    | Locate any product             | Product is displayed            |
| 2    | Click the Add to Cart button | Product is added to cart        |
| 3    | Observe the button             | Button text changes to Remove |
| 4    | Verify cart badge              | Cart badge count increases by 1   |

### Expected Result

- Product is added to cart
- Cart badge count increases by 1
- Button changes to Remove

### Actual Result

To be filled during test execution

### Status

Pass / Fail
---


## TC_PRODUCT_04: Verify Remove Product from Product Page

### Module

Products

### Priority

High

### Preconditions

- User is logged in successfully
- At least one product has been added to the cart

### Steps

| Step | Action                    | Expected Result                      |
| ---- | ------------------------- | ------------------------------------ |
| 1    | Locate added product      | Remove button is displayed           |
| 2    | Click the Remove button | Product is removed from cart         |
| 3    | Observe the button        | Button text changes to Add to Cart |
| 4    | Verify cart badge         | Cart badge count decreases by 1          |

### Expected Result

- Product is removed from cart
- Cart badge is updated 
- Button changes to Add to Cart

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_PRODUCT_05: Verify Product Sorting A to Z

### Module

Products

### Priority

Medium

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                 | Expected Result                                |
| ---- | ---------------------- | ---------------------------------------------- |
| 1    | Open sorting dropdown  | Sorting options are displayed                  |
| 2    | Select Name (A to Z) | Sorting is applied                             |
| 3    | Observe product order  | Products are sorted alphabetically from A to Z |


### Expected Result

- Products are displayed alphabetically from A to Z

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_PRODUCT_06: Verify Product Sorting Z to A


### Module

Products

### Priority

Medium

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                 | Expected Result                                |
| ---- | ---------------------- | ---------------------------------------------- |
| 1    | Open sorting dropdown  | Sorting options are displayed                  |
| 2    | Select Name (Z to A) | Sorting is applied                             |
| 3    | Observe product order  | Products are sorted alphabetically from Z to A |


### Expected Result

- Products are displayed alphabetically from Z to A

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_PRODUCT_07: Verify Product Sorting by Price Low to High

### Module

Products

### Priority

Medium

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                       | Expected Result                                     |
| ---- | ---------------------------- | --------------------------------------------------- |
| 1    | Open sorting dropdown        | Sorting options are displayed                       |
| 2    | Select Price (Low to High) | Sorting is applied                                  |
| 3    | Observe product order        | Products are sorted by price from lowest to highest |

### Expected Result

- Products are sorted from lowest price to highest

### Actual Result

To be filled during test execution

### Status

Pass / Fail
---


## TC_PRODUCT_08: Verify Product Sorting by Price High to Low

### Module

Products

### Priority

Medium

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                       | Expected Result                                     |
| ---- | ---------------------------- | --------------------------------------------------- |
| 1    | Open sorting dropdown        | Sorting options are displayed                       |
| 2    | Select Price (High to Low) | Sorting is applied                                  |
| 3    | Observe product order        | Products are sorted by price from highest to lowest |

### Expected Result

- Products are sorted from highest price to lowest

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_PRODUCT_09: Verify Multiple Products Can Be Added to Cart
### Module

Products

### Priority

High

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                    | Expected Result                      |
| ---- | ------------------------- | ------------------------------------ |
| 1    | Select the first product  | Product is available for selection   |
| 2    | Click Add to Cart       | Product is added to cart             |
| 3    | Select the second product | Product is available for selection   |
| 4    | Click Add to Cart       | Product is added to cart             |
| 5    | Verify cart badge         | Cart badge displays value 2        |
| 6    | Open the cart             | Cart page is displayed               |
| 7    | Verify cart contents      | Both selected products are displayed |

### Expected Result

- Multiple products can be added to cart
- Cart badge displays correct quantity
- All selected products are present in cart

### Actual Result

To be filled during test execution

### Status

Pass / Fail

---

## TC_PRODUCT_10: Verify Product Details Page Opens
### Module

Products

### Priority

High

### Preconditions

- User is logged in
- Products page is open

### Steps

| Step | Action                    | Expected Result                      |
| ---- | ------------------------- | ------------------------------------ |
| 1    | Locate any product on the Products page  | Product is displayed   |
| 2    | Click the product name       | Product details page is opened             |
| 3    | Observe the product details page | Product information is displayed   |
| 4    | Verify product name    | Product name is displayed correctly |
| 5    | Verify product description     | Product description is displayed correctly     |
| 6    | Verify product price             | Product price is displayed correctly  |
| 7    | Verify product image             | Product image is displayed correctly       |
| 8    | Verify Add to Cart button         | Add to Cart button is displayed correctly  |
| 9    | Click Back to Products button          | User is returned to the Products page   |

### Expected Result

- Product details page opens successfully
- Product informaton is displayed correctly
- Product name, description, price and image are visible

### Actual Result

To be filled during test execution

### Status

Pass / Fail
