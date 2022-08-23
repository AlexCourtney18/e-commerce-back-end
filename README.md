# E-Commerce Back End

## Description
This project is the back-end functionality for an E-commerce website. The back-end features the database that stores the information for the online store in multiple tables. It also contains the necessary routes so the company can add, update, and delete the products, categories, and tags. The back-end utilizes dotenv, express, mysql2, and sequelize to made the code/website more efficient and secure.

## Installation
To use the back-end of the website the user will need to download/clone the code and install the following dependencies:
```
dotenv
express
mysql2
sequelize
```

## Usage
To use the program, the user will need to first create the database using the mysql shell. Once logged into the mysql shell, the command "source db/schema.sql" will create the database. The user will then seed the database's various tables using the command "node seeds/index.js" from the command terminal (not mysql shell). With the database and tables created the user will start the server using the command "npm start". At that point the functionality can be tested using the application Insomnia.

To see the functionality of the program, see the description video:
[Description Video](https://watch.screencastify.com/v/p3wvmVhfbui5MngVe5UR)

