# Chitchat

A team-developed web application built with **Java, Spring Boot, PostgreSQL and Angular**.

Chitchat is a platform where users can create and join themed chat sessions, communicate with other participants and manage their profiles.

The project was developed as part of my previous Java software development training and provided practical experience with backend development, relational databases, authentication, external service integrations and collaborative Git workflows.

---

## 🚀 Main Features

- User registration and authentication
- JWT-based authentication and authorization
- User roles and permissions
- User profiles
- Creation and management of Chitchat sessions
- Categories, languages and language levels
- Participant management
- Session capacity and scheduling
- Messaging between participants
- Message read status
- File and avatar storage using AWS S3
- Email notifications
- Internationalization
- REST API documentation with OpenAPI / Swagger

---

## 🛠 Tech Stack

### Backend

- Java 17
- Spring Boot 3
- Spring Web
- Spring Security
- JWT
- Spring Data JPA
- Hibernate
- REST API
- WebSocket
- Maven

### Database

- PostgreSQL
- SQL
- H2 for testing

### External Services & Tools

- AWS S3
- Spring Mail
- Google Calendar API
- OpenAPI / Swagger
- Checkstyle

### Frontend

- Angular 15
- TypeScript
- Angular Material

The frontend was developed as part of the team application, while my main focus was on **backend development and application logic**.

---

## 🏗 Project Architecture

Chitchat is organized as a Maven multi-module project:

- `chitchat` — Spring Boot backend
- `front` — Angular frontend

The backend is responsible for application logic, authentication, authorization, persistence and external service integrations.

The frontend communicates with the backend through the application API.

The PostgreSQL data model includes entities and relationships for:

- users
- roles
- user profiles
- Chitchat sessions
- participants
- categories
- languages
- messages
- message read status
- refresh tokens

The backend application entry point is:

`chitchat/src/main/java/com/group/chitchat/ChitchatApplication.java`

The application is configured to run on port `5000`.

---

## 👨‍💻 My Contribution

My main focus in the project was backend development.

I worked with:

- Spring Boot application development
- REST API development
- Spring Security
- JWT authentication and authorization
- User roles and permissions
- PostgreSQL and relational data
- JPA / Hibernate persistence
- AWS S3 file storage
- Email notifications
- Internationalization
- Automated testing

The project was developed collaboratively using **Git, branches and pull requests**, which provided practical experience working with a shared codebase and integrating changes from multiple developers.

---

## 🔐 Security

Authentication is implemented using **Spring Security and JWT**.

The application uses access and refresh tokens and supports role-based authorization for protected functionality.

Sensitive configuration such as database credentials, JWT secrets and external service credentials is provided through environment variables rather than being stored directly in the source code.

---

## 🧪 Development & Quality

The project uses **Maven** for dependency management and build automation.

The complete multi-module project can be built with:

```bash
mvn clean install
```

Code style validation is integrated through **Checkstyle**.

Backend development is located under:

`chitchat/src/main/java/com/group/chitchat`

The Angular frontend is maintained as a separate module and included in the Maven project structure.

Running the complete application requires additional configuration, including a PostgreSQL database and environment variables for the connected services.

---

## 🤝 Team Project

Chitchat was created as a collaborative training project.

This repository is a **fork of the original team repository** and preserves the original project structure and development history.

The project gave me practical experience with:

- working in a shared repository
- feature branches
- pull requests
- integrating changes from multiple developers
- working with an existing application architecture
- developing features across different parts of a larger codebase

---

## 📚 What I Learned

Chitchat gave me practical experience with the complete backend application flow:

**HTTP request → REST controller → application logic → persistence → PostgreSQL**

It also provided experience with authentication, authorization, external services, relational data modelling and collaborative software development.

This project became an important foundation for my further focus on **backend development, application architecture and database-driven applications**.
