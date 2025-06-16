# Course Management Backend Project

This is a simple Spring Boot backend project for managing courses. It provides RESTful APIs to create, read, update, and delete course data stored in a MySQL database. This project is part of a course assignment.

---

## Table of Contents
- [About](#about)
- [Technologies Used](#technologies-used)
- [API Endpoints](#api-endpoints)
- [Getting Started](#getting-started)
- [Screenshots](#screenshots)

---

## About

This backend application manages a list of courses. It provides REST APIs for operations such as:

- Fetching all courses  
- Fetching a course by ID  
- Adding a new course  
- Updating an existing course  
- Deleting a course  

The application uses Spring Boot for the REST API and connects to a MySQL database to store course details.

---

## Technologies Used

- Java 21  
- Spring Boot  
- Spring Web
- Spring DATA JPA  
- MySQL
- POSTMAN
- Maven

---

## API Endpoints

| Method | Endpoint          | Description                      |
|--------|-------------------|--------------------------------|
| GET    | `/courses`        | Get all courses                 |
| GET    | `/courses/{id}`   | Get course by ID                |
| POST   | `/course`         | Add a new course                |
| PUT    | `/courses`        | Update an existing course       |
| DELETE | `/courses/{id}`   | Delete course by ID             |

---

## Getting Started

### Prerequisites

- Java JDK installed  
- MySQL server installed and running  
- Maven installed  

### Setup

1. Clone the repository  
   ```bash
   git clone <your-repo-url>

Screenshots
1. Application Running in Postman:
[https://drive.google.com/file/d/1jxoaqA3pwb-YWMGLq9fLsja6hGHlZUOK/view?usp=sharing](https://drive.google.com/file/d/1jxoaqA3pwb-YWMGLq9fLsja6hGHlZUOK/view?usp=sharing)

https://drive.google.com/file/d/1LaWwdS4Sq_kEMZYEZogLJSZh7Ftf3M5P/view?usp=sharing

https://drive.google.com/file/d/1uiwuEtc5RygjK_uj3G3YCmh6WCSYkPip/view?usp=sharing

2. MySQL Database:
[https://drive.google.com/file/d/1K_p5kJDnUUEq_YB3xY5TpfdEuBLCl0zH/view?usp=sharing](https://drive.google.com/file/d/1x2jan28A0vPWdHQQ3gB-2zOT5YJp_2QH/view?usp=sharing)

3. IDE with Server Running:
[https://drive.google.com/file/d/1aZlRGCy4yPP6_Bq_ssJVPWZUP-sZlVa-/view?usp=sharing](https://drive.google.com/file/d/1aZlRGCy4yPP6_Bq_ssJVPWZUP-sZlVa-/view?usp=sharing)
