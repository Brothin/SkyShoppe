# SkyShoppe
SkyShoppe is a full-stack MERN e-commerce application designed to provide users with a seamless shopping experience.

## YouTube Demo
https://youtu.be/v8iwPX8mw0w

## Technologies Used
• MongoDB

• Express.js

• React.js

• Node.js

• JWT Authentication

• Braintree for PayPal integration

# Overview and Features
## User Authentication
• Registration: Users can register by providing their details, including name, email, password, phone, address, and a secret question about their favorite sports.

• Login: Authentication is handled using JWT. Users can log in using their email and password.

## Forgot Password Feature
• Resetting Password: If users forget their password, they can reset it by answering the security question about their favorite sports.

## Home Page
• Displaying All Products: The home page showcases all available products.

• Filtering: Users can filter products by category and price range.

• Search: A keyword-based search functionality is available for users.

## Cart Management
• Adding Products to Cart: Users can add products to their cart for future purchase.

• Viewing and Editing Cart: The cart displays all added items, and users can edit or remove them.

• Checkout: Users can complete the purchase using card or PayPal.

## Admin Panel
• Product Management: Admins can add, delete, update, and view all products.

• Category Management: Admins can add, delete, update, and view product categories.

# Getting started

## Clone the repository
```
git clone https://github.com/Brothin/SkyShoppe.git
```
```
cd SkyShoppe
```

## You need
• Node

• MongoDB or Mongo Atlas

• NPM

## Create your MongoDB account and database/cluster
• Create your own MongoDB account by visiting the MongoDB website and signing up for a new account.

• Create a new database or cluster by following the instructions provided in the MongoDB documentation. Remember to note down the "Connect to your application URI" for the database, as you will need it later. Also, make sure to change with your own password.

• Add your current IP address to the MongoDB database's IP whitelist to allow connections (this is needed whenever your ip changes).

## Create your Braintree and paypal account
• SignUp and Login to your Braintree account on https://www.braintreepayments.com/ with your paypal business account.

• On verification of email, you will receive keys to your Sandbox account. Save and store them in your .env file.

## Create .env file
Create a .env file in the server folder to store your credentials. This file will store environment variables for the project to run.
```
PORT = 8080
DEV_MODE = development
MONGO_URL = 'mongodb+srv://<username>:<password>@mongodburlhere'
JWT_SECRET = 'somesuperhardstringtoguess'
BRAINTREE_MERCHANT_ID = 
BRAINTREE_PUBLIC_KEY = 
BRAINTREE_PRIVATE_KEY =
```

## Installation
To install and run this project - 

Install dependencies using npm in root folder and run server side of application.
```
npm install
npm start
```
Install dependencies using npm in client folder and run client side of application.
```
cd client
npm install
npm start
```
