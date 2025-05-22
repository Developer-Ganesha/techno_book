# Book Management API

A RESTful API for managing books with JWT authentication.

## Features

- User registration and authentication
- CRUD operations for books
- Input validation
- SQLite database (can be configured for PostgreSQL)

## API Endpoints

- `POST /register` - Register a new user
- `POST /login` - Login and get JWT token
- `GET /protected` - Test authentication
- `GET /books` - List all books
- `POST /books` - Create a new book
- `GET /books/{id}` - Get a specific book
- `PUT /books/{id}` - Update a book
- `DELETE /books/{id}` - Delete a book

## Deployment

This API is configured for deployment on Render.
