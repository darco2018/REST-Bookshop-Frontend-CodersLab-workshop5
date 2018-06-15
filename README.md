
# Bookshop
**A REST API** application with **JSON**  for running a bookshop  or cataloguing books. It is split into 2 separate projects: backend and frontend.
The application was started in March 2018 as workshop 4 during my participation in a **`Coders Lab` Java backend course**.

#### Current functionality
The fronend runs on Tomcat at http://localhost:8080/Workshop5/. The backend runs on Spring Boot's embedded Tomcat http://localhost:8081/bookStore/books. The backend uses a simple in-memory mock database to serve a book controller at these endpoints: /delete/{id}, /ad, /{id}, /.

The frontend displays a form to add a new book and displays the list of books in the database. When a book is clicked, the details of the book are revealed. One can also delete a book.

#### Oncoming improvements
* add a database and Hibernate ORM
* add JUNIT tests
* add  Publisher, Author, Review entities and CRUD for them
* add validation
* decorate with Bootstrap

#### Technologies and tools used
```
* Java 8
* Spring Boot 2.0.0
* Jackson
* Java Script, JQuery, Ajax, Bootstrap 3, HTML, CSS
* Tomcat
* Maven, Spring Tool Suite
```
# REST-Bookshop-Frontend-CodersLab-workshop5
