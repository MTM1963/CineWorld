# 🎥🎥Cinema-app🎥🎥

# Project decription:
- 🫡Welcome to the Cinema App project!🫡
- 😉This is a web application that provides various features including authentication, registration, and CRUD (Create, Read, Update, Delete) operations😉
- The project is built using the Hibernate and Spring frameworks, which provide powerful tools for interacting with databases and developing robust web applications.
-  With the Cinema App, users can enjoy a simplified and user-friendly experience while managing cinema-related data and operations.
  
## Setup

To set up the project, follow these steps:

### Prerequisites

Make sure you have the following software installed on your system:

- Java Development Kit (JDK) 11 or higher
- Apache Maven
- Apache Tomcat vesion 9 or higher
- DataBase: MySQL

### Installation
- First of all, you should made your fork
- Second, clink on Code<> and clone link, after that open your Intellij Idea, click on Get from VCS
- past link, which you clone later

### Replace Placeholders:
To connect to your DB, you should replace PlaceHolders in db.properties
- Open package resources and open file db.properties in your project.
Locate the placeholders that need to be replaced.
These placeholders might include values such as
db.driver=YOUR_DRIVER - replace with com.mysql.cj.jdbc.Driver
db.url=YOUR_DATABASE_URL - - You should change this with the actual URL of your database. This typically includes the database provider, host, port, and  database name. For example: jdbc:mysql://localhost:3306/mydatabase.
db.user=YOUR_USERNAME - replace with your username to DB
db.password=YOUR_PASSWORD - replace with your password to DB


# Features 🤌:

## User  🤵‍♂️
- Registration like a user
- Authentication like a user
- Create/update/remove a user
- Display all users from the list

## Movie 🎥 
- Create/update/remove a movie
- Display all movies from the list

## Cinema-Hall 🏢
- Create/update/remove a cinema-hall
- Display all cinema-halls from the list

## Shopping-cart 💵
- Create/updare/remove a shopping-cart
- Add  movie-session and user to shopping-cart
- Get shopping-cart by user
- Clear shopping-cart

## Order 💵
- Create/update/remove a order
- Complete order by shopping-cart
- Get order history by user

## Movie-Session ⏱
- Create/update/remove a movie-session
- Get available movie-session by movieId and LocalDate
- Display all movie-sessions from the list

## Role 🙎‍♂️
- Create/update/remove a role
- Get user role by roleName

## Authentication
- Registration user

