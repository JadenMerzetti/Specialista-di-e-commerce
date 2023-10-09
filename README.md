
# Demo vide Link
https://drive.google.com/file/d/1Iow53zqxRYwKLLwgL1VLfHxw3ina3PvJ/view

# E-Commerce Backend

## Description

This is a backend application for an e-commerce website that allows you to manage categories, products, and tags. It provides API endpoints to perform CRUD operations on these entities. This application is built using Node.js, Express.js, and Sequelize ORM to interact with a MySQL database.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [API Routes](#api-routes)
- [Contributing](#contributing)
- [License](#license)


Copy code
npm start
The server will start, and you can access the API at http://localhost:3001.

## Usage

You can use this backend application to perform various operations related to categories, products, and tags. You can interact with the API using tools like Insomnia or Postman.

### API Routes

The following API routes are available:

#### Categories:

- `GET /api/categories`: Get a list of all categories.
- `GET /api/categories/:id`: Get a specific category by ID.
- `POST /api/categories`: Create a new category.
- `PUT /api/categories/:id`: Update a category by ID.
- `DELETE /api/categories/:id`: Delete a category by ID.

#### Products:

- `GET /api/products`: Get a list of all products.
- `GET /api/products/:id`: Get a specific product by ID.
- `POST /api/products`: Create a new product.
- `PUT /api/products/:id`: Update a product by ID.
- `DELETE /api/products/:id`: Delete a product by ID.

#### Tags:

- `GET /api/tags`: Get a list of all tags.
- `GET /api/tags/:id`: Get a specific tag by ID.
- `POST /api/tags`: Create a new tag.
- `PUT /api/tags/:id`: Update a tag by ID.
- `DELETE /api/tags/:id`: Delete a tag by ID.

Please make sure to include the necessary request bodies and parameters as specified in the API routes.

## Contributing

Contributions are welcome! If you would like to contribute to this project, please follow these guidelines:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and test them thoroughly.
4. Commit your changes and push them to your fork.
5. Create a pull request with a clear description of your changes.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

