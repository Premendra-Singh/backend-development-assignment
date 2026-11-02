# Backend Development Assignment

A beginner-friendly REST API backend built using Node.js, Express.js, and MongoDB.

## Technologies Used
- Node.js
- Express.js
- MongoDB Atlas
- Mongoose
- Express.js Router
- Postman

## Project Structure

```text
backend-development-assignment/
├── backend/
│   └── src/
│       ├── config/
│       ├── controllers/
│       ├── models/
│       ├── routes/
│       ├── app.js
│       └── index.js
├── .gitignore
├── package.json
└── README.md
```

## Features
- Create posts
- Retrieve all posts
- Update existing posts
- Delete posts
- MongoDB database integration
- REST API testing using Postman

## Installation

1. Clone the repository.
2. Install dependencies:

```bash
npm install
```

3. Create a `.env` file in the project root:

```env
PORT=4000
MONGODB_URI=your_mongodb_connection_string
```

4. Start the development server:

```bash
npm run dev
```

## API Endpoints

| Method | Endpoint | Operation |
|---|---|---|
| POST | `/api/v1/posts/create` | Create post |
| GET | `/api/v1/posts/getPosts` | Get all posts |
| PATCH | `/api/v1/posts/update/:id` | Update post |
| DELETE | `/api/v1/posts/delete/:id` | Delete post |

## API Testing

All CRUD operations can be tested using Postman.

## Author
Premendra Singh

This project was developed as part of an academic backend development assignment. The project structure and implementation concepts were studied with reference to the following tutorial repository:

Reference Repository: Introduction to Backend

Tutorial Creator: Shivani

Topics Referenced: Node.js, Express.js, MongoDB integration, Mongoose models, REST API development, and CRUD operations.

The reference material was used for learning and understanding backend development concepts. The project was configured, tested, and prepared for this assignment.
