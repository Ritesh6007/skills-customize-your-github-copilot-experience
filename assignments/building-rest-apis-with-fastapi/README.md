# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build a simple REST API using the FastAPI framework in Python, including routing, request validation, and JSON responses.

## 📝 Tasks

### 🛠️ Set up a FastAPI project

#### Description
Create a new FastAPI application and configure it to run with a simple set of routes. Install any required dependencies and verify the app starts correctly.

#### Requirements
Completed project should:

- Create a FastAPI app instance in a Python file
- Include a root endpoint that returns a welcome message
- Use the correct HTTP method and route definitions
- Start the app locally so it can accept requests

### 🛠️ Build CRUD routes for a resource

#### Description
Implement a set of RESTful endpoints to manage a sample resource, such as `items` or `books`. Use Pydantic models for request and response validation.

#### Requirements
Completed API should:

- Support creating a new resource with `POST`
- Support reading a resource by ID with `GET`
- Support updating a resource with `PUT` or `PATCH`
- Support deleting a resource with `DELETE`
- Use Pydantic models for input validation and response serialization

### 🛠️ Add query parameters and error handling

#### Description
Enhance the API with query parameter support and proper HTTP error handling for invalid or missing resources.

#### Requirements
Completed API should:

- Accept query parameters for filtering or searching resources
- Return a `404` response when a resource is not found
- Return a `400` response for invalid request data
- Include descriptive JSON error messages for failure cases
