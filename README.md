# ecommerce-backend

## Description
GIVEN a functional Express.js API

WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize

WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data

WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database

WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON

WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database

## Usage
This backend application is run on localhost server port 3001, using MySQL to store data and Insomnia to interact with the api routes. You will need to install node, mysql workbench, and insomnia.

1. To run this application, clone the repository to your local machine and open a terminal in the folder that holds your repository.
2. make sure to create the database in your MySQL Workbench by running the code from the schema file:
~~~~sql
-- DROP DATABASE
DROP DATABASE IF EXISTS ecommerce_db;

-- CREATE DATABASE
CREATE DATABASE ecommerce_db;
~~~~

3. Run the following command in the terminal:

``
npm i && npm run seed
``

4. Once your database is created and seeded, and your node modules are installed, you can start the application by running:

``
npm start
``


