# Rest_API-Python
"Flask REST API for Product Management with SQLAlchemy Integration"

This Git repository contains a Flask application that serves as a REST API for product management. The application utilizes Flask, Flask SQLAlchemy, and Flask Marshmallow to handle HTTP requests, interact with a SQLite database, and serialize/deserialize data.

The application includes the following functionality:

- Retrieving a greeting message at the root endpoint ('/') to verify that the Flask app is working.
- Defining a `Product` model that represents a product with attributes such as name, description, price, and offer.
- Creating routes for CRUD (Create, Read, Update, Delete) operations on products.
  - `POST /product` creates a new product.
  - `GET /product` retrieves all products.
  - `GET /product/{id}` retrieves a single product by its ID.
  - `PUT /product/{id}` updates an existing product.
  - `DELETE /product/{id}` deletes a product.
- Utilizing SQLAlchemy for database management and Flask Marshmallow for object serialization/deserialization.

The application is structured to follow best practices for building REST APIs using Flask and SQLAlchemy. It demonstrates how to define models, create routes, handle HTTP methods, and interact with a database using an ORM.

This project can serve as a starting point for developing a Flask-based REST API for product management, allowing for easy customization and extension to meet specific requirements.
