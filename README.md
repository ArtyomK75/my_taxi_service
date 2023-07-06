## my_taxi_service![img.png](img.png)
# Description
Simple web application that supports authentication, registration and other CRUD operation.

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
- MySQL

# Instructions:
- Before run app, you need run script from the resources/init_db.sql file in the Workbench.
- change database connection parameters in the class main.java.taxi.util.ConnectionUtil
- adjust debug configuration options on TomCat 8.5.- or 9.5.-
- run app and register first user/driver, after that login under registered user

I have also deployed this example. Web app here:
http://mytaxiapp-env.eba-rvzifcmg.eu-north-1.elasticbeanstalk.com/login
