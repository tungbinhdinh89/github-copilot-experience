# 📘 Assignment: REST API with FastAPI

## 🎯 Objective

Build a RESTful API using the FastAPI framework to learn HTTP methods, request/response handling, and API routing. You'll create endpoints that handle GET, POST, PUT, and DELETE operations on a simple resource.

## 📝 Tasks

### 🛠️ Build a FastAPI Application

#### Description

Create a FastAPI application that implements a complete REST API for managing a collection of items. Students will define routes for retrieving, creating, updating, and deleting items using HTTP methods.

#### Requirements

Completed program should:

- Define FastAPI application and create multiple endpoints (GET, POST, PUT, DELETE)
- Implement at least one GET endpoint to retrieve all items
- Implement one GET endpoint with a path parameter to retrieve a specific item
- Implement a POST endpoint to create a new item with request body validation
- Implement a PUT endpoint to update an existing item
- Implement a DELETE endpoint to remove an item
- Use Pydantic models for request/response validation
- Include proper HTTP status codes (200, 201, 400, 404, etc.)
- Run the application using `uvicorn` and test endpoints using curl or Postman


### 🛠️ Add Data Persistence (Optional Enhancement)

#### Description

Extend the API to persist data using a simple file-based storage or in-memory database. This teaches how real applications handle stateful data across requests.

#### Requirements

Completed program should:

- Store item data in a file (JSON) or in-memory list that persists across requests
- Ensure items are retrievable after the application restarts (if using file storage)
- Handle file reading/writing errors gracefully

