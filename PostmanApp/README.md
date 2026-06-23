# PostmanApp

A simple Spring Boot CRUD REST API application developed using Java 17, Spring Data JPA, Hibernate, and MySQL. The application allows users to perform Create, Read, Update, and Delete (CRUD) operations on Student records and test APIs using Postman.

## Technologies Used

* Java 17
* Spring Boot
* Spring Data JPA
* Hibernate
* MySQL
* Maven
* Postman

## Features

* Add Student
* Get Student by ID
* Update Student
* Delete Student
* Get All Students
* Save Multiple Students
* Count Students
* Check Student Exists

## API Endpoints

| Method | Endpoint     | Description            |
| ------ | ------------ | ---------------------- |
| POST   | /save        | Save Student           |
| GET    | /findBy/{id} | Find Student by ID     |
| PUT    | /edit/{id}   | Update Student         |
| DELETE | /delete/{id} | Delete Student         |
| GET    | /findall     | Get All Students       |
| POST   | /inputlist   | Save Multiple Students |
| GET    | /count       | Count Students         |
| GET    | /exists/{id} | Check Student Exists   |

## Run the Project

1. Create a MySQL database named `postman`
2. Update database credentials in `application.properties`
3. Run:

```bash
mvn spring-boot:run
```

Application runs on:

```text
http://localhost:9090
```

## Author

Kishan P M
