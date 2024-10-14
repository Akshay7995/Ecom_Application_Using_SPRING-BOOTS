# Ecommerce_Using_SPRING-BOOTS

### **Project Overview:**

This project is the backend of an eCommerce application developed using the Spring Framework, adhering to the MVC (Model-View-Controller) architecture. It is designed to handle client requests efficiently, manage business logic, and interface with an H2 database.

### **Technologies Used:**

-> Spring Boot

-> Spring Data JPA

-> H2 Database

-> Maven

### **Key Features:**

1) MVC Architecture: Follows the MVC pattern to separate concerns, improving scalability and maintainability.

2) Spring Framework: Utilizes Spring Framework for dependency injection, request mapping, and service management.

3) H2 Database Integration: H2 is used to store and retrieve data.

4) Application Port: Runs on https://localhost:8080.

### **Architecture Overview:**

-> Client Request: Users interact with the frontend application, sending HTTP requests to the server.

-> Controller: Spring MVC routes requests based on predefined mappings to appropriate controller classes, which delegate tasks to the service layer.

-> Service Layer: Encapsulates core business logic, such as product management, user authentication, and order processing. It interacts with the repository layer and performs validation, rule enforcement, and other essential operations.

-> Repository Layer: Acts as the bridge between the service layer and the database, utilizing Spring Data JPA or JDBC to perform CRUD operations on data stored in H2.

### **Benefits:**

-> Modular Design: Clear separation of concerns facilitates easier maintenance, testing, and independent development.

-> Flexibility: The MVC pattern allows for customization of individual layers without affecting others.

-> Database Agnostics: Spring Data provides an abstraction layer, enabling easy switching to other databases if needed.

-> Scalability: The modular architecture promotes horizontal scaling to accommodate increased traffic.
