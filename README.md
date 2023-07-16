# Training_Project

An E-commerce website built using JavaScript, React.js, Node.js, MongoDB, and Express.js. The project consists of two modules: user and admin modules.

## Table of Contents
  - Introduction
  - Features
    a) User Module
    b) Admin Module
 - Set up the MongoDB database
 - Schema/model
 - Controllers
 - Routes
 - Middleware
 - Start the server and client


## Introduction

This project is an E-commerce website that allows users to browse and purchase products. It also includes an admin module for managing products, orders, and user data.
The user interface should be user-friendly and easy to navigate, with clear labels and intuitive icons.

## Features

# User Module:
  - User registration and authentication
  - Browse products by category or search
  - Add products to the shopping cart
  - Place orders and make payments
  - View order history
 
# Admin Module:
  - Admin authentication and authorization
  - Manage product inventory
  - Track and fulfil orders
  - View and manage user accounts

Set up the MongoDB database:
- Install MongoDB and make sure it's running on your system.
- Create a new MongoDB database and note down the connection URL.
- Install Mongoose for Creating Schema and Models.
  
## Schema/model
- CardModel
- OrderModel
- ProductModel
- UserModel

## Controllers
  - CartController
  - OrderController
  - ProductController
  - UserController

## Routes
  - get("/:user", getUserCart);
  - post("/:user", createUserCart);
  - put("/:user", addCartItem);
  - put("/qty/:user", updateQty);
  - put("/clear/:user", clearCart);
  - delete("/:user/:_id", deleteCartItem);

## Middleware
 - auth middleware
 - error-handler
 - notFound

## Start the server and client:
- In the `server` directory, run:
  ```
  npm start
  ```
- In the `client` directory, run:
  ```
  npm run dev
  ```


