# University Management API

A backend RESTful API built with **FastAPI** and **SQLAlchemy** for managing university data, including students, professors, and courses.

The system implements full CRUD functionality with strong data validation and a clean layered architecture.

---

## 🚀 Features

- Student, Professor, and Course management (CRUD operations)
- Robust data validation layer to ensure data integrity
- SQLAlchemy ORM for database interactions
- Modular and scalable project structure
- Clean separation of concerns (CRUD / Models / Schemas / Validation)
- RESTful API design using FastAPI
- Docker support for containerized deployment

---

## 🏗️ Tech Stack

- Python 3.12
- FastAPI
- SQLAlchemy
- Pydantic
- SQLite
- Docker

---

## 📁 Project Structure

- `main.py` → API routes and endpoints  
- `models.py` → Database models  
- `schemas.py` → Pydantic schemas  
- `crud.py` → Database operations  
- `datavalidation.py` → Input validation logic  
- `database.py` → Database configuration  

---

## 📌 API Endpoints

### Students
- `POST /create_student/`
- `GET /get_student/{student_stid}`
- `PUT /update_student/{student_stid}`
- `DELETE /delete_student/{student_stid}`

### Professors
- `POST /create_professor/`
- `GET /get_professor/{professor_lid}`
- `PUT /update_professor/{professor_lid}`
- `DELETE /delete_professor/{professor_lid}`

### Courses
- `POST /create_course/`
- `GET /get_course/{course_cid}`
- `PUT /update_course/{course_cid}`
- `DELETE /delete_course/{course_cid}`

---

## 📊 Project Highlights

This project demonstrates:

- Backend API development using FastAPI
- Clean architecture with modular design
- Strong data validation and error handling
- Database modeling using ORM (SQLAlchemy)
- Practical implementation of a real-world CRUD system
- Understanding of scalable backend structure

---

## 👩‍💻 Author

Computer Engineering student focused on backend development, mobile applications, and software engineering.
