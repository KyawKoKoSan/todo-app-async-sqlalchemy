# TODO App with SQLAlchemy

A simple asynchronous TODO application built using **Litestar**, **SQLAlchemy**, and **SQLite**. This project demonstrates a clean architecture for managing a task list with CRUD functionality using modern Python frameworks and libraries.

---

## Features
- Fully asynchronous operations using SQLAlchemy's async API.
- SQLite database for lightweight storage.
- RESTful API endpoints for CRUD operations.
- Dependency injection and transaction management.
- Scalable and modular design with plugins for SQLAlchemy.

---

## Requirements
- Python 3.11+
- `pyenv` or other environment managers (optional)
- `pip` or `pipenv` for dependency management

---


## Endpoints

### **GET /**  
- **Description**: Retrieve the list of TODO items.  
- **Query Parameters**:  
  - `done`: Filter tasks by their completion status (`true` or `false`).  
- **Response**: JSON array of TODO items.

### **POST /**  
- **Description**: Add a new TODO item.  
- **Body**: JSON object with the `title` (string) and `done` (boolean) fields.  
- **Response**: The newly created TODO item.

### **PUT /{item_title}**  
- **Description**: Update an existing TODO item by title.  
- **Body**: JSON object with updated `title` and `done` values.  
- **Response**: The updated TODO item.

---

Developed by **Kyaw Ko Ko San**. Contributions and feedback are welcome!
