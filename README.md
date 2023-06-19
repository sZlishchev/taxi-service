# taxi-service
 This is a simple project to show my Java, JDBC, WEB, OOP, and SOLID skills. In this project, I used basic CRUD operations. One-to-one, one-to-many, and many-to-many relationships are used in databases.
# Available functionality
* register a driver
* log in/out
* create/read/update a car
* create/read/update a manufacturer
* create/read/update a driver
* display list of all cars
* display list of all manufacturers
* display list of all drivers
# Project structure
* Controller - accepts requests from the user, passes them to the service layer, and returns jsp pages in response
* Service - accepts requests from the controller, passes them to the DAO layer, and performs all business logic
* DAO - accepts requests from the service, passes them to the DB, and executes all sql queries
# Technologies:
* Tomcat 9.0.50
* Maven
* MySQL
* JDBC
* Java 11
* JSP
* JSTL
* Servlet Api
# Installation:
1. Create DB using local MySQL or remote database. You can find schema in init_db.sql file.
2. Put our DB url, username, password, and JDBC driver into ConnectionUtil.class.
   ![image](https://github.com/sZlishchev/taxi-service/assets/110261412/f084d0d9-30d6-479c-92d5-58062e750bb0)
3. Install Apache Tomcat v.9.x.x.
4. Clone this project from GitHub.
5. Configure Tomcat server.
# You can try working version
AWS link: http://taxi-service-app-env.eba-py9ypppp.eu-north-1.elasticbeanstalk.com/
