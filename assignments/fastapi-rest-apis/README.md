# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to design and implement RESTful API endpoints using FastAPI, including request validation, response models, and simple error handling.

## 📝 Tasks

### 🛠️ Create a Basic FastAPI Service

#### Description
Set up a FastAPI app with a health-check endpoint and run it locally.

#### Requirements
Completed program should:

- Create a FastAPI app instance.
- Add a `GET /health` endpoint that returns JSON like `{ "status": "ok" }`.
- Include instructions for running the app with `uvicorn`.

### 🛠️ Build CRUD Endpoints for a Resource

#### Description
Create endpoints for a simple resource (e.g., `books` or `tasks`) with in-memory storage.

#### Requirements
Completed program should:

- Define a Pydantic model for the resource.
- Implement `POST /items` to create a new item.
- Implement `GET /items` to list all items.
- Implement `GET /items/{item_id}` to fetch a single item by ID.
- Return a clear error message if an item ID does not exist.

### 🛠️ Validate Input and Format Responses

#### Description
Add input validation and consistent responses to improve API reliability.

#### Requirements
Completed program should:

- Validate required fields using Pydantic types (e.g., `str`, `int`).
- Return structured JSON responses with appropriate status codes.
- Include at least one example request and response in a code block, such as:
	```http
	POST /items
	Content-Type: application/json

	{
		"name": "Read a book",
		"priority": 2
	}
	```
	```json
	{
		"id": 1,
		"name": "Read a book",
		"priority": 2
	}
	```
