BamazonCustomer

![image](https://user-images.githubusercontent.com/54162286/69511760-12a1c200-0f07-11ea-9a32-aa29542cfc07.png)


Week 12 Homework
Requirements
nodejs 12.13.0
mysql 8.0.11
Installation
Get it from GitHub
GitHub

Or Install the NPM package from npmjs
npm i skbiswas1975/bamazonCustomer

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
