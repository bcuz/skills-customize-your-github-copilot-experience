# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to build and test RESTful APIs using the FastAPI framework in Python. You will create endpoints, handle requests, and return JSON responses for a simple data model.

## 📝 Tasks

### 🛠️ Task 1: Set Up FastAPI Project

#### Description
Initialize a new FastAPI project and create a basic API endpoint that returns a welcome message.

#### Requirements
Completed program should:
- Install FastAPI and Uvicorn
- Create a main application file (e.g., `main.py`)
- Implement a root endpoint (`/`) that returns a JSON welcome message
- Run the server locally and test the endpoint

### 🛠️ Task 2: Create CRUD Endpoints

#### Description
Design and implement RESTful endpoints for managing a list of items (e.g., books, tasks, or users). Support Create, Read, Update, and Delete operations.

#### Requirements
Completed program should:
- Define a data model using Pydantic
- Implement endpoints for:
  - Listing all items (`GET /items`)
  - Creating a new item (`POST /items`)
  - Retrieving a single item by ID (`GET /items/{id}`)
  - Updating an item (`PUT /items/{id}`)
  - Deleting an item (`DELETE /items/{id}`)
- Return appropriate JSON responses and status codes

### 🛠️ Task 3: Add Basic Validation

#### Description
Add input validation to your endpoints using Pydantic models and FastAPI features.

#### Requirements
Completed program should:
- Validate request data for creating and updating items
- Return error messages for invalid input
- Ensure all endpoints handle errors gracefully

---

**Starter code and requirements.txt will be provided.**
