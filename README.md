E-Commerce Backend Application

This repository contains the backend code for an e-commerce application built using Node.js, Express.js, and Sequelize ORM. The application provides API endpoints to manage products, categories, and tags, allowing users to perform CRUD operations (Create, Read, Update, Delete) on these entities.
![Uploading image.png…]()


video
[Untitled_ Mar 4 2024 11_15 PM.webm](https://github.com/BryceGitHuba/E-Commerce/assets/149907275/35a6d261-0906-48c8-9f50-a22ea341f9e5)

Features
Create, Read, Update, and Delete products
Create, Read, Update, and Delete categories
Create, Read, Update, and Delete tags
Associate products with categories and tags
Error handling for invalid requests
Data validation and integrity checks using Sequelize ORM
Automatic generation of API documentation using Swagger UI
Installation
Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/your-username/e-commerce-backend.git
Navigate to the project directory:
bash
Copy code
cd e-commerce-backend
Install dependencies using npm or yarn:
bash
Copy code
npm install
or
bash
Copy code
yarn install
Set up the database:
Create a MySQL database named ecommerce_db.
Modify the .env file with your MySQL database credentials.
Seed the database with sample data:
bash
Copy code
npm run seed
Usage
Start the server:
bash
Copy code
npm start
Access the API endpoints using an API client like Postman or Insomnia.
Use the provided API documentation to explore available endpoints and their functionalities.
API Documentation
API documentation is available through Swagger UI. After starting the server, navigate to http://localhost:3001/api-docs in your web browser to access the API documentation.

Endpoints
Products

GET /api/products: Get all products
GET /api/products/:id: Get a single product by ID
POST /api/products: Create a new product
PUT /api/products/:id: Update a product by ID
DELETE /api/products/:id: Delete a product by ID
Categories

GET /api/categories: Get all categories
GET /api/categories/:id: Get a single category by ID
POST /api/categories: Create a new category
PUT /api/categories/:id: Update a category by ID
DELETE /api/categories/:id: Delete a category by ID
Tags

GET /api/tags: Get all tags
GET /api/tags/:id: Get a single tag by ID
POST /api/tags: Create a new tag
PUT /api/tags/:id: Update a tag by ID
DELETE /api/tags/:id: Delete a tag by ID
Contributing
Contributions are welcome! Feel free to open issues or submit pull requests to improve the application.

License
This project is licensed under the MIT License.
