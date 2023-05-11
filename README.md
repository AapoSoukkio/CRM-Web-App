# Project: CRM-Web-App
Spring Boot application with a responsive frontend web app using Vaadin Flow

Made by: Aapo Soukkio

***

## Purpose of this project

The main purpose of this project was to gain hands-on experience with Java and web application
development using Spring Boot and Vaadin. The goal was to become familiar with the techniques
behind these frameworks and to build a functional web application. The project was built by
following the Vaadin Course and implementing the concepts learned throughout the course.

## About the project

The application is a Customer Relationship Management (CRM) system designed to manage contacts,
and it includes features such as a log-in screen, a responsive layout that works on both desktop
and mobile, a database for persistent data storage, a list view that can be sorted and filtered,
a form for editing and adding contacts, a dashboard view, and cloud deployment capabilities.

## Technologies Used

- Java
- Spring Boot
- Vaadin
- Maven
- H2 Database

## About the data

The application accesses the data through the use of Spring Data JPA repositories.

### Data Model

The application uses a model consisting of three main entities:

- Contact: Represents a contact in the CRM system. Each contact belongs to a
  company and has a corresponding status.
- Company: Represents a company in the CRM system. It can have multiple contacts 
  associated with it.
- Status: Represents the status of a contact in the CRM system.

### Seed data

To populate the database with initial sample data, the application utilizes the data.sql
file located in the src/main/resources directory. This file contains SQL statements that
are executed when the application starts up, providing the necessary seed data for demonstration purposes.

### Data access

Instead of directly accessing the database from the view, the application follows a service-oriented approach.
The service class acts as the intermediary between the view and the database. 

By following this architecture, the application separates the concerns of data access and presentation,
promoting modularity and maintainability.

## Features

The application provides the following features:


## How to run the project

1. Clone the project repository to your local machine.
2. Open IntelliJ IDEA and click on "File" -> "New" -> "Project from Existing Sources"
3. Navigate to the directory where you cloned the project and select the "pom.xml" file.
4. Click "Open" and wait for IntelliJ to import the project and download its dependencies.
5. Once the project is imported, navigate to the "src/main/java" directory and open the "Application.java" file.
6. Click on the green "Run" arrow located next to the "main" method or right-click on the file and select "Run Application".
7. Wait for the server to start up and the application to build.
8. Once the application has started, navigate to http://localhost:8080 in your web browser to view the running application.

Note: The first time you start the Vaadin application, it may take some time to download front-end dependencies and build
a JavaScript bundle. Additionally, the development mode in Vaadin will automatically open a browser window for you.
## Tests

Coming soon

### How to run the tests

Coming soon

## Other notes

Coming soon

## Helpful Links

Coming soon
