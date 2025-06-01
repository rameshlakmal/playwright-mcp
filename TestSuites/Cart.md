# Instructions

- Run "Before Each Test case" section before running each test case.
- Run "After Each Test case" section after running each test case.

# Before Each Test case

- Login to the website use https://www.saucedemo.com/v1/
- User Username and password given in the [User Data](/TestData/UserData.md).

# Ater Each Test case

- Close the web browser.

# Test Cases

## TC 001 - Verify that user can add an item to the cart

### Priority : High

- Add Sauce Labs Backpack to the cart
- Verify that "Add To Cart" button text changed to "Remove"
- Verify that value in the cart icon on the top right corner changed to "1"

## TC 002 - Verify that user can remove an item from the cart

### Priority : High

- Click "Remove" button on the Sauce Labs Backpack item
- Verify that "Remove" button text changed to "Add to Cart"
- Verify that value "1" get removed from the cart icon on the top right corner

## TC 003 - Verify that user can view items in the cart

### Priority : High

- Add Sauce Labs Bolt T-Shirt to the cart
- Verify that "Add To Cart" button text changed to "Remove"
- Verify that value in the cart icon on the top right corner changed to "1"
- Click on Sauce Labs Fleece Jacket text
- Verify that user redirects to "https://www.saucedemo.com/v1/inventory-item.html?id=5" URl
- Click "Add to Cart" button
- Verify that "Add To Cart" button text changed to "Remove"
- Verify that value in the cart icon on the top right corner changed to "2"
- Click cart icon
- Verify that user redirects to the "https://www.saucedemo.com/v1/cart.html" URL
- Verify that Sauce Labs Bolt T-Shirt and Sauce Labs Fleece Jacket should be in the cart with 1 QTY for each
