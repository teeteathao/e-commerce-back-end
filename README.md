# Object-Relational Mapping (ORM): E-Commerce Back End

## Description

Internet retail, also known as **e-commerce**, is the largest sector of the electronics industry, generating an estimated $29 trillion in 2019. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. Building the back end for an e-commerce site by modifying starter code. Configured a working Express.js API to use Sequelize to interact with a MySQL database.

## Usage

Given a functional Express.js API, I add my database name, MySQL username, and MySQL password to an environment variable file. Then I am able to connect to a database using Sequelize. When I enter schema and seed commands then a development database is created and is seeded with test data. In Insomnia, the GET routes for categories, products, or tags will display the data for each of these routes in a formatted JSON. Additionally, the API POST, PUT, and DELETE routes in Insomnia will create, update, and delete data in the database.

## Visual

The following animation shows the application's GET routes to return all categories, all products, and all tags being tested in Insomnia:

![In Insomnia, the user tests “GET tags,” “GET Categories,” and “GET All Products.”.](./Assets/13-orm-homework-demo-01.gif)

The following animation shows the application's GET routes to return a single category, a single product, and a single tag being tested in Insomnia:

![In Insomnia, the user tests “GET tag by id,” “GET Category by ID,” and “GET One Product.”](./Assets/13-orm-homework-demo-02.gif)

The following animation shows the application's POST, PUT, and DELETE routes for categories being tested in Insomnia:

![In Insomnia, the user tests “DELETE Category by ID,” “CREATE Category,” and “UPDATE Category.”](./Assets/13-orm-homework-demo-03.gif)


## Walkthrough Video 

https://watch.screencastify.com/v/x4nWIRdA2pM7LqBphVj9


