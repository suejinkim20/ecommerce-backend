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

Full Walkthrough video can be found at: https://youtu.be/Ccte-qc09hM

## Technologies Used

* Node.js: https://nodejs.org/en/
* Express: https://www.npmjs.com/package/express
* MySQL: https://www.mysql.com/
* Insomnia Core: https://insomnia.rest/


## License

MIT License

Copyright (c) [2021] [Sue Jin Kim]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.