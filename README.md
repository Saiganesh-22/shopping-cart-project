# Shopping Cart Project

## Overview

This project is a simple Shopping Cart application built using JavaScript, HTML, and CSS.

The application allows users to:

* View available products
* Add products to the shopping cart
* Increase product quantity
* Decrease product quantity
* Remove products from the cart
* Calculate the cart total
* Process payments
* Display the remaining balance or change to return
* Empty the cart after successful checkout

---

## Features

### Product Management

* Displays a list of available products.
* Each product contains:

  * Product Name
  * Price
  * Quantity
  * Product ID
  * Product Image

### Shopping Cart Operations

Users can:

* Add products to the cart
* Increase quantity of products
* Decrease quantity of products
* Remove products from the cart

### Checkout System

The checkout system:

* Calculates the total cart value
* Accepts customer payment
* Displays remaining balance when payment is insufficient
* Displays change when payment exceeds the total
* Clears the cart after successful payment

---

## Technologies Used

* HTML
* CSS
* JavaScript
* Node.js
* Jest

---

## Project Structure

shopping-cart-project
│
├── src
│   ├── assets
│   │   ├── front.js
│   │   ├── script.js
│   │   └── styles.css
│   │
│   ├── images
│   │   ├── cherry.jpg
│   │   ├── orange.jpg
│   │   └── strawberry.jpg
│   │
│   └── index.html
│
├── tests
│   └── script.test.js
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md

---

## Functions Implemented

### addProductToCart(productId)

Adds a product to the shopping cart and increases its quantity.

### increaseQuantity(productId)

Increases the quantity of a selected product.

### decreaseQuantity(productId)

Decreases the quantity of a selected product.

### removeProductFromCart(productId)

Removes a product completely from the cart.

### cartTotal()

Calculates and returns the total value of the shopping cart.

### pay(amount)

Processes customer payment and returns:

* Positive value → change to return
* Negative value → remaining balance

### emptyCart()

Clears all items from the cart.

---

## Running the Project

### Install Dependencies

npm install

### Run Tests

npm run test

### Start Application

Open index.html using Live Server in Visual Studio Code.

---

## Test Results

All automated tests pass successfully.

Test Suites: 1 passed
Tests: 10 passed
Snapshots: 0 total

---

## Future Improvements

* Clear receipt history after successful payment
* Add product search functionality
* Add currency conversion feature
* Add local storage support
* Improve user interface design

---

## Author

N. Sai Ganesh Yadav
