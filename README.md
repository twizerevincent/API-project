# Spring Boot API Project

This is a sample Spring Boot API project that demonstrates basic CRUD (Create, Read, Update, Delete) operations for managing users.

## Technologies Used

- Java
- Spring Boot
- Spring Data JPA
- MySQL (or any other relational database)
- Maven

## Project Structure

The project is structured as follows:

- **User.java**: Entity class representing a user with `id`, `name`, and `email` fields.
- **UserRepository.java**: Repository interface for performing CRUD operations on the `User` entity.
- **UserService.java**: Service class containing business logic for managing users.
- **UserController.java**: REST controller for handling HTTP requests related to user management.
- **application.yml**: Application configuration file specifying database connection details and other properties.
  
## Usage

1. Make sure you have MySQL installed and running.
2. Configure the database connection details in the `application.yml` file.
3. Run the application using Maven or your preferred IDE.
4. Access the API endpoints to perform CRUD operations on users:
   - GET `/api/users`: Get all users.
   - GET `/api/users/{id}`: Get a user by ID.
   - POST `/api/users`: Create a new user.
   - PUT `/api/users/{id}`: Update an existing user.
   - DELETE `/api/users/{id}`: Delete a user by ID.

## Running the Application

To run the application locally, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the project in your preferred IDE (such as IntelliJ IDEA or Eclipse).
4. Configure the database connection details in the `application.yml` file.
5. Build and run the application.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.


