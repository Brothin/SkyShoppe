# SkyShoppe
Created a full fledged E‑Commerce application with Backend using Javascript, Node, Express, MongoDB and Mongoose.

# YouTube Demo
https://youtu.be/v8iwPX8mw0w

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
• SignUp and Login to your Braintree account on https://www.braintreepayments.com/ with your paypal business account
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
