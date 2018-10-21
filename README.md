[![MIT licensed](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/jonathanmusila/store_manager_api/blob/master/LICENSE)

[![Build Status](https://travis-ci.org/jonathanmusila/store_manager_api.svg?branch=master)](https://travis-ci.org/jonathanmusila/store_manager_api)

[![Coverage Status](https://coveralls.io/repos/github/joanathanmusila/store_manager_api/badge.svg?branch=master)](https://coveralls.io/github/jonathanmusila/store_manager_api?branch=master)

[![Code Climate](https://codeclimate.com/github/codeclimate/codeclimate/badges/gpa.svg)](https://codeclimate.com/github/jonathanmusila/store_manager_api)

# Store Manager

Store Manager is a web application that helps store owners manage sales and product inventory records. This application is meant for use in a single store.


## Endpoints

| Endpoint       | Description          |   HTTP-verb  |
| ------------- |:-------------:| -----:| 
| /api/v1/products | Post a product | POST |
| /api/v1/sales  | Post a sale record      | POST   |
| /api/v1/products | Get all products |  GET |
| /api/v1/product/id | Get product by id | GET |
| /api/v1/sales | Get all sale records | GET |
| /api/v1/sales/id | Get a record by id | GET|
| /api/v1/products | Get all a product and update it |  PUT |
| /api/v1/products/id | Get product by id and delete it| DELETE |
| /api/v1/users/register | Post a user | POST |
| /api/v1/users/login | Post a login | POST|

