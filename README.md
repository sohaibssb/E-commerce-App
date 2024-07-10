# E-commerce-App


Backend service that manages users, products, and orders. It is built with NodeJS and Express, uses MongoDB for data storage, and provides a RESTful API for client interactions. Also JWT for authentication.

## Features

- User registration and authentication
- Product management (CRUD operations)
- Order management
- Secure password handling with AES encryption
- Authentication using JSON Web Tokens (JWT)

## Tools and Libraries

- **NodeJS**: JavaScript runtime for building server-side applications
- **Express**: Web framework for NodeJS
- **MongoDB**: NoSQL database for storing application data
- **Mongoose**: ODM for MongoDB
- **CryptoJS**: Library for encryption and decryption
- **Nodemon**: Utility to automatically restart the server on code changes
- **Dotenv**: Module to load environment variables from a `.env` file
- **JWT (jsonwebtoken)**

## Setup and Installation

### Prerequisites

- NodeJS (v14 or higher)
- MongoDB (v4 or higher)
- npm (v6 or higher)

### Installation Steps

1. **Clone the repository**

    ```bash
    git clone https://github.com/sohaibssb/E-commerce-App.git
    cd E-commerce-App
    ```

2. **Install dependencies**

    ```bash
    npm install
    ```

3. **Create a `.env` file**

    ```bash
    touch .env
    ```

    Add the following environment variables to the `.env` file:

    ```
    MONGO_URL=mongodb://localhost:27017/ecommerce
    PASS_SEC=your_secret_key
    ```

4. **Run the application**

    ```bash
    npm start
    ```

    The server will start on `http://localhost:5000`