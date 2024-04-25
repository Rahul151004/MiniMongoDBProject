# Mini MongoDB Project

This project demonstrates basic CRUD (Create, Read, Update, Delete) operations on a MongoDB database using Express.js and Mongoose.

## Installation

1. Clone the repository:

git clone <https://github.com/Rahul151004/MiniMongoDBProject>


2. Install dependencies:

npm install express mongoose mongodb


3. Set up environment variables:

Create a `.env` file in the root directory with the following contents:
MONGO_URI= Your mongo connection uri

## Usage

1. Start the server:

2. The server will be running at `http://localhost:3002` by default.

## Endpoints

- `GET /users`: Fetch all users from the database.
- `POST /users`: Add a new user to the database.
- `PUT /users/:id`: Update an existing user by ID.
- `DELETE /users/:id`: Remove a user from the database by ID.




