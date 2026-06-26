| Test Case ID | Test Case Name               | Status | Comment                 |
| ------------ | ---------------------------- | ------ | ----------------------- |
| TC_LOGIN_01  | Successful Login with Valid Credentials          | Pass   | User was logged in successfully  and Products page was displayed      |
| TC_LOGIN_02  | Login with Invalid Username                      | Pass   | Error message displayed: Epic sadface: Username and password do not match any user in this service |
| TC_LOGIN_03  | Login with invalid password                      | Pass   | Error message displayed: Epic sadface: Username and password do not match any user in this service |
| TC_LOGIN_04   | Login with Invalid Username and Password        | Pass   | Error message displayed: Epic sadface: Username and password do not match any user in this service     |
| TC_LOGIN_05  | Login with Empty Username    | Pass   | Error message displayed: Epic sadface: Username is required        |
| TC_LOGIN_06  | Login with Empty Password    | Pass   | Error message displayed: Epic sadface: Password is required              |
| TC_LOGIN_07  | Login with Empty Username and Password           | Pass   | Error message displayed: Epic sadface: Username is required        |
| TC_LOGIN_08  | Login with Locked Out User   | Pass   | Error message displayed: Epic sadface: Sorry, this user has been locked out.       |
| TC_LOGIN_09  | Password Masking Verification | Pass   | Password characters were masked successfully  |
| TC_PRODUCT_01  | Verify Product Catalog is Displayed            | Pass   |  Product catalog was displayed correctly and all product items were visible    |

| Test Case ID | Test Case Name               | Status | Comment                 |
| ------------ | ---------------------------- | ------ | ----------------------- |
| TC_PRODUCT_02  | Verify Product Information is Displayed Correctly  | Pass   |  All product names, descriptions, prices, images and Add to Cart button were displayed correctly    |
| TC_PRODUCT_03 | Verify Add to Cart Button Functionality                | Pass   |  Product was added to the cart and cart badge count increased correctly   |
| TC_PRODUCT_04  | Verify Remove Product from Product Page        | Pass   |  Product was removed from the cart. Cart badge was updated correctly    |
| TC_PRODUCT_05  | Verify Product Sorting A to Z                  | Pass   |  Products were displayed alphabetically from A to Z    |
| TC_PRODUCT_06  | Verify Product Sorting Z to A                  | Pass   |  Products were displayed alphabetically from Z to A    |
| TC_PRODUCT_07  | Verify Product Sorting by Price Low to High    | Pass   |  Products were sorted from lowest price to highest    |
| TC_PRODUCT_08  | Verify Product Sorting by Price High to Low    | Pass   |  Products were sorted from highest price to lowest   |
| TC_PRODUCT_09  | Verify Multiple Products Can Be Added to Cart  | Pass   |  All selected products were displayed in the cart. Cart badge displayed correct quantity   |
| TC_PRODUCT_10  | Verify Product Details Page Opens  | Pass   |  Product details page opened successfully. Product name, description, image price and Add to Cart button were displayed correctly    |

| Test Case ID | Test Case Name               | Status | Comment                 |
| ------------ | ---------------------------- | ------ | ----------------------- |
| TC_CART_01 | Verify Cart Page Opens Successfully  | Pass   |  Cart page opened successfully. "Your Cart" title and correct URL were displayed     |
| TC_CART_02 | Verify Added Product is Displayed in Cart  | Pass   |  Added product was displayed correctly with matching name, description and price    |
| TC_CART_03 | Verify Multiple Products are Displayed in Cart  | Pass   |  All selected products were displayed in the cart without missing items    |
| TC_CART_04 | Verify Product Can Be Removed from Cart  | Pass   |  Product was removed successfully and cart badge count was updated correctly    |
| TC_CART_05 | Verify Continue Shopping Functionality  | Pass   |  User was redirected to the Products page and correct URL was displayed    |
| TC_CART_06 | Verify Checkout Button Functionality  | Pass   |  Checkout Information page opened successfully with correct title and URL    |
| TC_CART_07 | Verify Product Information is Displayed Correctly in Cart  | Pass   |  Product name, description, price and quantity matched the selected product    |
| TC_CART_08 | Verify Empty Cart State  | Pass   |  Empty cart page was displayed correctly and Continue Shopping button was dosplayed and clickable    |
| TC_CART_09 | Verify Cart Badge Updates Correctly  | Pass   |  Cart badge count updated correctly after adding and removing products    |
| TC_CART_10 | Verify Cart Contents Persist After Navigation  | Pass   |  Added products remained in the cart after navigation between pages   |
| TC_CART_11 | Verify Product Quantity is Displayed Correctly  | Pass   |  Product quantity was displayed correctly and matched the number of added products    |
| TC_CART_12 | Verify Cart Badge and Cart Contents Match | Pass   |  Cart badge value matched the number of products displayed in the cart    |

