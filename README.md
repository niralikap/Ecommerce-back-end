# Ecommerce-back-end

# 13 Object-Relational Mapping

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Description

In this assignment, I have used MySQL and API routes to develop an e-commerce back end application. I have created the database tables in the models folder. I have written code for the API routes. 

I have used the [MySQL2] and [Sequelize] packages to connect the Express.js API to a MySQL database and the [dotenv] package to use environment variables to store sensitive data.

I have used the `schema.sql` file in the `db` folder to create the database with MySQL shell commands. 

The application does the following:

- Given a functional Express.js API - When I add my database name, MySQL username, and MySQL password to an environment variable file, then I am able to connect to a database using Sequelize.

- When I enter schema and seed commands, then a development database is created and is seeded with test data.

- When I enter the command to invoke the application, then my server is started and the Sequelize models are synced to the MySQL database.

- When I open API GET routes in Insomnia for categories, products, or tags, then the data for each of these routes is displayed in a formatted JSON.

- When I test API POST, PUT, and DELETE routes in Insomnia, then I am able to successfully create, update, and delete data in my database.

- In order to run the application, 
-- We use "npm i" command to install the node module. 
-- We use "source schema.sql" to run the schema files in the db folder.
-- We run the seeds data using the command "npm run seed".
-- We run the application using the command "npm start".

![Image](./assets/images/Screen%20Shot1.jpg)
![Image](./assets/images/Screen%20Shot2.jpg)
![Image](./assets/images/Screen%20Shot3.jpg)
![Image](./assets/images/Screen%20Shot4.jpg)


