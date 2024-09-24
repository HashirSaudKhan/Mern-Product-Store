# MERN Product Store

A full-stack web application built using the MERN (MongoDB, Express.js, React.js, and Node.js) stack that allows users to add, update, delete, and view products in a store. The application features a user-friendly interface for managing products and a backend API to handle CRUD operations.

## Features

- **Create, Read, Update, and Delete (CRUD)** products.
- **Responsive UI** built using React.js.
- **RESTful API** built with Express.js and Node.js.
- **MongoDB** for storing product data.
- **Mongoose** for data modeling.
- **React Hooks and Context API** for state management.
- **API Error Handling** for robust performance.

## Prerequisites

Before you begin, ensure you have the following installed on your machine:

- Node.js (v14 or higher)
- MongoDB (local or hosted instance)
- Git

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/mern-product-store.git
    ```

2. Navigate to the project directory:
    ```bash
    cd mern-product-store
    ```

3. Install dependencies for both the frontend and backend:
    ```bash
    # For backend
    cd backend
    npm install

    # For frontend
    cd ../frontend
    npm install
    ```

4. Set up environment variables:

    - Create a `.env` file in the `backend` directory and add the following:

    ```env
    MONGO_URI=your-mongodb-connection-string
    PORT=5000
    NODE_ENV=development
    ```

5. Run the development servers:

    - For backend:
      ```bash
      cd backend
      npm run dev
      ```

    - For frontend:
      ```bash
      cd frontend
      npm start
      ```

6. Access the application:

    - Frontend: Open `http://localhost:3000`
    - Backend: Open `http://localhost:5000/api/products`

## Project Structure

```bash
mern-product-store/
├── backend/             # Backend API built with Express.js
│   ├── controllers/     # Product controllers
│   ├── models/          # Mongoose models
│   ├── routes/          # API routes
│   ├── config/          # Configuration files (e.g., MongoDB connection)
│   └── server.js        # Main server file
├── frontend/            # Frontend built with React.js
│   ├── public/          # Public assets
│   ├── src/             # React components and logic
│   └── App.js           # Main App component
├── README.md            # Project documentation
└── package.json         # Project dependencies
