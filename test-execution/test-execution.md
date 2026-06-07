| Test Case ID | Test Case Name               | Status | Comment                 |
| ------------ | ---------------------------- | ------ | ----------------------- |
| TC_LOGIN_01  | Successful Login with Valid Credentials          | Pass   | User successfully logged in and Products page opened        |
| TC_LOGIN_02  | Login with Invalid Username                      | Pass   | Error message displayed: Epic sadface: Username and password do not match any user in this service |
| TC_LOGIN_03  | Login with invalid password                      | Pass   | Error message displayed: Epic sadface: Username and password do not match any user in this service |
| TC_LOGIN_04   | Login with Invalid Username and Password        | Pass   | Error message displayed: Epic sadface: Username and password do not match any user in this service     |
| TC_LOGIN_05  | Login with Empty Username    | Pass   | Error message displayed: Epic sadface: Username is required        |
| TC_LOGIN_06  | Login with Empty Password    | Pass   | Error message displayed: Epic sadface: Password is required              |
| TC_LOGIN_07  | Login with Empty Username and Password           | Pass   | Error message displayed: Epic sadface: Username is required        |
| TC_LOGIN_08  | Login with Locked Out User   | Pass   | Error message displayed: Epic sadface: Sorry, this user has been locked out.       |
| TC_LOGIN_09  | Password Masking Verification | Pass   | Password characters were masked successfully  |
| TC_PRODUCT_01  | Verify Product Catalog is Displayed            | Pass   |  Product catalog was displayed correctly and all product items were visible    |
| TC_PRODUCT_02  | Verify Product Information is Displayed Correctly  | Pass   |  All product names, discriptions, prices, images and Add to Cart button were displayed correctly    |
| TC_PRODUCT_03 | Verify Add to Cart Button Functionality                | Pass   |  Product was added to the cart. Cart badge was updated correctly   |
| TC_PRODUCT_04  | Verify Remove Product from Product Page        | Pass   |  Product was removed from the cart. Cart badge was updated correctly    |
| TC_PRODUCT_05  | Verify Product Sorting A to Z                  | Pass   |  Products were displayed alphabetically from A to Z    |
| TC_PRODUCT_06  | Verify Product Sorting Z to A                  | Pass   |  Products are displayed alphabetically from Z to A    |
| TC_PRODUCT_07  | Verify Product Sorting by Price Low to High    | Pass   |  Products were sorted from lowest price to highest    |
| TC_PRODUCT_08  | Verify Product Sorting by Price High to Low    | Pass   |  Products were sorted from highest price to lowest   |
| TC_PRODUCT_09  | Verify Multiple Products Can Be Added to Cart  | Pass   |  All selected products were displayed in the cart. Cart badge displayed correct quantity   |
| TC_PRODUCT_10  | Verify Product Details Page Opens  | Pass   |  Product details page was displayed correctly and all product items were visible    |