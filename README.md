E-Commerce Web Application
==========================

This is an e-commerce web application built with the MERN (MongoDB, Express.js, React.js, Node.js) stack. The application includes features like user authentication, product search, cart management, and handling of ordered and refunded products.

Features
--------

*   **User Authentication**: Secure login and signup functionality.
    
*   **Product Search**: Search products and view product details.
    
*   **Cart Management**: Add and remove products from the cart.
    
*   **Order Management**: View ordered and refunded products.
    
*   **Responsive Design**: Fully responsive layout for all devices.
    

Tech Stack
----------

*   **Frontend**: React.js
    
*   **Backend**: Node.js, Express.js , Razorpay
    
*   **Database**: MongoDB
    
*   **Styling**: CSS, CSS Modules
    

Getting Started
---------------

### Prerequisites

*   Node.js
    
*   npm or yarn
    
*   MongoDB
    

### Installation
```bash
1.git clone https://github.com/major0001/E-commerce_Website-ALX-Project
    
1.  cd server
2.  npm install
    
3.   cd ../client    
4.   npm install

```

### Environment Variables

Create a .env file in the server directory and add the following environment variables:

```
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  
RAZORPAY_KEY_ID=your_razorpay_key_id  
RAZORPAY_KEY_SECRET=your_razorpay_key_secret   `
```
### Running the Application

```bash
1. cd server 
2. npm start
    
3.  cd ../client 
4.  npm start

```
API Endpoints
-------------

### Authentication

*   **POST** /api/v1/signup - Register a new user
    
*   **POST** /api/v1/login - Authenticate user and get token
    

### Payment

*   **GET** /api/v1/getkeyid - Get Razorpay Key ID
    
*   **POST** /api/v1/capturepayment - Capture payment
    
*   **POST** /api/v1/refundpayment - Refund payment
    
*   **GET** /api/v1/fetchallpayments - Fetch all payments
    
*   **GET** /api/v1/getpaymentdetails/:id - Get payment details by ID
    
*   **GET** /api/v1/fetchcarddetails - Fetch card details
    
*   **POST** /api/v1/paymentverification - Verify payment

POSTMAN LINK - https://www.postman.com/roy707/workspace/shop-cart/collection/32632569-0177389f-3ffc-4d24-a8bb-9c869782bc67?action=share&creator=32632569

### Cart Management

*   **POST** /api/v1/addtocart - Add product to cart
    
*   **DELETE** /api/v1/removefromcart - Remove product from cart
    
*   **POST** /api/v1/showcartitems - Show all cart items
    

### Order Management

*   **POST** /api/v1/orderedproducts - Show all ordered products
    
*   **POST** /api/v1/refundedproducts - Show all refunded products

### DB Schema
<img width="928" alt="Ecommerce_DB" src="https://github.com/user-attachments/assets/c8e92ab8-3088-4f8a-902e-35a5d62f8fa7">

Contribution
------------

Feel free to submit issues or pull requests if you have suggestions or improvements.

License
-------

This project is licensed under the MIT License.
