# BoardgameListingWebApp

## Description

**Board Game Database Full-Stack Web Application.**
This web application displays lists of board games and their reviews. While anyone can view the board game lists and reviews, they are required to log in to add/ edit the board games and their reviews. The 'users' have the authority to add board games to the list and add reviews, and the 'managers' have the authority to edit/ delete the reviews on top of the authorities of users.  

## Technologies

- Java
- Spring Boot
- Amazon Web Services(AWS) EC2
- Thymeleaf
- Thymeleaf Fragments
- HTML5
- CSS
- JavaScript
- Spring MVC
- JDBC
- H2 Database Engine (In-memory)
- JUnit test framework
- Spring Security
- Twitter Bootstrap
- Maven

## Features

- Full-Stack Application
- UI components created with Thymeleaf and styled with Twitter Bootstrap
- Authentication and authorization using Spring Security
  - Authentication by allowing the users to authenticate with a username and password
  - Authorization by granting different permissions based on the roles (non-members, users, and managers)
- Different roles (non-members, users, and managers) with varying levels of permissions
  - Non-members only can see the boardgame lists and reviews
  - Users can add board games and write reviews
  - Managers can edit and delete the reviews
- Deployed the application on AWS EC2
- JUnit test framework for unit testing
- Spring MVC best practices to segregate views, controllers, and database packages
- JDBC for database connectivity and interaction
- CRUD (Create, Read, Update, Delete) operations for managing data in the database
- Schema.sql file to customize the schema and input initial data
- Thymeleaf Fragments to reduce redundancy of repeating HTML elements (head, footer, navigation)

## How to Run

1. Clone the repository
2. Open the project in your IDE of choice
3. Run the application
4. To use initial user data, use the following credentials.
  - username: bugs    |     password: bunny (user role)
  - username: daffy   |     password: duck  (manager role)
5. You can also sign-up as a new user and customize your role to play with the application! 😊

## Building a Java Project Using Maven on Ubuntu

1. sudo -i
2. apt update
3. apt install default-java
4. apt install maven -y
5. git clone https://github.com/Krishpluto/BoardgameListingWebApp.git
6. cd BoardgameListingWebApp/
7. mvn clean (Removes the tagret folder inside the project if any )
8. mvn validate  (This will validate the files and folders in side the project)
9. mvn compile   (This will compile the project )
10. mvn test     (This will run the test cases )
11. mvn package  (This will create a jar or war file inside the target folder)
12. Now, go inside the “target” folder and execute the jar file “database_service_project-0.0.1.jar”.
#cd target/
#java -jar database_service_project-0.0.1.jar

Now go to the browser to access the application by entering “public ip address of the instance:8080” (eg: 13.23.45.67:8080), the site should be accessible.

The application will be running in port 8080.

  
