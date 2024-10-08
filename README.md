# **Mugikoni Trends API**

This is a RESTful API for Mugikoni Trends, designed to manage ingredients in a food-related application. Developed using Node.js, Express, and PostgreSQL, the API supports full CRUD (Create, Read, Update, Delete) operations for ingredients, along with a search functionality to easily find specific ingredients.

## **Features**

- **Ingredient Management**: Create, update, delete, and retrieve ingredients.
- **Search Functionality**: Search ingredients based on a query parameter.
- **User-Friendly API**: Endpoints are designed with a RESTful approach, ensuring a clean and easy-to-use API.

## **Technologies Used**

- **Node.js**: A JavaScript runtime for building fast and scalable network applications.
- **Express**: A web framework for Node.js that helps manage routes, middleware, and more.
- **PostgreSQL**: A powerful, open-source relational database system used for data storage.
- **Sequelize**: A promise-based Node.js ORM for Postgres, MySQL, MariaDB, SQLite, and Microsoft SQL Server.
- **Morgan**: HTTP request logger middleware for Node.js.
- **Cors**: Middleware to enable Cross-Origin Resource Sharing.

## **API Endpoints**

### **Ingredient Routes**

- `GET /api/ingredients/` - Retrieve all ingredients.
- `GET /api/ingredients/:id` - Retrieve a specific ingredient by its ID.
- `POST /api/ingredients/` - Create a new ingredient.
- `PATCH /api/ingredients/:id` - Update an existing ingredient.
- `DELETE /api/ingredients/:id` - Delete an ingredient.
- `GET /api/ingredients/search?query=salt` - Search for ingredients based on a query parameter.

## **Installation**

1. Clone the repository and navigate to the project directory:
    ```bash
    git clone https://github.com/yourusername/mugikoni-trends-api.git
    cd mugikoni-trends-api
    ```

2. Create a `.env` file in the root directory and add the following environment variables:
    ```env
    PORT=
    DEV_DATABASE_URL=
    ```

3. Run the setup script:
    ```bash
    npm install
    npm start
    ```

## **Usage**

Once the server is running, you can access the API at `http://localhost:5000/` and start making requests to the endpoints.
