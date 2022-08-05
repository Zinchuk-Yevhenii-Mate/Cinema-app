# Cinema app  ![1505719599_178](https://user-images.githubusercontent.com/103262708/183136151-1be1a43f-6817-44a1-a9b5-2732db442d0e.jpg) 

# Project purpose
The Cinema application comprises the basic back-end functionality of a movie tickets online booking web application. 
The project is based on the Spring framework. The program also uses DTO projection and validation when communicating with the client.

# Used technologies
- Java 11
- Apache Maven
- Apache Tomcat
- MySQL
- Hibernate
- Spring Core
- Spring MVC
- Spring Security

# Project structure
The Cinema application is based N-tier architecture. It has 3 layers:

- DAO layers, containing basic CRUD-operations
- Service layers, containing business logic of the application
- Model layers, serves as the data translator for the network

# Database structure
![structure](https://user-images.githubusercontent.com/103262708/183130332-2a61def4-a8e4-4e6d-bf70-0cd24b48539c.jpg)

# How to run this project?
- Clone this project
- Install and configure MySQL and Apache Tomcat
- Setup database parameters in resources/hibernate.cfg.xml
- Set up your Tomcat local server configuration
- Run the application with Tomcat