| Test Case ID | Test Case Name               | Status | Comment                 |
| ------------ | ---------------------------- | ------ | ----------------------- |
| TC_CHECKOUT_01 | Verify Checkout Information Page Opens Successfully                    | Pass   | Checkout Information page opened successfully. All required fields, page title and URL were displayed correctly |
| TC_CHECKOUT_02 | Verify Checkout with Valid Information                                 | Pass   | Valid checkout information was accepted and user proceeded to Checkout Overview page                            |
| TC_CHECKOUT_03 | Verify Checkout with Empty First Name                                  | Pass   | Validation message for missing First Name was displayed correctly                                               |
| TC_CHECKOUT_04 | Verify Checkout with Empty Last Name                                   | Pass   | Validation message for missing Last Name was displayed correctly                                                |
| TC_CHECKOUT_05 | Verify Checkout with Empty Postal Code                                 | Pass   | Validation message for missing Postal Code was displayed correctly                                              |
| TC_CHECKOUT_06 | Verify Error Message Display for Required Fields                       | Pass   | Error message was displayed correctly and remained readable when required fields were empty                     |
| TC_CHECKOUT_07 | Verify Cancel Button Functionality                                     | Pass   | User was redirected to the Cart page and correct URL was displayed                                              |
| TC_CHECKOUT_08 | Verify Checkout Overview Page Opens Successfully                       | Pass   | Checkout Overview page opened successfully with correct title and URL                                           |
| TC_CHECKOUT_09 | Verify Product Information is Displayed Correctly in Checkout Overview | Pass   | Product information matched the selected products previously added to the cart             |
| TC_CHECKOUT_10 | Verify Total Price Calculation                 | Pass   | Item total, tax and total amount were calculated and displayed correctly    |
| TC_CHECKOUT_11 | Verify Finish Button Functionality             | Pass   | User was redirected to Checkout Complete page successfully        |
| TC_CHECKOUT_12 | Verify Successful Order Completion                                     | Pass   | Order was completed successfully and confirmation message was displayed                                         |
| TC_CHECKOUT_13 | Verify Back Home Button Functionality                                  | Pass   | User was redirected to the Products page successfully   |
| TC_CHECKOUT_14 | Verify Cancel Button Functionality on Checkout Overview Page           | Pass   | User was redirected from Checkout Overview page to Products page successfully   |
| TC_CHECKOUT_15 | Verify Checkout Information is Retained After Validation Error         | Pass   | Previously entered First Name and Last Name values were preserved after validation error                        |

| Test Case ID | Test Case Name               | Status | Comment                 |
| ------------ | ---------------------------- | ------ | ----------------------- |
| TC_LOGOUT_01 | Verify Menu Button Opens Successfully                  | Pass   | Side menu opened successfully and all available menu options were displayed    |
| TC_LOGOUT_02 | Verify Logout Option is Displayed in Side Menu         | Pass   | Logout option was visible, readable and available for interaction                 |
| TC_LOGOUT_03 | Verify Successful Logout                               | Pass   | User was logged out successfully and redirected to the Login page                 |
| TC_LOGOUT_04 | Verify User is Redirected to Login Page After Logout   | Pass   | Login page and correct URL were displayed after logout                            |
| TC_LOGOUT_05 | Verify Protected Pages Cannot Be Accessed After Logout | Pass   | Logged out user could not access protected pages without authentication           |
| TC_LOGOUT_06 | Verify Browser Back Button After Logout                | Pass   | User could not return to the Products page using browser Back button after logout |

