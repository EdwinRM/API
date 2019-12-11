# API
Basic node API with the Get, Post, Patch methods

#install node modules
#nodemon
#install express
#install mongoose
#install body-parser
#morgan

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





