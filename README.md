# Note Taking Application

This is a simple Note Taking application built with Spring Boot, designed to demonstrate the capabilities of **Firebase Studio** in a Java development environment.

## Link to Firebase Studio 
  https://idx.google.com/key-concept-63180881
## Project Overview

This project provides a basic REST API for managing notes and notebooks. It's a straightforward example to test the development workflow within Firebase Studio, focusing on the IDE's features for Java projects, dependency management (Maven), and potentially integration with other tools.

The application includes the following main components:

*   **Note:** A simple data model for notes, likely including properties like title, content, and tags.
*   **Notebook:** A data model for organizing notes.
*   **NoteService:** A service layer for handling business logic related to notes and notebooks (e.g., creating, reading, updating, deleting notes).
*   **NoteController:** A REST controller to expose the API endpoints for interacting with the note service.

## Technologies Used

*   **Java:** The core programming language.
*   **Spring Boot:** A framework for building production-ready Spring applications quickly.
*   **Maven:** A build automation tool used for dependency management and project building.
*   **Firebase Studio:** The integrated development environment used for building and testing this project.

## Development Environment: Firebase Studio

This project is being developed and tested within **Firebase Studio**. The primary goal of this project is to explore and showcase the capabilities of Firebase Studio for Java development, including:

*   Code editing and completion
*   Dependency management with Maven
*   Running and debugging Spring Boot applications
*   Terminal access within the IDE
*   (Potentially) Integration with Firebase services, although the core application logic is independent of Firebase for this demonstration.

This project serves as a testbed to evaluate the developer experience of using Firebase Studio for Java-based microservices or web applications.

## Getting Started

### Prerequisites

*   **Firebase Studio:** You need access to and a workspace set up in Firebase Studio.
*   **Java Development Kit (JDK):** Ensure a compatible JDK is configured in your Firebase Studio environment.

### Running the Application

1.  **Clone the Repository:** Clone this repository to your local machine or within your Firebase Studio workspace.
2.  **Open in Firebase Studio:** Open the project in Firebase Studio.
3.  **Run with Maven:** Open the integrated terminal in Firebase Studio and navigate to the project's root directory. Run the following command:
(Alternatively, if you have Maven installed globally, you can use `mvn spring-boot:run`)
4.  **Access the API:** Once the application starts, the API will be available, usually at `http://localhost:8080`.

## API Documentation

This project uses Swagger to provide interactive API documentation. Once the application is running, you can access the Swagger UI at:

*   (If using SpringDoc) `http://localhost:8080/swagger-ui.html`
*   (If using Springfox) `http://localhost:8080/swagger-ui/index.html`

This documentation serves as a "menu" to explore and test the available API endpoints for managing notes and notebooks.

## Project Structure

The project follows a standard Maven project structure: 

## Contribution

This project is primarily for demonstrating Firebase Studio capabilities with Java. Contributions are welcome, especially those that highlight features or improvements related to the development experience within Firebase Studio.

