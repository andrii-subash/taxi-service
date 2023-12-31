# TAXI-SERVICE

## *Description*

This is a simple web application for working with a taxi service.
The application allows to create or delete drivers, cars, manufacturers and attach drivers to the cars.

---
## *Features*
- login as driver
- display all drivers
- display all cars
- display cars by logged driver
- display all manufactures
- add(register)/delete a driver
- add/delete a car;
- add/delete a manufacturer
- add a driver to a car

---

## *Technologies*
- JDK    v.11
- MySQL  v.8.0.22
- TomCat v.9.0.75
- Maven  v.3.1.1
- JSP/JSTL
- CSS
- Servlets
- GIT

---
## *Application run*
- Clone the project to your IDE from GitHub.
- Download/install MySQL and TomCat.
- Execute sql query from file resources/init_db.sql in MySQL Workbench.
- In ConnectionUtil class configure your Url, username, password and JDBC Driver.
- Add Local Tomcat Server into run configuration (click Fix -> taxi-service:war exploded -> set "/" in Deployment/Application context ).

