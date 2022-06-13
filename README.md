# E-CommerceBackEnd

Week 13: ORM (Object-Relational Mapping)
Back-end development for an E-Commerce based on modified starter code.

## About

Utilizes [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages, connected to Express.js API to a MySQL Database and a [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

A `schema.sql` file in the `db` folder is used to create the SQL database with SQL shell commands. Environment variables are used for sensitive data storage.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Technical Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Funcionality Demo, Video
