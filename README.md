bamazonCustomer


Week 12 Homework
Requirements
nodejs 9.11.1
mysql 8.0.11
Installation
Get it from GitHub
GitHub

Or Install the NPM package from npmjs
npm i keith66fuller/bamazoncustomer

Create database and table and seed the table.
mysql -u username -p database_name < db/products_seed.sql

Modify mysql user/passwd in bamazonCustomer.js lines 6-7.
Running the application.
node bamazonCustomer.js

Using the application
You will be presented with a table products in the database.

At the first prompt, type in the id number of product to purchase.

At the second prompt, type in the desired quantity.

Repeat as necessary.
