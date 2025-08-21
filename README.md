🧩 Tech Stack
Backend: Spring Boot (Java 17)
Frontend: Thymeleaf
Database: MySQL
ORM: Spring Data JPA
Build Tool: Maven
🏗️ Project Structure

user-management/
├── src/
│   ├── main/
│   │   ├── java/com/example/usermanagement/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── service/
│   │   │   └── UserManagementApplication.java
│   │   └── resources/
│   │       ├── templates/
│   │       ├── static/
│   │       └── application.properties
└── pom.xml


📦 Features
1. User Login
Simple login form using Thymeleaf.
Authentication logic in the service layer.
Redirect to dashboard on successful login.

3. Create User
Form to input user details (name, email, password, role).
Validation using Spring Boot annotations.
Save user to MySQL using JPA.

5. Update User
Fetch user by ID.
Populate form with existing data.
Save updated data back to the database.

7. Delete User
Delete user by ID.
Confirmation prompt before deletion.
8. View Users
List all users in a table.
Pagination and search (optional).
