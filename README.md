# E-commerce Back End

## GitHub Repository
[GitHub](https://github.com/josephptflanagan/200816-E-Commerce-Back-End)

## Video Walktrhough
* [Walkthrough Part 1](https://drive.google.com/file/d/1bO8UdLYcLUwgTkwCVQb_wF-AkHXpk1a7/view)
 
* [Walkthrough Part 2](https://drive.google.com/file/d/1_FXjn4iijYHUcjPHcGCF2id4Vz5jJ54a/view)

* [Using the Schema](https://drive.google.com/file/d/1ChXVJu0ZF_au-ePR6aTAG1JpZpi-PFZO/view)

### Description
This is the back end half of an e-commerce website built with node.js, express, mysql2, and sequelize. It contains a MySQL database that is intereacted with by the express server utilizing sequelize to update the data tables.

### Installation Instructions
* Download code repository. 
* Use npm to install express, sequelize, mysql2, dotenv.
* Create .env file with mysql database information (database name, mysql username and password)
* Use MySQL shell to initialize Database with included schema.sql file.
* Populate Database with seed files using command "npm run seed"
* Start server with "npm start"
* Interact with database using api viewer like Insomnia. 