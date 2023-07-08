## my_taxi_service![img.png](img.png)
# Description
Taxi service it's a simple web application that supports authentication, registration, allows customers to create entity
of database and show them in the relevant pages of the application. It provides basic CRUD (Create, Read, Update,
Delete) functionality.

# Features:
- registration user like a driver;
- authentication user;
- create/update/remove a driver;
- create/update/remove a manufacturer;
- create/update/remove a car;
- display list of drivers;
- display list of manufacturers;
- display list of cars;

# Technologies Used
- Java 11
- Maven 3.1.1
- Apache Tomcat
- Java Servlet API
- JSP
- JSTL
- MySQL 8.0.28

# Instructions:
- Before running the app, you need to run a script from the resources/init_db.sql file in the Workbench.
- change database connection parameters in the class main.java.taxi.util.ConnectionUtil
- adjust debug configuration options on TomCat 8.5.- or 9.5.-
- run the app and register the first user/driver, after that log in under the registered user

I have also deployed this example. Web app here:
http://mytaxiapp-env.eba-rvzifcmg.eu-north-1.elasticbeanstalk.com/login
