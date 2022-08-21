# my-retail-store-backend
## -=Project Description=-
This challenge enhanced our knowledge of MYSQL through the use of Sequelize to create, alter, and query our databases. Sequelize allowed us to write more legible code in JavaScript, speeding up the coding process and reducing the risk of errors. With this server, the user has access to an online retail store's database with capabilities to alter categories, products, and product tags.
<br>
<br>

---
## Table of Contents
* [Installation Instructions](#installation)
* [Usage](#usage)
* [Contact Information](#contact)

---

## -=Installation=-
Before running this program, install the *express.js*, *sequelize*, *dotenv*, and *mysql2* dependencies with:
<div style="background-color:rgba(0, 0, 0, 0.25); vertical-align: middle; padding:10px 20px; border-radius: 10px">
npm i
</div>

<br>

Express is used to operate our server providing endpoints for our API routes. Sequelize is used in tandem with mysql2 to create, connect, and alter our database. Lastly, dotenv is used to provide security for the user- providing a .env file for the user to input their database, username and password to connect to their database.

<br>

## -=Usage=-
To run the code, first open your mysql using: 
<div style="background-color:rgba(0, 0, 0, 0.25); vertical-align: middle; padding:10px 20px; border-radius: 10px">
mysql -u root -p
</div> 

<br>
and enter in your password. Then run:
<br><br>

<div style="background-color:rgba(0, 0, 0, 0.25); vertical-align: middle; padding:10px 20px; border-radius: 10px">
SOURCE db/schema.sql; USE ecommerce_db;
</div>

<br>
to create and enter the database. Quit mysql and type in the command line:
<br><br>

<div style="background-color:rgba(0, 0, 0, 0.25); vertical-align: middle; padding:10px 20px; border-radius: 10px">
npm run seed
</div>  

<br>
to seed the data. Finally type:
<br><br>

<div style="background-color:rgba(0, 0, 0, 0.25); vertical-align: middle; padding:10px 20px; border-radius: 10px">
node server.js <em>OR</em> npm start
</div> 

<br>
in the command line of the root directory. 
<br><br>
Since this application is only providing the back-end of the retail store. The use of Insomnia is required to run the api routes to view the database and functionality. 
<br><br>

## -=Contact=-

Checkout out the [walkthrough video](https://drive.google.com/file/d/18HUC2aFBkf28Jk8earnZyGkQavLqIhWS/view) and feel free to look at my other work on my [GitHub](https://github.com/AHudg).

Made by Andrew Hudgins :)