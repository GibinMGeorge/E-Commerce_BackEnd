# E-Commerce_BackEnd

This is a back end for an e-commerce site. It is having an Express.js API and it is configured to use Sequelize to interact with a MySQL database.

Insomnia is used to test api routes.

## Installation

initialize npm 

install inquirer package 

install mysql2 package

install sequelize

install dotenv

configure .env file

run the javascript server

## API Routes

Categories

GET /api/categories: Retrieve all categories from the database.
GET /api/categories/:id: Retrieve a specific category by its ID.
POST /api/categories: Create a new category.
PUT /api/categories/:id: Update a category by its ID.
DELETE /api/categories/:id: Delete a category by its ID.

Products

GET /api/products: Retrieve all products from the database.
GET /api/products/:id: Retrieve a specific product by its ID.
POST /api/products: Create a new product.
PUT /api/products/:id: Update a product by its ID.
DELETE /api/products/:id: Delete a product by its ID.

Tags

GET /api/tags: Retrieve all tags from the database.
GET /api/tags/:id: Retrieve a specific tag by its ID.
POST /api/tags: Create a new tag.
PUT /api/tags/:id: Update a tag by its ID.
DELETE /api/tags/:id: Delete a tag by its ID.

## Testing with Insomnia Core

GET Routes: Insomnia Core to test GET routes for categories, products, or tags. Ensure that the data for each route is displayed in a formatted JSON.

POST, PUT, and DELETE Routes: Test POST, PUT, and DELETE routes in Insomnia Core to create, update, and delete data in the database.


## Usage

https://drive.google.com/file/d/1UcxPnYC2Z0bDF5-xUWEmybFJG6zTuwOd/view?usp=sharing


* The URL of the GitHub repository - https://github.com/GibinMGeorge/E-Commerce_BackEnd