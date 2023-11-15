# API

# Basic Node API with Get, Post, Patch Methods

This simple Node.js API is designed for handling CRUD operations (Create, Read, Update, Delete) on a MongoDB database. It includes endpoints for creating, retrieving, updating, and deleting products.

## Getting Started

### Prerequisites
- Node.js
- MongoDB
- Postman (for testing)

### Installation
```bash
# Install Node.js modules
npm install

# Install nodemon
npm install -g nodemon

# Install required packages
npm install express mongoose body-parser morgan

#run npm start to start the server on localhost:3001

#use postman tu test the methods

POST: localhost:3001/products
body:

  {
    "name": "somthing",
    "price": "12.3"
  }

GET: localhost:3001/products/id_of_the_product

DELETE: localhost:3001/products/id_of_the_product

PATCH: localhost:3001/products/id_of_the_product
body:

  [
    {"propName":"name","value":"Something else"}
  ]





