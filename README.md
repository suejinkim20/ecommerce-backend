# ecommerce-backend

## Description
GIVEN a functional Express.js API

* When the user adds their database name, MySQL username, and MySQL password to an environment variable file,then they are able to connect to a database using Sequelize
* When the user enters schema and seed commands, then a development database is created and is seeded with test data
* When the user enters the command to invoke the application, then their server is started and the Sequelize models are synced to the MySQL database
* When the user opens API GET routes in Insomnia Core for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON
* When the user tests API POST, PUT, and DELETE routes in Insomnia Core, then the user am able to successfully create, update, and delete data in my database

## Usage
This backend application is run on localhost server port 3001, using MySQL to store data and Insomnia Core to interact with the api routes. You will need to install NodeJs, MySQL Workbench, and Insomnia Core.

### Starting the Application
1. To run this application, clone the repository to your local machine and open a terminal in the folder that holds your repository.
2. Make sure to create the database in your MySQL Workbench by running the code from the schema file:
~~~~sql
-- DROP DATABASE
DROP DATABASE IF EXISTS ecommerce_db;

-- CREATE DATABASE
CREATE DATABASE ecommerce_db;
~~~~

![Initialize MySQL](https://media.giphy.com/media/1lVVzDS8w4mmlotb46/giphy.gif)

3. Run the following command in the terminal:

``
npm i && npm run seed
``

4. Once your database is created and seeded, and your node modules are installed, you can start the application by running:

``
npm start
``

![Install, Seed, and Start the Server](https://media.giphy.com/media/Zaom6tMnTdYsDzZdog/giphy.gif)

### API Routes
1. CATEGORY Routes

![Category Routes](https://media.giphy.com/media/2YZCNe18MupldRurgD/giphy.gif)

2. PRODUCT Routes

![Product Routes](https://media.giphy.com/media/se0uu69meq5E7oDCyk/giphy.gif)

3. TAG Routes

![Tag Routes](https://media.giphy.com/media/V61YdhtG98qHGUAVsO/giphy.gif)

