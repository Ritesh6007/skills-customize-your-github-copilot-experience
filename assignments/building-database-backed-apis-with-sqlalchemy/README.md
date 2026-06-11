# 📘 Assignment: Building Database-Backed APIs with SQLAlchemy

## 🎯 Objective

Learn how to connect FastAPI to a database using SQLAlchemy, define models, and build CRUD APIs that persist data in a real database.

## 📝 Tasks

### 🛠️ Define SQLAlchemy models and database setup

#### Description
Create the database connection and define a SQLAlchemy model for a resource such as `Item` or `Book`. Configure the app to create tables automatically when the application starts.

#### Requirements
Completed project should:

- Configure a SQLAlchemy `engine` and `session` for a local SQLite database
- Define a SQLAlchemy model class with appropriate fields
- Create database tables automatically on startup
- Include a database session dependency for FastAPI routes

### 🛠️ Implement CRUD endpoints with database persistence

#### Description
Build REST API routes that use SQLAlchemy to create, read, update, and delete database records.

#### Requirements
Completed API should:

- Create a resource with `POST` and store it in the database
- Read a resource by ID with `GET`
- Update a resource with `PUT` or `PATCH`
- Delete a resource with `DELETE`
- Use the database session in each route to persist changes

### 🛠️ Add validation and database error handling

#### Description
Enhance the API with Pydantic validation and proper error responses for invalid input or missing records.

#### Requirements
Completed API should:

- Use Pydantic models for request and response validation
- Return a `404` error when a record is not found
- Handle invalid request data with a `400` response
- Provide clear JSON error messages for failure cases
