# MY_E-Commerce Back-End Application



## Description

This project is a back-end solution for an e-commerce website. It uses Express.js as the backend framework and Sequelize as the ORM to interact with a MySQL database. This solution supports CRUD operations for managing products, categories, and tags on the e-commerce platform.

## Demo Video

https://drive.google.com/file/d/1P5ViItFdNjlL7v2YQ70oDyjczAhuIdMq/view?usp=sharing

## Installation

1. Clone the repository to your local machine.

    ```
    git clone https://github.com/billhamilton68/My_E-Commerce_Back-End.git
    ```

2. Navigate to the project directory and install the required npm packages.

    ```
    cd e-commerce-back-end
    npm install
    ```

3. Set up your MySQL database. Make sure MySQL is installed on your machine, and create a `.env` file in the root directory to store your MySQL username and password.

    ```
    # .env
    DB_USER=<your_mysql_username>
    DB_PW=<your_mysql_password>
    DB_NAME='ecommerce_db'
    ```

4. Run the database schema and seed files.
   
5. Start the application.

    ```
    npm start
    ```

## Usage

After installation, you can use  Insomnia to test the API endpoints.

## API Endpoints

- Categories:
  - `GET /api/categories`: Retrieve all categories.
  - `GET /api/categories/:id`: Retrieve a single category by ID.
  - `POST /api/categories`: Create a new category.
  - `PUT /api/categories/:id`: Update a category by ID.
  - `DELETE /api/categories/:id`: Delete a category by ID.

- Products:
  - `GET /api/products`: Retrieve all products.
  - `GET /api/products/:id`: Retrieve a single product by ID.
  - `POST /api/products`: Create a new product.
  - `PUT /api/products/:id`: Update a product by ID.
  - `DELETE /api/products/:id`: Delete a product by ID.

- Tags:
  - `GET /api/tags`: Retrieve all tags.
  - `GET /api/tags/:id`: Retrieve a single tag by ID.
  - `POST /api/tags`: Create a new tag.
  - `PUT /api/tags/:id`: Update a tag by ID.
  - `DELETE /api/tags/:id`: Delete a tag by ID.



