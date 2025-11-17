# Student_Management_APISpringBoot
Student Management API (Spring Boot)

A simple and clean RESTful Student Management API built with Spring Boot, Spring Validation, and Lombok.
This project demonstrates CRUD operations, DTO usage, partial updates with PATCH, and clean controller/service architecture.

🚀 Features

-Get all students
-Get a student by ID
-Create a new student (with validation)
-Update a student (PUT)
-Partially update a student (PATCH)
-Delete a student
-DTO-based request/response
-Clean service-layer architecture

src/main/java/com/example/demo
│
├── controller
│   └── StudentController.java
│
├── service
│   ├── StudentService.java
│   └── StudentServiceImpl.java
│
├── dto
│   ├── Addstudentdto.java
│   └── StudentDto.java
│
└── entity
    └── Student.java
